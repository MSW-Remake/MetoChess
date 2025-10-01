# Penalty System - Penalty List

## Overview
MetoChess's penalty system provides a total of 46 diverse penalties across 4 levels. Each penalty constrains specific aspects of the game or strengthens enemies to implement progressive difficulty increase.

## Penalty Classification by Level

### Level 0: Basic Constraint Penalties (PEN00XXX)

Introductory penalties that impose basic game system constraints.

#### PEN00001: Remove Round Defeat Reward
- **Effect**: Remove the 5-coin additional reward received upon round defeat
- **Impact**: Increase defeat cost by removing economic cushion

#### PEN00002: Rune Card Unsellable/Indestructible Tag
- **Effect**: 30% chance to apply 'Unsellable and Indestructible' tag when rune cards appear in shop
- **Impact**: Reduce flexibility in rune card management

#### PEN00003: Rune Card Burn Tag
- **Effect**: 30% chance to apply 'Burn after 5 rounds' tag when rune cards appear in shop
- **Impact**: Limit rune card sustainability

### Level 1: Enemy Stat Enhancement Penalties (PEN1XXXX)

Direct difficulty increase penalties that enhance all enemy units' basic stats.

#### Attack-related Enhancements
- **PEN10001**: All enemies +15% attack power
- **PEN10002**: All enemies +15% magic power
- **PEN10005**: All enemies +15% attack speed
- **PEN10006**: All enemies +30% critical chance

#### Defense-related Enhancements
- **PEN10003**: All enemies +30 physical defense
- **PEN10004**: All enemies +30 magic defense
- **PEN10008**: All enemies +225 maximum HP

#### Skill-related Enhancements
- **PEN10007**: All enemies +22 starting MP

### Implementation Pattern Example
```lua
-- PEN10001: 15% attack power increase
for _, unit in pairs(teamManager.EnemyUnits) do
    if unit.UnitAIWanderComponent.Enable then
        _StatusChangeLogic:GetBuff(unit, "Multi_PhysicalAttack", 15, -1)
    end
end
```

### Level 2: System Constraints and Additional Enemies (PEN2XXXX)

Intermediate penalties that constrain game systems themselves or add special conditions.

#### Shop System Constraints
- **PEN20001**: Legendary grade doesn't appear in rune card shop (excluding coach effects)
- **PEN20002**: All item box selection count reduced by 1

#### Additional Enemy Spawn
- **PEN20003**: Add 1 scarecrow to enemy team
  - Gets progressively stronger proportional to stage
  - Automatic tanker item equipment system

```lua
-- Scarecrow spawn and enhancement
self.SetUnit = _UnitSetLogic_New:SpawnEnemyUnit(ownerId, "C00000", 
    math.floor((gameManager.Stage + 2) / 3), 0)
gameManager.EnemyCount += 1

-- Stage-based item equipment
if gameManager.Stage > 2 then
    for i = 1, math.floor((gameManager.Stage-1) / 2) do
        _ItemSetLogic:EquipItemThroughItemID(self.SetUnit, nItemTable[i])
    end
end
```

#### Economic System Changes
- **PEN20004**: All enemies +1 attack range
- **PEN20005**: Cannot gain interest, but rewards proportional to surviving allies on victory increase by 100%
- **PEN20006**: Remove 5-coin additional reward on round defeat

#### Forced Rune Card System (PEN20007~PEN20016)
Penalties that force possession of specific rune cards in indestructible/unsellable state:

- **PEN20007**: Seffy Rune Card (RC10034)
- **PEN20008**: Young Lune Rune Card
- **PEN20009**: Thunder Rune Card
- **PEN20010**: Wandering Alchemist Rune Card
- **PEN20011**: Krishrama Rune Card
- **PEN20012**: Goldrich Junior Rune Card
- **PEN20013**: Denma Rune Card
- **PEN20014**: Ruty Rune Card
- **PEN20015**: Wiz Rune Card
- **PEN20016**: Frederick Rune Card

### Level 3: Cost Increases and Slot Restrictions (PEN3XXXX)

Advanced penalties that increase costs of various in-game actions or restrict slots.

#### Shop Cost Increases
- **PEN30001**: Character shop refresh cost +1 (`Reroll_Cost += 1`)
- **PEN30002**: Experience purchase cost +1
- **PEN30003**: Rune shop refresh cost +2 (`RuneReroll_Cost += 2`)

