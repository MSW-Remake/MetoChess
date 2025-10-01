# Challenge System - Challenge List

## Overview
MetoChess's 10 challenges each provide unique strategic challenges to players through distinctive game rule changes. Each challenge inherits from `ChallengeComponent` and modifies game mechanisms at specific events.

## Challenge Implementation Patterns

### Common Structure
All challenges follow this pattern:
```lua
@Component
script CH1000X extends ChallengeComponent
    method void [Event]Handler(any event)
        __base:[Event]Handler(event)
        -- Implement challenge-specific logic
```

### Main Implementation Methods
- `StartGameHandler()`: Initial setup at game start
- `StartStageHandler()`: Processing at stage start
- `StartBattleHandler()`: Processing at battle start

## Individual Challenge Analysis

### CH10001: Patience Brings Wealth
**Objective**: Economic management challenge focused on utilizing the interest system

**Implementation Features**:
- Remove victory/defeat reward gold (`Golds_baseReward -= 10`)
- Provide 5 Baikin rune cards at start (`RC10004`)
- +2 sell value effect every round

### CH10002: Happy Christmas
**Objective**: Simplification and creative utilization of the item system

**Implementation Features**:
- All completed items changed to Santa Gloves
- Activate item transformation logic through flag setting
- Complete change in item combination strategy

### CH10003: Cornucopia
**Objective**: Remove character shop dependency and utilize fixed rune cards

**Implementation Features**:
- Cannot refresh character shop (`Shop_CanRerollCharacter = false`)
- Provide 2 Rememberer rune cards at start (`RC30001`)
- Set rune cards as indestructible (`SetIsDestructible(false)`)

### CH10005: Money Talks
**Objective**: Balance gold management with damage dealing

**Implementation Features**:
- Set starting gold to 77 coins (`AddGolds(61)`)
- Reduce damage when below 100 coins from stage 2
- Apply real-time stat debuff (`Multi_DealingDamageRate`)

```lua
if gameManager.Stage >= 2 and teamManager.Golds < 100 then
    local amount = 100 - teamManager.Golds
    _StatusChangeLogic:GetBuff(myUnit, "Multi_DealingDamageRate", -amount, -1)
end
```

### CH10008: Full House
**Objective**: Maximize same character synergy strategy

**Implementation Features**:
- Provide 5 special rune cards at start (`RC10014~RC10017`, `RC30016`)
- Rune cards related to Hina, Rain, Sera, Lina, Mongtail
- Set all rune cards as indestructible

### CH10009: Mercenary
**Objective**: No fixed strategies possible, adaptability-focused play

**Implementation Features**:
- Block Denma rune card appearance in shop
- Randomly change all units every stage
- Transform characters within same cost range
- Link with automatic synthesis check system

```lua
for _, unit in pairs(teamManager.OwnUnits) do
    local charID = charShopManager:ChooseRandomCharacterFromSameCost(cost, "Add3Level")
    unit.UnitInfo:ChangeCharInfo(charID, level, cost)
end
```

### CH10010: Monopoly
**Objective**: Extreme constraints on rune card selection

**Implementation Features**:
- Reduce rune card slots by 4 (`Rune_UseRuneSlotCount -= 4`)
- Force single rune card strategy
- Maximize importance of optimized rune card selection

## Challenge Analysis by Category

### Economic System Changes
- **CH10001**: Remove battle rewards, interest-focused
- **CH10005**: Increase starting capital, gold maintenance pressure

### Shop System Constraints
- **CH10003**: Cannot refresh character shop
- **CH10009**: Block specific rune card appearances
- **CH10010**: Extremely limit rune card slots

### Item System Changes
- **CH10002**: Unify all completed items
- **CH10004**: Block item shop, alternative acquisition methods

### Unit System Changes
- **CH10008**: Enhance specific character synergies
- **CH10009**: Periodic unit randomization

## Implementation Technical Elements

### Property Control System
Change game settings through `TM_PropertyControl`:
- Control shop functions
- Adjust gold rewards
- Change rune card slot count

### Special Shop System
Provide rune cards through `SpecialShopManager`:
- Provide challenge-specific special rune cards
- Set indestructible properties

### Stat Buff/Debuff System
Real-time stat adjustment through `_StatusChangeLogic`:
- Conditional damage reduction/increase
- Duration setting (-1 is permanent)

### Timer System
Sequential processing through delayed execution:
- Synthesis check after unit changes
- UI update timing control

## Code References
- `RootDesk/MyDesk/InGame/Challenge/List/CH10001.mlua :: StartGameHandler()` — Baikin rune card provision, gold reward removal
- `RootDesk/MyDesk/InGame/Challenge/List/CH10003.mlua :: StartGameHandler()` — Shop refresh block, rune card indestructible setting
- `RootDesk/MyDesk/InGame/Challenge/List/CH10005.mlua :: StartBattleHandler()` — Gold-based damage debuff
- `RootDesk/MyDesk/InGame/Challenge/List/CH10008.mlua :: StartGameHandler()` — Special rune card set provision
- `RootDesk/MyDesk/InGame/Challenge/List/CH10009.mlua :: StartStageHandler()` — Unit randomization logic
- `RootDesk/MyDesk/InGame/Challenge/List/CH10010.mlua :: StartGameHandler()` — Rune card slot limitation

## Features and Design Philosophy

1. **Diversity**: Each challenge provides completely different play experiences
2. **Progressive Difficulty**: From simple constraints to complex mechanisms
3. **Strategic Depth**: Requires complete review of existing strategies
4. **Technical Excellence**: Clean implementation based on events
5. **Extensibility**: Easy structure for adding new challenges

Each challenge creatively transforms MetoChess's core mechanisms, providing players with opportunities to view the game from new perspectives.