#### Slot Restriction System
- **PEN30004~PEN30015**: Various slot count restrictions
- **PEN30016**: Special penalty - Periodic enemy stealth during battle

### Level 4: Extreme Constraints (PEN4XXXX)

The highest difficulty extreme penalty.

#### PEN40001: Extreme Enemy Enhancement
- **Effect**: All enemies +40% damage dealt, -40% damage taken
- **Feature**: Dynamic stack system proportional to rounds and stages

```lua
local penaltyStack = gameManager.Round + (gameManager.Stage - 1) * 3
_StatusChangeLogic:GetBuff(unit, "Add_DealingDamageRate", 2 * penaltyStack, -1)
_StatusChangeLogic:GetBuff(unit, "DamageDecrease_Per", 2 * penaltyStack, -1)
```

## Penalty Implementation Technical Elements

### Common Implementation Pattern
```lua
@Component
script PEN[XXXXX] extends PenaltyComponent
    method void [Event]Handler(any event)
        __base:[Event]Handler(event)
        -- Penalty-specific logic implementation
```

### Main Implementation Methods
- `StartGameHandler()`: Change basic settings at game start
- `StartBattleHandler()`: Apply temporary effects at battle start
- `SetBattleHandler()`: Enemy spawning etc. during battle setup phase

### Core System Usage

#### Stat Change System
```lua
_StatusChangeLogic:GetBuff(unit, "Multi_PhysicalAttack", percent, duration)
_StatusChangeLogic:SetStatus(unit, caster, "SE0002", duration) -- Stealth
```

#### Property Control System
```lua
userPControl.Reroll_Cost += 1 -- Shop cost increase
userPControl.Rune_UseRuneSlotCount -= 1 -- Rune card slot decrease
```

#### Rune Card Management System
```lua
specialShopManager:GetRuneCard_Check(runeID) -- Rune card provision
rcCompo:SetIsDestructible(false) -- Set indestructible
```

#### Timer System
```lua
timer = _TimerService:SetTimerRepeat(function, interval, delay)
_TimerService:ClearTimer(timer)
```

## Strategic Impact by Penalty Category

### Economic Pressure Penalties
- Defeat reward removal, cost increases
- Increased importance of resource management
- Need for stable operation strategies

### Enemy Enhancement Penalties
- Direct combat power difference
- Need for stronger combinations and synergy
- Increased importance of items and leveling

### System Constraint Penalties
- Force gameplay pattern changes
- Need for creative solutions
- Importance of adaptability and flexibility

### Slot Restriction Penalties
- Limit choice options
- Need for efficient resource utilization
- Importance of optimized builds

## Code References
- `RootDesk/MyDesk/InGame/Penalty/List/PEN10001.mlua :: StartBattleHandler()` — Enemy attack power 15% increase
- `RootDesk/MyDesk/InGame/Penalty/List/PEN20003.mlua :: SetBattleHandler()` — Scarecrow spawn and item equipment
- `RootDesk/MyDesk/InGame/Penalty/List/PEN20007.mlua :: StartGameHandler()` — Forced rune card provision and indestructible setting
- `RootDesk/MyDesk/InGame/Penalty/List/PEN30001.mlua :: StartGameHandler()` — Shop cost increase
- `RootDesk/MyDesk/InGame/Penalty/List/PEN30016.mlua :: StartBattleHandler()` — Periodic enemy stealth system
- `RootDesk/MyDesk/InGame/Penalty/List/PEN40001.mlua :: StartBattleHandler()` — Dynamic stack-based extreme enemy enhancement

## Features and Design Philosophy

1. **Progressive Difficulty**: Systematic difficulty increase from Level 0 to 4
2. **Diversity**: Multi-angle approach including economic, combat, system constraints
3. **Strategic Depth**: Each penalty requires different response strategies
4. **Technical Excellence**: Clean event-based implementation
5. **Dynamic System**: Penalty strengthening according to game progress
6. **Balance**: Appropriate constraint levels that are not impossible to overcome

The penalty system serves as a core mechanism in MetoChess that provides continuous challenges and growth, helping players develop and adapt new strategies at higher levels.
