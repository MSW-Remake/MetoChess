UIPopup:Open -- Opens popup and sets message with callback function
UIPopup:OnClickOk -- Executes callback and closes popup when OK button is clicked
UIPopup:OnClickCancel -- Executes callback and closes popup when Cancel button is clicked
UIPopup:Close -- Closes popup and disconnects event handlers
UIPopup:StartTween -- Starts tween animation for popup open/close
UIToast:ShowMessage -- Displays toast message on screen
UIToast:StartTween -- Starts fade in/out tween animation for toast message
UIToast:ShowMessageByLocalizingKey -- Shows toast message using localization key
CheatButton:HandleButtonClickEvent -- Executes corresponding cheat command when cheat button is clicked
CheatButton_DictionaryType:HandleButtonClickEvent -- Handles type-specific cheat item acquisition button clicks
CheatButton_New:HandleButtonClickEvent -- Executes new cheat button click with input values
CheatManager:OpenCheatPanel -- Opens cheat panel after permission verification
CheatManager:OpenCheatPanelOnClient -- Activates cheat UI on client side
CheatManager:OnBeginPlay -- Initializes allowed cheat users list
CheatManager:IsAllowedUser -- Checks if user has cheat usage permission
CheatManager:UseCheat -- Parses cheat key and executes corresponding cheat function
CheatManager:Cheat_PhaseOver -- Forces current phase to end
CheatManager:Cheat_GoStage -- Moves to specified stage-round
CheatManager:Cheat_ChangeLife -- Changes team health (hearts)
CheatManager:Cheat_ChangeLevel -- Changes team level
CheatManager:Cheat_GetCoin -- Acquires specified amount of coins
CheatManager:Cheat_GetCharacter -- Acquires specified 1-star character
CheatManager:Cheat_GetCharacterBySynergy -- Acquires all 1-star characters by synergy
CheatManager:Cheat_GetItem -- Acquires specified item
CheatManager:Cheat_GetRuneCard -- Acquires specified rune card
CheatManager:Cheat_OutGame_GetSyrup -- Acquires regular syrup
CheatManager:Cheat_OutGame_GetRoyalSyrup -- Acquires royal syrup
CheatManager:Cheat_OutGame_GetEXP -- Acquires experience points (includes level up processing)
CheatManager:Cheat_OutGame_ChangeLevel -- Directly changes player level
CheatManager:Cheat_OutGame_ChangeCoachOwnInfo -- Changes coach ownership information (individual/cost-based/all)
CheatManager:Cheat_OutGame_SetAchievementProgress -- Sets achievement progress
CheatManager:Cheat_OutGame_GetCollection_Character -- Sets character collection grade
CheatManager:Cheat_OutGame_GetCollection_Synergy -- Sets synergy collection grade
CheatManager:Cheat_OutGame_GetTitle -- Acquires title (name tag/keyword)
CheatManager:Cheat_OutGame_RemoveAllTitles -- Removes all titles
CheatManager:Cheat_OutGame_OpenSingleModeLevel -- Unlocks single mode level
CheatManager:Cheat_OutGame_OpenRankModeLevel -- Unlocks rank mode level
CheatManager:Cheat_OutGame_GetChallengeChance -- Sets challenge mode attempt count
CheatManager:PrintUnitStatusInfo -- Prints unit's current status information to console
CheatManager:OpenCharShopBoard -- Opens character shop board
CheatManager:RefreshCharShopBoard -- Refreshes character shop board UI
CheatManager:OpenCharShopBoard_Client -- Activates character shop board UI on client side
CheatManager:InitCheatDictUI -- Initializes cheat dictionary UI (character/item/rune card)
CheatManager:HandleKeyDownEvent -- Executes cheat functions using keyboard shortcuts
CheatManager:HandleButtonClickEvent -- Activates out-game cheat tab
CheatManager:HandleButtonClickEvent2 -- Activates in-game cheat tab
CheatManager:HandleButtonClickEvent3 -- Shows character cheat list
CheatManager:HandleButtonClickEvent4 -- Shows item cheat list
CheatManager:HandleButtonClickEvent5 -- Shows rune card cheat list
CustomChatLogic:OnBeginPlay -- Initializes chat system and sets broadcast timer
CustomChatLogic:RequestChat -- Processes chat message request and adds to queue
CustomChatLogic:OnGetMessage -- Parses chat data received from server and triggers events
CustomChatLogic:ReplaceNonSpaceWithAsterisk -- Replaces all non-space characters with asterisks for censorship
CustomChatLogic:AddSystemMessage -- Outputs system message on client side
CustomChatLogic:GetTypeByMessage -- Determines chat type by message content
CustomChatLogic:StartsWith -- Checks if string starts with specific prefix
CustomChatLogic:SendMegaphone -- Sends megaphone message to entire server
CustomChatLogic:RequestReport -- Processes chat report request and shows report popup
CustomChatLogic:ShowReportPopup -- Displays report popup UI
CustomChatLogic:ShowReportSuccessPopup -- Shows report success popup
CustomChatLogic:OnEndPlay -- Cleans up timers on game end
CustomChatLogic:HandleUserEnterEvent -- Sends cached chat messages when user enters
CustomChatLogic:HandleOnGetChatMessage -- Handles chat messages from other servers
UICustomChat:OnBeginPlay -- Initializes chat UI and connects events
UICustomChat:OnSumitMessage -- Processes chat message submission and command parsing
UICustomChat:SetWhisper -- Sets whisper target
UICustomChat:Refresh -- Updates chat list UI
UICustomChat:ActivateInputField -- Activates chat input field
UICustomChat:OnTextInputEndEdit -- Handles text input end editing
UICustomChat:OnActivateInputField -- Sets input field activation state
UICustomChat:HandleOnGetChatMessage -- Handles new chat message reception
UICustomChat:HandleKeyUpEvent -- Handles keyboard input for chat activation
UI_CustomChat_New:OnBeginPlay -- Initializes new chat UI and settings
UI_CustomChat_New:OnSumitMessage -- Processes chat message submission and command parsing
UI_CustomChat_New:ActivateInputField -- Activates/deactivates chat input field
UI_CustomChat_New:Refresh -- Updates chat message list UI
UI_CustomChat_New:ChangeCurrentWatcingLineIndex -- Changes current viewing chat line index for scrolling
UI_CustomChat_New:HandleOnGetChatMessage -- Handles new chat message reception and UI updates
UI_CustomChat_New:HandleKeyDownEvent -- Handles keyboard input for chat activation/deactivation
UI_CustomChat_New:HandleTextInputSubmitEvent -- Handles text input submission
UI_CustomChat_New:HandleMouseScrollEvent -- Scrolls chat list with mouse scroll
UI_CustomChat_New:HandleUITouchEnterEvent -- Sets flag when entering touch area
UI_CustomChat_New:HandleUITouchExitEvent -- Clears flag when exiting touch area
UI_CustomChat_New:HandleUITouchBeginDragEvent -- Starts scrollbar dragging
UI_CustomChat_New:HandleUITouchDragEvent -- Handles scrollbar dragging
UI_CustomChat_New:HandleUITouchEndDragEvent -- Ends scrollbar dragging
UI_CustomChat_New:HandleButtonClickEvent -- Handles report button click
UI_CustomChat_NicknameButton:HandleButtonClickEvent -- Shows report popup when nickname button is clicked
CharacterSynergyLogic:OnBeginPlay -- Loads character synergy data on game start
CharacterSynergyLogic:LoadTable -- Caches character synergy dataset in memory
ExpTableLogic:OnBeginPlay -- Loads experience table data on game start
ExpTableLogic:LoadTable -- Caches required experience data by level in memory
ExpTableLogic:GetNeedExp -- Returns experience amount needed for specific level
PlaySoundLogic:OnBeginPlay -- Loads sound table on game start
PlaySoundLogic:LoadTable -- Caches sound and BGM data in memory
PlaySoundLogic:PlaySound -- Plays sound effects by type with layering and priority handling
PlaySoundLogic:StopSound -- Stops sound of specified type
PlaySoundLogic:PlayBGM_Ver2 -- Plays background music for stage with fade effects
PlaySoundLogic:PlayTileSettingSound -- Plays stage-specific sound effects when placing units
PlaySoundLogic:FadeInFadeOut -- Handles background music volume fade in/out
PlaySoundLogic:SetBgmVolume -- Sets background music volume
PlaySoundLogic:HandleSliderValueChangedEvent -- Handles BGM volume slider value changes
PlaySoundLogic:HandleSliderValueChangedEvent2 -- Handles SFX volume slider value changes
GameModeDataManager:OnBeginPlay -- Initializes game mode data on game start
GameModeDataManager:Initialize -- Caches single mode and rank mode data in memory
InGameInfoDataLogic:SaveInGameData -- Function to save data
InGameInfoDataLogic:LoadInGameData -- Function to retrieve data
InGameInfoDataLogic:SaveInGameInfoData -- Function to save basic GameInfo
InGameInfoDataLogic:LoadInGameInfoData -- Function to load and apply saved GameInfo
InGameInfoDataLogic:SaveInGameTeamInfoData -- Function to save Team data
InGameInfoDataLogic:LoadInGameTeamInfoData -- Function to load Team data
InGameInfoDataLogic:SaveInGameRuneInfoData -- Function to save Rune data
InGameInfoDataLogic:LoadInGameRuneInfoData -- Function to load Rune data
InGameInfoDataLogic:SaveInGameUnitInfoData -- Function to save Unit data
InGameInfoDataLogic:LoadInGameUnitInfoData -- Function to save Unit data
InGameInfoDataLogic:SaveInGameTeamPropertyInfoData -- Function to save in-game miscellaneous property data
InGameInfoDataLogic:LoadInGameTeamPropertyInfoData -- Function to load in-game miscellaneous property data
InGameInfoDataLogic:SaveGameUnitBattleStatisticsData -- Function to save unit statistics
InGameInfoDataLogic:LoadInGameUnitBattleStatisticsData -- Function to load unit statistics
InGameInfoDataLogic:SaveGameTeamBattleStatisticsData -- Function to save team battle statistics
InGameInfoDataLogic:LoadInGameTeamBattleStatisticsData -- Function to load team battle statistics
InGameInfoDataLogic:SetSavedDataDB -- SetSavedData: Property to check if saved data exists
InGameInfoDataLogic:GetSavedDataDB -- SetSavedData: Property to check if saved data exists
InGameInfoDataLogic:LoadInGameInfoDataInLobby -- Function to load only necessary GameInfo data in lobby
InGameInfoDataLogic:SaveGameEndData -- Function to save data when game ends
InGameInfoDataLogic:LoadEndInGameData -- Prevents loading more continuation data when loading is complete
ModeDataLogic:OnBeginPlay -- Initializes mode data and loads season information on game start
ModeDataLogic:OnUpdate -- Checks branch update status every 300+ random seconds
ModeDataLogic:CountUserToSeason -- Records number of connected users for the season
ModeDataLogic:GetModeClearCountData -- Clear count
ModeDataLogic:SaveRankModeScoreData -- Function to measure and save rank mode scores
ModeDataLogic:LoadRankingData -- Loads ranking data
ModeDataLogic:GetRankModeUserClearPercent -- Calculates top percentage within season nth records
ModeDataLogic:GetSeasonData -- Function to load season data
ModeDataLogic:SetSeasonData -- Sets season data
ModeDataLogic:GetRankTierString -- Returns rank mode tier corresponding to level as string (e.g., lv1 = Iron, lv2 = Bronze1, ...)
ModeDataLogic:GetVersionInfo -- Gets current world version (string), season, and branch number based on UTC DateTime
ModeDataLogic:GetLeftTimeToNextOrdinal -- Gets remaining time until next branch
ModeDataLogic:SaveClearStageNumData -- Users outside certain rank range show current rank bracket (top n%) without individual rank measurement
ModeDataLogic:SaveModeClearCountData -- Saves data by cleared type and level
ModeDataLogic:CheckFirstRank -- Checks if this is the first rank match
ModeDataLogic:SetRankPenaltyAndRankScoreCriteriaData -- Function to save penalty and rank score measurement criteria data to DB
PlayerDataComponent:OnBeginPlay -- Initializes player data component and loads data
PlayerDataComponent:AddSyrup -- Adds specified amount by syrup type
PlayerDataComponent:AddEXP -- Function to acquire experience points. Returns changed level value if level up occurred
PlayerDataComponent:SubtractSyrup -- Subtracts syrup and returns success/failure status
PlayerDataComponent:AddBoxPurchaseCount -- Accumulates gacha box purchase count
PlayerDataComponent:SetGameRecordProperty -- Saves recent game record to profile property
PlayerDataComponent:SetFavoriteTable -- Sets favorite table by type
PlayerDataComponent:SetChallengeModeTryCount -- Sets remaining challenge mode attempts
PlayerDataComponent:OnSyncProperty -- Handles UI updates during property synchronization
PlayerDataLogic:GetPlayerData -- Function called to load necessary data when user connects to game
PlayerDataLogic:GetAchievementData -- Function to load achievement-related properties
PlayerDataLogic:SetPlayerAchievementData -- Function to save PlayerAchievementData property
PlayerDataLogic:SetPlayerAchievementCategoryData -- Function to save PlayerAchieveCategoryData property
PlayerDataLogic:GetCoachesData -- Function to load coach-related properties
PlayerDataLogic:SetPlayerOwnedCoachesData -- Function to save PlayerOwnedCoachesID property
PlayerDataLogic:SetPlayerCoachPresetsData -- Function to save SetCoachPresetInfo property
PlayerDataLogic:SetPlayerFollowingCoachIDData -- Function to save FollowingCoachID property
PlayerDataLogic:SetPlayerPickAdjustmentCountData -- Function to save PickAdjustmentCount property
PlayerDataLogic:GetCollectionData -- Function to save Collection-related properties
PlayerDataLogic:SetCharCollectionData -- Function to save CharacterCollection property
PlayerDataLogic:SetSynergyCollectionData -- Function to save SynergyCollection property
PlayerDataLogic:GetTitleData -- Function to load TitleManager properties
PlayerDataLogic:SetTitleData -- Function to save TitleManager properties
PlayerDataLogic:GetPlayerRecordData -- Loads player record data
PlayerDataLogic:GetPlayerSyrupsData -- Loads player out-game currency (syrup) status
PlayerDataLogic:SetPlayerSyrupData -- Saves player's out-game currency - Syrup
PlayerDataLogic:SetPlayerRoyalSyrupData -- Saves player's out-game currency - RoyalSyrup
PlayerDataLogic:SetPlayerRepechageData -- Saves player's out-game currency - Repechage
PlayerDataLogic:GetPlayerFavoriteDicData -- Loads dictionary favorite data
PlayerDataLogic:GetPlayerFavoriteDicDataInClient -- Saves favorites to client
PlayerDataLogic:SetPlayerFavoriteDicData -- Saves player's favorite information in dictionary
PlayerDataLogic:GetLastLoginDateData -- Loads player's most recent login date
PlayerDataLogic:SetLastLoginDateData -- Then saves current connection date
PlayerDataLogic:SetPlayerInfoData -- Saves player's basic information
PlayerDataLogic:GetPlayerNickNameData -- Loads player's nickname
PlayerDataLogic:GetPlayerCumulativeBoxPurchasesAmountData -- Loads player's gacha purchase count
PlayerDataLogic:SetPlayerCumulativeBoxPurchasesAmountData -- Saves player's gacha purchase count
PlayerDataLogic:CheckPlayerHighRankData -- Checks player's data and records if higher
PlayerDataLogic:GetPlayerLevelData -- Loads player account level status
PlayerDataLogic:SetPlayerLevelData -- Saves player account level status
PlayerDataLogic:SetPlayerProfileIsPublicData -- Saves player's profile public/private setting
PlayerDataLogic:GetPlayerProfileIsPublicData -- Loads player's profile public/private setting
PlayerDataLogic:SetPlayerTutorialData -- Saves player's tutorial-related information
PlayerDataLogic:GetPlayerTutorialData -- Loads player's tutorial-related information
PlayerDataLogic:SetPlayerChallengeInfoData -- Saves player's challenge-related information
PlayerDataLogic:GetPlayerChallengeInfoData -- Loads player's challenge-related information
PlayerDataLogic:SetPlayerDailyMissionData -- Saves player's daily mission-related information
PlayerDataLogic:GetPlayerDailyMissionData -- Loads player's daily mission-related information
PlayerDataLogic:GetPlayerGachaCountData -- Loads player gacha count
PlayerDataLogic:SetPlayerGachaCountData -- Saves player's gacha count
ArcaneRiverColleague:SetColleagueVisible -- Sets specified number of colleague entities visible and starts spawning
ArcaneRiverColleague:SpawnColleague -- Makes colleagues appear with 1-second fade-in effect
ArcaneRiverColleague:VisibleOff -- Makes colleagues disappear, plays effects, and removes entities
ChangeLifeColorComponent:OnUpdate -- Update logic to change heart UI color based on player health (currently disabled)
InfoTileComponent:HandleKeyDownEvent -- Handler to hide tile info UI on mouse click in PC platform
LineEffectCompo:OnUpdate -- Update logic for rendering line effects of various character skills
NowStageProfileComponent:OnBeginPlay -- Stores original position of current stage profile UI
NumChange:Swaping -- Starts animation cycling through number pool and changing text
NumChange:StopTimer -- Stops and resets number change timer
NumChange:StopNum -- Stops timer and sets text to final number value
OverTileComponent:SetTileEnable -- Sets tile overlay display state
RuneCardBuffComponent:ChangeUnitEffect -- Creates and plays particle effects based on rune card buff effects
RuneCardBuffComponent:Init_ver2 -- Initializes and sets buff UI by stat type
S10011TakePower:MoveToParent -- Plays power absorption effect by synergy
ScrollComponent:SpawnScroll -- 1 second at 0.5 alpha value, move 0.3 coordinates
TileSetAlpha:Starttoalpha100 -- Gradually fade alpha value to 100
TileSetAlpha:Starttoalpha0 -- Gradually fade alpha value to 0
UnitShadowComponent:Init -- Initializes unit shadow settings based on character ID and level
BackgroundChangeLogic:OnBeginPlay -- Initializes and caches background and stage icon data
BackgroundChangeLogic:GotoNextNode -- Plays transition to next stage and sets background
BackgroundChangeLogic:SetBg -- Changes background image based on stage index
BackgroundChangeLogic:BGUIOff -- Fades out background UI and shows battle field
BackgroundChangeLogic:Init -- Sets stage UI elements to initial state
BackgroundChangeLogic:SetNodeForce -- Displays previous stages as cleared based on DB data
BackgroundChangeLogic:SetWinLoseUI -- Shows round win/lose status
BackgroundChangeLogic:SetBestClearInfoUI -- Displays the furthest reached stage for this game
BackgroundChangeLogic:SetStageIconTween -- Function to enable or disable stage icon tween animation
BackgroundChangeLogic:HandleKeyDownEvent -- Keyboard input event handler (currently empty)
BackgroundChangeLogic:HandleEntityMapChangedEvent -- UI initialization handler when player map changes
CursorManager_check:OnBeginPlay -- Custom cursor initialization logic (currently disabled)
CursorManager_check:OnUpdate -- Custom cursor position update logic (currently disabled)
GeneralDirectorLogic:OnBeginPlay -- Initializes UI and data on game start
GeneralDirectorLogic:ShowReadyPhaseUI -- Shows preparation phase UIs
GeneralDirectorLogic:ShowBattleUI -- Enemy team synergy list UI appears
GeneralDirectorLogic:ResetReadyPhaseUI -- Resets for button cancellation and other reasons
GeneralDirectorLogic:ShowFreeCost -- Handles coin UI when cost is 0
GeneralDirectorLogic:LockCharacterShopSlot -- Locks or unlocks specified number of character shop slots
GeneralDirectorLogic:SpawnRuneCard -- Function to play transformation effects when acquiring rune cards
GeneralDirectorLogic:BattleBuffEffect -- Effect played when receiving stat buffs during battle
GeneralDirectorLogic:PlayBuff -- Sequential playback
GeneralDirectorLogic:UnitOnTileDirector -- Plays when unit spawns or is placed on tile by dragging
GeneralDirectorLogic:InsertItemDirectorData -- Inserts data into item effect table
GeneralDirectorLogic:StarttoPlayItemDirector -- Starts sequential playback of queued item effects
GeneralDirectorLogic:PlayItemDirector -- Item acquisition effect
GeneralDirectorLogic:PlayCoinDirector_Text -- Coin acquisition effect: Text change effect
GeneralDirectorLogic:PlayCoinDirector_Sprite -- Coin acquisition effect: Sprite effect
GeneralDirectorLogic:SetTileDirection_Main -- Battle tile display logic. All battle tiles except synergy tiles are displayed through this function
GeneralDirectorLogic:BattleDebuffEffect -- Creates particle effects when units receive debuffs during battle
GeneralDirectorLogic:Init -- Function to initialize UI positions and data on game start
GeneralDirectorLogic:RemoveHectorEffect -- Function to remove Hector character's threat effect
GeneralDirectorLogic:ShowRedTile -- Shows red tiles for units placed over level limit
GeneralDirectorLogic:ShowBattleField -- Effect to sequentially display battle tiles on game start (currently disabled)
GeneralDirectorLogic:OffInventoryUI -- Function to hide inventory UI from screen when preparation phase ends
GeneralDirectorLogic:OffShopUI -- UI turns off sequentially according to count
GeneralDirectorLogic:SetEffectAlpha -- Call this function when server needs to modify alpha value
GeneralDirectorLogic:CheckLife -- Checks remaining heart count. If 2 or less, heart UI blinks red
GeneralDirectorLogic:MinusLifeCount -- Plays heart decrease effect (resource cleanup needed)
GeneralDirectorLogic:AddLifeCount -- Plays heart increase effect (resource cleanup needed)
GeneralDirectorLogic:SetResultCoinTable -- Round result screen: Information list output for rune card/coach items
GeneralDirectorLogic:ShowResultCoins -- Sequentially displays rune card/coach rewards on round result screen
GeneralDirectorLogic:ShowSynergyTile -- Shows unit's synergy tiles
GeneralDirectorLogic:ShowSkillRangeInBattle -- Shows unit attack range
GeneralDirectorLogic:GetTileDistance -- Function to calculate distance between two tiles (based on hexagon tiles)
GeneralDirectorLogic:OnOffTileVisible -- Displays tile entity outlines
GeneralDirectorLogic:InsertRangeEntity -- Adds skill range display tile entities to list
GeneralDirectorLogic:SetClientRedTile -- Function to set unit's red tile display state
GeneralDirectorLogic:SetClientShadow -- Shadow settings
GeneralDirectorLogic:HandleEntityMapChangedEvent -- Handler to initialize UI and synergy tiles when player map changes
RuneCardDirectEnum:OnBeginPlay -- Initializes rune card stat-related data tables
RuneCardDirectEnum:GetBuffDirectorType -- Converts stat type string to buff effect type number
RuneCardDirector:OnBeginPlay -- Initializes icons and data needed for rune card effects
RuneCardDirector:ShakingCard_Battle -- Plays shaking effect when rune card activates during battle
RuneCardDirector:ShakingCard_Ready -- Plays shaking effect when rune card activates during preparation phase
RuneCardDirector:IconToastDirector_Ready -- Creates toast UI displaying effect icons and values above rune cards during preparation phase
RuneCardDirector:IconToastDirector_Battle -- Creates toast UI displaying multiple effect icons and values above rune cards during battle
RuneCardDirector:GoldenMaterial -- Function to apply golden material effect to specific rune cards
RuneCardDirector:InitDirector -- Function to initialize effect presentations applied to rune cards
RuneCardDirector:RuneCardItemDirector_Ready -- Function to play effects when acquiring items from rune cards during preparation phase
RuneCardDirector:RC10010Director -- Vicious rune card effect presentation (coin acquisition and grayscale processing)
RuneCardDirector:Setgraysprite -- Function to reset rune card stack gauge to 0
RuneCardDirector:RC30001Director -- Memory Keeper rune card effect presentation (unit image change and blinking)
RuneCardDirector:RC10022Director -- Function to set availability of bench tiles
RuneCardDirector:BattleResultDirector -- Function to handle rune card effects that activate based on battle results
RuneCardDirector:CheckRuneCardManagingValue -- Checks status of rune cards requiring special management and applies effects
RuneCardDirector:SetFillAmount -- Function to play effect that fills rune card stack gauge
RuneCardDirector:InitRuneCardManagingValue -- Function to initialize values of specially managed rune cards
RuneCardDirector:GetRuneCardIndex -- Function to find index from rune card entity
RuneCardDirector:RuneCardCoinDirector -- Plays coin sprite effects when acquiring coins from rune cards
RuneCardDirector:ChangeInvenItem -- Function to play effects when inventory items change
RuneCardDirector:DestroyRuneCard -- Plays burning or normal destruction effects when rune card is destroyed
RuneCardDirector:RC20008Director -- Karcasa rune card's synergy icon change effect
RuneCardDirector:ChangeShopCharacterValues -- Displays UI for changing shop character purchase count via Henna and Phantom rune card effects
RuneCardDirector:RC20030Director -- Plays explosion effects and sound when Bomb King rune card is destroyed
RuneCardDirector:ChangeUnifEffect -- Function to play unit transformation effects (Denma rune card effect)
RuneCardDirector:StrongerSynergyDirector -- UI effect function for displaying enhanced synergy effects
RuneCardDirector:RC20014Director -- Removes number display from other slots except selected slot via Henna rune card effect
RuneCardDirector:RC40003Director -- Function to control highlighting of rune cards via Phantom rune card effect
RuneCardDirector:RC30004Director_New -- Function to change bench tile state via Taurospear rune card effect
RuneCardDirector:RC40001Director -- Plays Elvish Blessing effect on units via Mercedes rune card effect
RuneCardDirector:RC40002Director -- Shows or hides flame UI at screen edges via Aran rune card effect
RuneCardDirector:RC40004Director_1 -- Adele rune card stage 1 effect (sequential bench tile check)
RuneCardDirector:RC40004Director_2 -- Adele rune card stage 2 effect (reward distribution)
RuneCardDirector:RC40005SpawnDirector -- Plays sound and effects when units spawn via Zero rune card effect
RuneCardDirector:StrongerSynergyDirector_Init -- Function to initialize enhanced synergy effect presentations
RuneCardDirector:RuneCardItemDirector_Battle -- Function to play effects when acquiring items from rune cards during battle
RuneCardDirector:RC20009Director -- Plays heart damage prevention effects via Tofu rune card effect
RuneCardDirector:HandleUserLeaveEvent -- Handler to reset rune card management values when user leaves
RuneCardDirector:HandleEntityMapChangedEvent -- Handler to reset rune card management values when player map changes
SampleClientSpawnLogic:SpawnUnitSample -- Function to pre-spawn entity samples for use as units
SampleClientSpawnLogic:SpawnUnitChildren -- Function to create child components needed for units
ShadowTableLogic:OnBeginPlay -- Loads shadow table data on client
ShadowTableLogic:LoadTable -- Caches shadow information table in memory for performance optimization
ShadowTableLogic:GetShadowScaleType -- Returns shadow scale type based on character ID
ShadowTableLogic:GetShadowPos -- Returns shadow position as Vector3 based on character ID and level
SynergyBattleDirectorLogic:S10017SurviveEffect -- Displays effects for units that survived
SynergyBattleDirectorLogic:S10019GetItem -- Called when acquiring items via Ludibrium synergy effect
SynergyBattleDirectorLogic:S10023Status -- Gets Adventurer synergy units
SynergyBattleDirectorLogic:S10025Tree -- Called when Knight Commander units receive buffs
SynergyBattleDirectorLogic:S10009RecoverHP -- Recovery effects
SynergyBattleDirectorLogic:S10008TargetShow -- Chaser target display
SynergyBattleDirectorLogic:S10010TargetShow -- Target display
SynergyBattleDirectorLogic:S10016ColdAir -- Elnas cold air stacking display
SynergyBattleDirectorLogic:S10016IceBomb -- Elnas cold air explosion
SynergyBattleDirectorLogic:S10018Curse -- Jormungandr curse display
SynergyBattleDirectorLogic:S10002Wave -- Guardian shield destruction
SynergyBattleDirectorLogic:S10021OrbisStoneBuff -- Orbis buff provision display
SynergyBattleDirectorLogic:S10003Bigger -- Vanguard unit temporarily grows larger and taunts units
SynergyBattleDirectorLogic:S10003Angry -- Anger display
SynergyBattleDirectorLogic:S10011ChangePos -- When two units swap positions
SynergyBattleDirectorLogic:S10011TakePower -- Plays during robbery
SynergyBattleDirectorLogic:S10032Status -- Gets Magatia units
SynergyReadyDirectorLogic:OnBeginPlay -- Loads synergy effect-related table data on client start
SynergyReadyDirectorLogic:LoadTable -- Caches all resources and data needed for synergy effects in memory for performance optimization
SynergyReadyDirectorLogic:ReceiveFieldSynergyCount -- Called when field synergy count changes and plays corresponding synergy effects
SynergyReadyDirectorLogic:BasicDirection -- Plays basic synergy effects (sound and effects)
SynergyReadyDirectorLogic:S10001Direction -- Handles Mascot synergy effects and manages popularity system
SynergyReadyDirectorLogic:S10001GetReward -- Handles effects when receiving popularity rewards from Mascot synergy
SynergyReadyDirectorLogic:S10005Direction -- Handles Temple of Time synergy effects by stages
SynergyReadyDirectorLogic:S10011Direction -- Handles Thief synergy effects and displays guide message on first activation
SynergyReadyDirectorLogic:S10015Direction -- Handles Temple of Time synergy effects with effects centered around Dodo entity
SynergyReadyDirectorLogic:S10016Direction -- Elnas synergy effect that covers battlefield with ice and plays blizzard effects
SynergyReadyDirectorLogic:S10019Direction -- Ludibrium synergy effect that summons Factory Manager Kaho and plays related effects
SynergyReadyDirectorLogic:S10020Direction -- Arcane River synergy effect that summons appropriate colleagues for each unit and applies effects
SynergyReadyDirectorLogic:S10021Direction -- Plays Orbis synergy sound and effects
SynergyReadyDirectorLogic:Set10021TilesEffect -- Manages visual effects for tiles affected by Orbis Summoning Stone
SynergyReadyDirectorLogic:S10023Direction -- Handles Adventurer synergy effects and changes doll appearance based on synergy stage
SynergyReadyDirectorLogic:S10024Direction -- Handles Job Instructor synergy effects and plays different effects based on instructor type
SynergyReadyDirectorLogic:S10025Direction -- Handles Knight Commander synergy effects and manages sanctuary tile positions and effects
SynergyReadyDirectorLogic:S10025TileBless -- Applies blessing effects to Knight Commander synergy sanctuary tiles
SynergyReadyDirectorLogic:S10025TileBuff -- Plays buff effects when units are on Knight Commander synergy sanctuary tiles
SynergyReadyDirectorLogic:GetOnFieldUnit -- Filters and returns units on field with specific synergy ID
SynergyReadyDirectorLogic:GetSynergyStep -- Calculates and returns synergy stage based on synergy count (0 if inactive)
SynergyReadyDirectorLogic:PlayEffect -- Plays synergy effects and applies to map, synergy units, or all units based on attachment type
SynergyReadyDirectorLogic:GetPos -- Calculates effect position supporting both pivot-based position and absolute position
SynergyReadyDirectorLogic:Set10001MascotInfo -- Changes mascot and audience appearance based on Mascot synergy popularity
SynergyReadyDirectorLogic:S10007ShadowSpawnEffect -- Plays spawn effects when shadow units are summoned via Shadow synergy
SynergyReadyDirectorLogic:S10021SpawnStone -- Plays spawn effects when Orbis Summoning Stone is summoned
SynergyReadyDirectorLogic:InitOrbistile -- Initializes Orbis tile effects and disables all Orbis effects on tiles
SynergyReadyDirectorLogic:S10031Direction -- Handles Fairy Tale synergy effects and plays different fairy tale book effects for each character
SynergyReadyDirectorLogic:PlayEffect_Solo -- Plays effects individually on specific units only (exclusive to Fairy Tale synergy)
SynergyReadyDirectorLogic:SetS10001StackText -- Updates Mascot synergy popularity value to UI text
Util:IsContainStringkey -- Checks if specific string key exists in dictionary
Util:Stringf -- String formatting function that replaces placeholders like {1}, {2} with values
Util:GenerateShuffle -- Randomly shuffles array keys and returns them
Util:IsContain -- Checks if table contains specific element
Util:GetDegreeByTan -- Calculates angle in degrees using vector tangent value
Util:GetDistance -- Calculates Euclidean distance between two points
Util:GetRadianByAtan -- Calculates radian value using vector tangent value
Util:DegToRad -- Converts degrees to radians
Util:RadToDeg -- Converts radians to degrees
Util:DeepCopy -- Performs deep copy of table, completely duplicating nested tables
Util:toBoolean -- Converts string to boolean value
Util:GenerateShuffleTable -- Creates table with random order of numbers in specified range
Util:LogTableItem -- Logging function to iterate through all table items (currently empty)
Util:ArrShuffle -- Randomly shuffles array elements and returns new array
Util:GetRemovedRangeTable -- Returns new table with specified range elements removed (currently disabled)
Util:MergeTable -- Merges two tables and returns new table
Util:TableToString -- Converts all table elements to string connected by separator
Util:SumTable -- Calculates sum of all numeric elements in table (currently disabled)
Util:IntToString -- Converts number to integer string
Util:TableShuffle -- Performs recursive random shuffling on all table elements
Util:RemoveDuplicatedElements -- Returns new table with duplicate elements removed (currently disabled)
Util:ConvertToOneDimentionaryTable -- Converts multidimensional table to one-dimensional table
Util:IsContainType -- Checks if table contains element of specific type
Util:SortByKey -- Sorts table by key in ascending or descending order
Util:GetRandElement -- Randomly selects and returns one element from table
Util:GetRandElementByRate -- Selects random element from table based on probability weights
Util:GetMaxValue -- Finds and returns largest value in table
Util:GetKeySameValue -- Returns first key with value equal to specific value
Util:ChageElementsType -- Converts all table elements to specified type
Util:IsElementsSame -- Compares if all elements of two tables are the same
Util:GetTableRemoveElements -- Returns new table with target elements removed from base table
Util:AddElement -- Adds specific element to table by specified count
Util:GetRandVec3 -- Generates random 3D vector within specified range
Util:GetRandVec2 -- Generates random 2D vector within specified range
Util:Clamp -- Limits value between specified minimum and maximum values
Util:GetStringMultiLine -- Converts long string to multiple lines by specified length
Util:GetTextLineCount -- Calculates number of lines in text (currently disabled)
Util:GetImageRectSizeByResourceSizeRate -- Adjusts rectangle size based on image resource ratio (currently disabled)
Util:MultiTableToString -- Converts multidimensional table to string with type information
Util:StringToMultiTable -- Converts string to multidimensional table (currently disabled)
Util:Round -- Performs rounding at specified decimal places
Util:IsSameValueVector2 -- Compares if two Vector2 values are the same
Util:GetNegativeOrPositive -- Determines number sign and returns 1, -1, or 0
Util:IsPassedTargetPos -- Checks if current position has passed target position based on direction
Util:QuickSort -- Performs quick sort using comparison function
Util:QuickSortWith -- Quick sort that sorts two arrays simultaneously (based on first array)
Util:MergeTableByKey -- Merges two tables by key with duplicate key handling options
Util:GetTableRange -- Extracts only elements in specified index range from table
Util:GetPositionWithDistance -- Calculates new position from origin with specified distance and rotation angle
Util:NumberToPercent -- Converts decimal to percentage integer
Util:PercentToNumber -- Converts percentage integer to decimal
Util:GetCreateTimeElapsedETCFromMapCode -- Extracts creation time information from map code using Base62 decoding
Util:DecimalToBase62 -- Converts decimal to Base62 string
Util:Base62ToDecimal -- Converts Base62 string to decimal
Util:OnBeginPlay -- Sets random seed and initializes Base62 table when utility logic initializes
Util:UTCTimeToHourValue -- Converts UTC elapsed time to hour units
Util:TableLen -- Calculates number of table elements
Util:ClampInteger -- Limits integer value between specified minimum and maximum values
Util:InitializeBase62Table -- Initializes character table for Base62 encoding/decoding
Util:Lerp -- Performs linear interpolation between two numbers
Util:ILerp -- Inverse function of linear interpolation that calculates t value
Util:IsDev -- Checks if developer account (identified by specific PPSN)
Util:MaxInteger -- Returns larger value between two integers
Util:MinInteger -- Returns smaller value between two integers
Util:Vector2ToString -- Converts Vector2 to string (x,y format)
Util:StringToVector2 -- Converts string to Vector2 (parsing x,y format)
Util:Utf8StringListToList -- Converts UTF-8 string to unicode code point list
Util:ListToUtf8StringList -- Converts unicode code point list to UTF-8 string
Util:ConvertIntegerToUTF8 -- Converts integer to UTF-8 valid range (avoiding surrogate pair area)
Util:ConvertUTF8ToInteger -- Reverse converts UTF-8 value to original integer
Util:IsEmptyTable -- Checks if table is empty
Util:Vector3ToString -- Converts Vector3 to string (x,y,z format)
Util:StringToVector3 -- Converts string to Vector3 (parsing x,y,z format)
Util:UTCtoLocalTime -- Converts UTC time to local time string
Util:UIPostoScreenPos -- Converts UI coordinates to screen coordinates
Util:ScreenPostoUIPos -- Converts screen coordinates to UI coordinates
AStarAlgorithm:Algorithm -- Calculates optimal path from start point to goal using A* algorithm
AStarAlgorithm:OnBeginPlay -- Runs A* algorithm test on component start
CustomCameraComponent:OnBeginPlay -- Initialization work to activate appropriate UI by map and switch camera
PersonalRoomStatus:OnBeginPlay -- Initializes personal room hex tiles and maps by coordinates
PersonalRoomStatus:GetUserID -- Sets user ID to identify personal room owner
PersonalRoomStatus:CharLocationSet -- Sets character position and updates tile placement information
TileComponent:TileSet -- Sets tile properties to define game position and type
TileComponent:TouchReleaseCheck -- Checks and handles unit or item placement availability on touch release
TileComponent:HandleTouchReleaseEvent -- Handler that receives touch release events from client and forwards to server
TileComponent_New:TileSet -- Sets tile area, type, and coordinates in new tile system
BattleStatItemHoverInfo:HandleUITouchEnterEvent -- Shows item information tooltip when mouse enters item
BattleStatItemHoverInfo:HandleUITouchExitEvent -- Hides item information tooltip when mouse exits item
DropDownBoxCloser:HandleUITouchExitEvent -- Closes dropdown when mouse exits dropdown box area
DropDownMain:Initialize -- Activates round selection slots based on current stage round information (all previous stage-rounds)
DropDownMain:Close -- Removes slots when closing window
DropDownMain:HandleUITouchDownEvent -- Opens or closes box list when dropdown button is pressed
DropDownMain:HandleTabChangedEvent -- Switches to battle statistics of corresponding round when specific round tab is selected in dropdown
DropDownSlot:HandleUITouchDownEvent -- Switches to battle statistics data of corresponding round when dropdown slot is clicked (currently unused)
StatCloseBtn:HandleButtonClickEvent -- Deactivates statistics window and all related UI when battle statistics close button is clicked
StatCoachHoverInfo:HandleUITouchEnterEvent -- Shows coach information tooltip when mouse enters coach icon
StatCoachHoverInfo:HandleUITouchExitEvent -- Hides coach information tooltip when mouse exits coach icon
StatRuneCard:HandleUITouchEnterEvent -- Shows rune card information tooltip when mouse enters rune card
StatRuneCard:HandleUITouchExitEvent -- Hides rune card information tooltip when mouse exits rune card
UI_BattleStatistics:StatValueFormatter -- Converts received values to appropriate format string for the stat. For handling decimal notation of critical rate etc.
UI_BattleStatistics:Initialize -- Function to put UnitBattleStatistics data into this logic's table and create unit slots and graphs when window opens
UI_BattleStatistics:ClearGameProperties -- Initializes battle statistics-related properties on game end
UI_BattleStatistics:ChangeTab_1stCategory -- Changes primary category tab and sets secondary category menu for the tab (cumulative/maximum)
UI_BattleStatistics:ChangeTab_2ndCategory -- Changes secondary category tab and refreshes graphs and rankings with corresponding statistics data
UI_BattleStatistics:RefreshUI_GraphList -- Sorts UnitCombatStats in descending order according to selected tab
UI_BattleStatistics:DrawGraphs -- Changes size of created graphs to match values
UI_BattleStatistics:BattleStatRuneCardSetter -- Displays rune cards owned by user in corresponding round
UI_BattleStatistics:RefreshUI_RoundInfo -- Reflects information updated when round changes to UI
UI_BattleStatistics:GetData -- Loads UnitBattleStatistics data matching stage round conditions into this logic's table
UI_BattleStatistics:SetManagerName -- Sets player and opponent manager names
UI_BattleStatistics:RoundSynergySetter -- Organizes synergy information owned by user in corresponding round based on unit and rune information
UI_BattleStatistics:HandleButtonClickEvent -- When 'Cumulative' tab button is pressed
UI_BattleStatistics:HandleButtonClickEvent2 -- When 'Maximum' tab button is pressed
UI_BattleStatistics:HandleButtonClickEvent4 -- When opening battle statistics from final result screen, turns off 'final result screen'
UI_BattleStatistics:HandleButtonClickEvent5 -- When battle statistics close button is clicked, redisplays result screen if opened from game result screen
UI_BattleStatistics_GraphTooltipActivator:HandleUITouchEnterEvent -- Shows detailed statistics information of corresponding character as tooltip when mouse enters graph area
UI_BattleStatistics_GraphTooltipActivator:HandleUITouchExitEvent -- Hides tooltip when mouse exits graph area
UI_BattleStatistics_UnitTooltipActivator:HandleUITouchEnterEvent -- Shows unit information tooltip when mouse enters unit portrait
UI_BattleStatistics_UnitTooltipActivator:HandleUITouchExitEvent -- Hides unit information tooltip when mouse exits unit portrait
UI_Tooltip_BattleStatisticsGraph:OnUpdate -- Updates position of tooltip following mouse position and adjusts to not exceed screen boundaries
ChallengeManager:InitNewGameChallengeSet -- Loads challenge component before in-game start
ChallengeManager:SetChallenge -- Sets corresponding challenge ID or initializes based on challenge number
ChallengeManager:OnSyncProperty -- Handles server-synchronized property changes on client
CoachIngameComponent:CoachSleepTimer -- Shows SleepRUID if no interaction with coach for 100 seconds. Only visible effect during preparation phase
CoachIngameComponent:Interaction -- Handles interaction with coach and plays random animations
CoachIngameComponent:CheckRUID -- Compares with current RUID and resets sleep timer
CoachIngameComponent:PlayRollAction -- Plays special action where coach rotates and jumps
CoachIngameComponent:BattleResultCoachReaction -- Sets coach reaction based on battle result
CoachIngameComponent:TalkAnim -- Function to turn coach dialogue animation on or off
CoachIngameComponent:PlayCoachAbilityEffect -- Plays effects and animations when coach ability activates
CoachIngameComponent:HandleTouchEvent -- Handles coach touch event to execute interaction
CoachManager:SetCoachID -- Function used in settings screen to set coach according to input type
CoachManager:SetCoachRUID -- Changes coach RUID according to type
CoachManager:SetCoachPreset -- Changes coach preset according to preset number
CoachManager:InitNewGameCoachSet -- Loads equipped coach components before in-game start
CoachManager:ModifyPlayerOwnedCoachesID -- Function to modify coach ownership information
CoachManager:OnSyncProperty -- Function to reflect server-synchronized coach data to client UI
CoachManager:GetOwnedCoachList -- Returns list of owned coach IDs corresponding to cost
CoachManager:setCoachEntityOwner -- Function to set companion coach entity on server and synchronize to client
CoachManager:setCoachEntityOwner_Client -- Function to set companion coach entity on client
CoachManager:GetHasType -- Function to return ownership status of specified coach (0:not owned, 1:owned, 2:master coach)
CoachManager:GetAllOwnedCoachCount -- Function to return total count of coaches owned by player
CoachManager:setCoachMasterEffect -- Function to control master coach effect settings (currently disabled)
CoachManager:SetBattleResultRUID -- Function to set coach reaction animation based on battle result
CoachManager:OnMapEnter -- Function to initialize companion coach status when entering map
ESCMenuService:ResetSetting -- Resets configured settings
ESCMenuService:OpenESCMenu -- Function to play effects when opening ESC menu
ShortCutKeyService:ActivateChangingKeyMode -- Function to execute or exit shortcut key change mode
ShortCutKeyService:ChangeKey -- Checks for duplicate keys
ShortCutKeyService:DeleteKey -- Function to unbind specified shortcut key
ShortCutKeyService:HandleKeyDownEvent -- Event handler for Arena map
ShortCutKeyService:HandleKeyDownEvent2 -- Event handler for Lobby map
ItemCombineService:LoadData -- Pre-stores ItemCombine table data
ItemCombineService:GetNormalItemIDByMaterialItemIDs -- Finds and returns resulting (completed) item ID from combining items with itemId1 and itemId2
ItemCombineService:GetMateiralIDinUnitEquippedItems -- Finds and returns if there are material items among unit's equipped items
ItemCombineService:GetMaterialItemIDsByNormalItemID -- Returns material item list needed to create item with normalItemID
ItemCombineService:ShowCombineTableTooltip -- Function to show combination table tooltip when right-clicking in shop or storage
ItemStatusLogic:GetItemStatusCalculatingType -- @type table<string, string>
CharacterShopManager_New:Initiate -- Reset piece count / Initial list update / Property initialization
CharacterShopManager_New:ChooseRandomCharacterFromSameCost -- Selects random character with purchase cost of targetCost
CharacterShopManager_New:ChooseRandomCharacterFromSameCostNSynergy -- Selects character with purchase cost of targetCost that shares synergy with target character
CharacterShopManager_New:CreateCharacterPoolFromSameSynergy -- Creates character pool that shares synergy with target character
CharacterShopManager_New:ChooseRandomCharacterFromTable -- Selects random character with purchase cost of targetCost from character pool
CharacterShopManager_New:Reroll -- Function to refresh shop
CharacterShopManager_New:Reroll_Setting -- Function to set predetermined characters and costs in shop
CharacterShopManager_New:Reroll_Special -- Function to refresh shop so only same synergy appears due to invitation letter (cheating dice) effect
CharacterShopManager_New:BuyCharacter -- Attempts purchase processing (checks purchase availability based on conditions like bench etc.)
CharacterShopManager_New:Lock -- Function caller verification
CharacterShopManager_New:UI_RefreshShopList -- Refreshes product list in shop UI
CharacterShopManager_New:UI_RefreshChanceList -- Changes 'appearance probability by cost' display in shop
CharacterShopManager_New:UI_RefreshUIByOwnGoldsCondition -- Makes refresh and EXP purchase buttons black and white based on gold ownership condition
CharacterShopManager_New:UI_RefreshLockButtonUI -- Modifies buttons and tooltips according to lock status
CharacterShopManager_New:Reroll_Select -- Function to make specified character ID appear in shop
GameManager:GoToNextPhase -- Function to proceed to next phase
GameManager:Ready -- Executes functions that should be performed when preparation phase starts
GameManager:InitUI_BattleTeamInfo -- Initially sets up 'team information' UI among battle UIs
GameManager:Clean_OnClient -- Turns off overtime UI
GameManager:SetGameOver -- If there's still a chance to use resurrection ticket
GameManager:SetUI_BattleOver -- Triggers popup to check rewards acquired after each battle ends
GameManager:ClearGameInfo -- Function to delete all game progress information when exiting to lobby
GameManager:MoveToLobby_OnClient -- Activates loading screen when moving to lobby
GameManager:RestartArena -- Function to restart from 1-1
GameManager:UseRepechage -- Function called when resurrection ticket is used
GameManager:GiveUpRepechage -- Function called when giving up resurrection ticket use
LoadResourcesInfo:ResourceLoad -- Pre-downloads for fast resource loading speed
LoadResourcesInfo:GetUILocalPositionScale -- Use when you want to appropriately adjust resources in UI
LoadResourcesInfo:GetColliderOffsetScale -- Use when specifying collision range offset and scale for TriggerComponent, physicsColliderComponent
MatchManager:OnBeginPlay -- Uses 8x8 matrix
MatchManager:SetCurrentRoundMatchInfo -- Generates matching information during player battle rounds (N-1 ~ N-3)
MatchManager:SetCurrentRoundMatchInfo2 -- Generates matching information during player battle rounds (N-1 ~ N-3)
MatchManager:SetNextMatchInfoUI_OnServer -- Function to filter next possible matching candidates and send that information to client
MatchManager:GetRandomCloneOpponentUserID -- When user (with userID) needs to face clone, designates and returns random clone target ID
SpecialShopManager:PurchaseItem_Check -- Function called when purchase button is pressed in item shop
SpecialShopManager:GetRuneCard_Check -- Executes when rune card is acquired through acquisition effect
SpecialShopManager:RemoveRuneCard -- Called when rune card is destroyed
SpecialShopManager:RemoveRuneCard_Check -- Called when rune card is destroyed
SpecialShopManager:PurchaseRunecard_Check -- Function called when purchase button is pressed in rune card shop
SpecialShopManager:ResellRuneCard_Check -- Called when dragging card from rune card inventory to sellZone
SpecialShopManager:CheckReroll_Runes -- Function caller verification
SpecialShopManager:RerollList_RunesSpecial -- Function to make specified rune cards appear in rune card shop for tutorial progress
SynergyManager_New:InitAllStacks -- Sets all synergy-related stack values to 0
SynergyManager_New:OnGameStart -- Called once when starting game for first time (not called when loading)
SynergyManager_New:OnMergeUnit -- Called when unit is merged
SynergyManager_New:OnActivatedSynergyCountChanged -- Called whenever number of activated synergies on battlefield changes
SynergyManager_New:OnReadyPhase -- Executes when preparation phase starts
SynergyManager_New:OnFieldUnitCountChanged -- Called when number of units placed on battlefield changes
SynergyManager_New:OnBattleStart -- Called when battle starts
SynergyManager_New:OnSkillUsedByAllies -- When ally uses skill
SynergyManager_New:RefreshUnitStatus_AllOwnUnits -- Refreshes stats of all allies
SynergyManager_New:S10001_GetStack -- Mascot characters gain popularity when participating in player battles
SynergyManager_New:S10001_GiveReward_Check -- When reward button is pressed, receives rewards based on accumulated popularity
SynergyManager_New:S10001_GiveReward -- When reward button is pressed, receives rewards based on accumulated popularity
SynergyManager_New:S10004_UseSkill -- Whenever mages use skills, allied mages gain additional mana
SynergyManager_New:S10004_Default -- Mage: Allied mana increases
SynergyManager_New:S10008_Stat -- Chaser: Movement speed increases by 100%
SynergyManager_New:S10009_Default -- Brawler: All allies gain health
SynergyManager_New:S10011_WithdrawItem -- When unit equipped with 'Troublemaker's Mask' is placed on bench, retrieves that item
SynergyManager_New:S10012_GetInvincible -- Noble Soul (Mihile unique synergy)
SynergyManager_New:S10014_Kill -- Empress (Cygnus unique synergy): Whenever ally defeats enemy unit, removes all status ailments from all allies and increases attack speed by 4%
SynergyManager_New:S10015_ApplySumOfStarLevel -- Sets Dodo's stats in SettingPhase (based on sum of team members' star levels)
SynergyManager_New:S10015_SpawnUnitBattlePhase -- Function to set Dodo's stats and summon in BattlePhase
SynergyManager_New:S10018_Curse -- Sleepywood: Curses all enemies to deal fixed damage proportional to max health every 3 seconds
SynergyManager_New:S10018_RecoverHP -- Sleepywood: Sleepywood characters recover health whenever enemies are defeated
SynergyManager_New:S10019_OnBattleStart -- Ludibrium: At battle start, Ludibrium characters gain max health and mana proportional to number of items equipped by allies
SynergyManager_New:S10021_OnKilled -- Troublemaker (7) When enemy is defeated, (ally unit equipped with Troublemaker's Mask) becomes invisible for 2 seconds
SynergyManager_New:S10022_GainMP -- Cygnus (11): When ally unit is defeated, all surviving ally units recover 30 MP
SynergyManager_New:S10023_GetCoin -- Adventurer: 9 synergy, 50% chance to gain 1 coin when defeating enemy
SynergyManager_New:S10023_StatSet -- Adventurer: Stats increase proportional to team level
SynergyManager_New:S10024_BattleStart -- Among Job Instructors: Heinz (starting MP increase) or Helena (unstoppable for x seconds after battle start)
SynergyManager_New:S10025_SetSaintArea -- Knight Commander: Randomly designate sanctuary position - specified in "y00x" format (e.g., 3005 for row 3 column 5)
SynergyManager_New:S10025_SetSainAreaTarget -- Designates targets to receive Knight Commander buff
SynergyManager_New:S10026_Spawn -- [Yeti and Pepe] (2): At battle start, 'Yeti' and 'Pepe' units combine forces. Summons Yeti and Pepe
SynergyManager_New:S10027_Dead -- Balrog: Whenever ally is defeated, Balrog units gain additional max health and become larger
SynergyManager_New:S10032_Default -- Allied unit abilities increase according to sum of Magatia units by star level
SynergyManager_New:S10034_Default -- Executioner: Gains additional critical chance and critical damage
SynergyManager_New:S10037_Dead -- Rage: If two or more allies die, Goblin becomes enraged. Enters unstoppable state until battle ends, increasing movement speed and attack speed
SynergyManager_New:S10031_SetItemOrder -- Kerning City
SynergyManager_New:S10031_GetItem -- Kerning City
SynergyManager_New:S10038_Blessing -- Fox God's Blessing
SynergyManager_New:S10032_GetItem -- Magatia "Alcadno" After battle start and every 8 seconds, equips appropriate completed item to random living ally unit
SynergyManager_New:S10031_BattleStart -- Kerning City rune card effect
SynergyManager_New:S10036_BattleStart -- Fantastic Theme Park: Parade is open! Receives various effects at regular intervals. Parade effects become 10% stronger per level of allied Fantastic Theme Park units
TeamBattleStatistics:RoundPropertyInitialize -- Records initial values in each property at battle start
TeamBattleStatistics:RoundPropertyInitializeToClient -- Records initial values in each property at battle start
TeamBattleStatistics:SetProperty -- Records in property
TeamBattleStatistics:SetPropertyToClient -- Records in property
TeamBattleStatistics:SetPropertyWithKey -- Records in property
TeamBattleStatistics:SetPropertyToClientWithKey -- Records in property
TeamBattleStatistics:SetCoachesProperty -- Records coach list at game start
TeamBattleStatistics:SetCoachesPropertyToClient -- Records coach list at game start
TeamManager:UnitInfo_ToString -- UnitID / Star grade / Equipped item 3 types IDs (0 if none) / Permanent increase buff / Placement information
TeamManager:InitNewGame -- Preparation function for game start
TeamManager:LoadContinuedGame -- Loads ongoing game if exists
TeamManager:SaveCurrentGame -- Saves current state to prevent forced termination, crashes, etc.
TeamManager:AddEXP -- Increases experience points
TeamManager:OnSyncProperty -- Updates team health UI
TeamManager:SetBattleResult -- Reduces health based on battle win/loss and remaining unit count
TeamManager:SetItemBoxList -- Function to determine choices when opening item box
TeamManager:SetEmblemBoxList -- Function to determine choices when opening emblem box
TeamManager:GetItemFromItemBox -- When selecting slot selectIdx from item box, processes to obtain that slot's item
TeamManager:GetOnFieldSynergyCount -- Increases/decreases activated synergy count by count amount
TeamManager:GetEnemyOwnedFieldSynergyCount -- Increases/decreases activated synergy count by count amount
TeamManager:SwapRuneCardIndex -- Function to execute rune card placement order change requests
TeamManager:CheckActiveSynergy -- Function to return count of currently activated synergies
TeamManager:CheckSpecificSynergy -- Function to return whether specific synergy is activated
PenaltyManager:InitNewGamePenaltySet -- Loads penalty component before in-game start
RC10003:InGameDataLoadHandler -- At battle start, attack speed of all allies increases by 5% for each owned rune card
RC10009:SellThisRuneCard -- Acquires Golden Karma Scissors
RC10010:SetDirectorValue -- Function to set effect values when loading values from DB
RC10011:SellThisRuneCard -- Experience points needed for level up decreases by 3
RC10011:InGameDataLoadHandler -- Experience points needed for level up decreases by 3
RC10018:PlayEffect -- Unit summon sound
RC10020:SetDirectorValue -- Function to set effect values when loading values from DB
RC10021:SellThisRuneCard -- When selling character, separates completed items that character had equipped into combination items
RC10022:SellThisRuneCard -- Number of units deployable on battlefield +1
RC10023:SellThisRuneCard -- When winning battle, additionally acquires 4 coins
RC10024:PlayEffect -- Activation effect
RC10024:SetDirectorValue -- Function to set effect values when loading values from DB
RC10026:SetDirectorValue -- Function to set effect values when loading values from DB
RC10028:SetDirectorValue -- Function to set effect values when loading values from DB
RC10034:PlayEffect -- Rune card activation effect
RC10036:SetDirectorValue -- Function to set effect values when loading values from DB
RC10041:SellThisRuneCard -- Summons scarecrow equipped with 2 random emblem items
RC10041:InGameDataLoadHandler -- SetUnit configuration needed
RC10042:SellThisRuneCard -- Temple of Time synergy is considered to have 1 additional
RC10042:InGameDataLoadHandler -- Temple of Time synergy is considered to have 1 additional
RC10043:SellThisRuneCard -- Elnas synergy is considered to have 1 additional
RC10043:InGameDataLoadHandler -- Elnas synergy is considered to have 1 additional
RC10044:SellThisRuneCard -- Victoria Island synergy is considered to have 1 additional
RC10044:InGameDataLoadHandler -- Victoria Island synergy is considered to have 1 additional
RC10045:SellThisRuneCard -- Ludibrium synergy is considered to have 1 additional
RC10045:InGameDataLoadHandler -- Ludibrium synergy is considered to have 1 additional
RC10046:SellThisRuneCard -- Arcane River synergy is considered to have 1 additional
RC10046:InGameDataLoadHandler -- Arcane River synergy is considered to have 1 additional
RC10047:SellThisRuneCard -- Orbis synergy is considered to have 1 additional
RC10047:InGameDataLoadHandler -- Orbis synergy is considered to have 1 additional
RC10048:SellThisRuneCard -- Cygnus synergy is considered to have 1 additional
RC10048:InGameDataLoadHandler -- Cygnus synergy is considered to have 1 additional
RC10049:SellThisRuneCard -- Adventurer synergy is considered to have 1 additional
RC10049:InGameDataLoadHandler -- Adventurer synergy is considered to have 1 additional
RC10050:SellThisRuneCard -- Knight Commander synergy is considered to have 1 additional
RC10050:InGameDataLoadHandler -- Knight Commander synergy is considered to have 1 additional
RC10051:SellThisRuneCard -- Mascot synergy is considered to have 1 additional
RC10051:InGameDataLoadHandler -- Mascot synergy is considered to have 1 additional
RC10052:SellThisRuneCard -- Guardian synergy is considered to have 1 additional
RC10052:InGameDataLoadHandler -- Guardian synergy is considered to have 1 additional
RC10053:SellThisRuneCard -- Vanguard synergy is considered to have 1 additional
RC10053:InGameDataLoadHandler -- Vanguard synergy is considered to have 1 additional
RC10054:SellThisRuneCard -- Mage synergy is considered to have 1 additional
RC10054:InGameDataLoadHandler -- Mage synergy is considered to have 1 additional
RC10055:SellThisRuneCard -- Strategist synergy is considered to have 1 additional
RC10055:InGameDataLoadHandler -- Strategist synergy is considered to have 1 additional
RC10056:SellThisRuneCard -- Hunter synergy is considered to have 1 additional
RC10056:InGameDataLoadHandler -- Hunter synergy is considered to have 1 additional
RC10057:SellThisRuneCard -- Chaser synergy is considered to have 1 additional
RC10057:InGameDataLoadHandler -- Chaser synergy is considered to have 1 additional
RC10058:SellThisRuneCard -- Brawler synergy is considered to have 1 additional
RC10058:InGameDataLoadHandler -- Brawler synergy is considered to have 1 additional
RC10059:SellThisRuneCard -- Sniper synergy is considered to have 1 additional
RC10059:InGameDataLoadHandler -- Sniper synergy is considered to have 1 additional
RC10060:SellThisRuneCard -- Troublemaker synergy is considered to have 1 additional
RC10060:InGameDataLoadHandler -- Troublemaker synergy is considered to have 1 additional
RC10061:SellThisRuneCard -- Kerning City synergy is considered to have 1 additional
RC10061:InGameDataLoadHandler -- Kerning City synergy is considered to have 1 additional
RC10062:SellThisRuneCard -- Magatia synergy is considered to have 1 additional
RC10062:InGameDataLoadHandler -- Kerning City synergy is considered to have 1 additional
RC10063:SellThisRuneCard -- Magatia synergy is considered to have 1 additional
RC10063:InGameDataLoadHandler -- Kerning City synergy is considered to have 1 additional
RC10064:SellThisRuneCard -- Executioner synergy is considered to have 1 additional
RC10064:InGameDataLoadHandler -- Executioner synergy is considered to have 1 additional
RC10065:SellThisRuneCard -- Duelist synergy is considered to have 1 additional
RC10065:InGameDataLoadHandler -- Duelist synergy is considered to have 1 additional
RC10066:SellThisRuneCard -- Fantastic Theme Park synergy is considered to have 1 additional
RC10066:InGameDataLoadHandler -- Fantastic Theme Park synergy is considered to have 1 additional
RC20001:SellThisRuneCard -- Interest-acquirable coin limit increases by 5 (maximum 10 coins)
RC20007:SetDirectorValue -- Function to set effect values when loading values from DB
RC20008:InGameDataLoadHandler -- 'Specific synergy' changes each time new round starts
RC20009:PlayEffect -- Heart defense effect
RC20011:SetDirectorValue -- Function to set effect values when loading values from DB
RC20012:SetDirectorValue -- Function to set effect values when loading values from DB
RC20013:PlayEffect -- Activation effect
RC20013:SetDirectorValue -- Function to set effect values when loading values from DB
RC20014:PlayEffect -- Activation effect
RC20014:SetDirectorValue -- Function to set effect values when loading values from DB
RC20015:PlayEffect -- Activation effect
RC20021:SetDirectorValue -- Function to set effect values when loading values from DB
RC20022:SellThisRuneCard -- Item purchase cost decreases by 50%
RC20023:PlayEffect -- Sound
RC20024:SellThisRuneCard -- Number of deployable units +1
RC20030:PlayEffect -- No rune card activation effect
RC20031:SetDirectorValue -- Function to set effect values when loading values from DB
RC20032:PlayEffect -- No activation effect
RC20033:SellThisRuneCard -- __ always provides optimal items to units
RC20033:PlayEffect -- Activation effect
RC20034:SellThisRuneCard -- Shop character selling slots decrease by 2. Instead, refresh cost decreases by 1 coin (refresh cost cannot go below 1 coin)
RC20037:PlayEffect -- Activation effect
RC20038:SellThisRuneCard -- Cost needed to purchase experience points decreases by 1 coin
RC20040:PlayEffect -- Activation effect
RC20043:SellThisRuneCard -- Acquires two scarecrows
RC20043:InGameDataLoadHandler -- Scarecrow check
RC20044:SellThisRuneCard -- Shop probability one tier higher than current team level is applied
RC20045:SellThisRuneCard -- Temple of Time synergy enhancement
RC20046:SellThisRuneCard -- Elnas synergy enhancement
RC20047:SellThisRuneCard -- Victoria Island synergy effect
RC20048:SellThisRuneCard -- Sleepywood synergy effect
RC20049:SellThisRuneCard -- Ludibrium synergy effect
RC20050:SellThisRuneCard -- Arcane River synergy effect
RC20051:SellThisRuneCard -- Orbis synergy effect
RC20052:SellThisRuneCard -- Cygnus synergy effect
RC20053:SellThisRuneCard -- Adventurer synergy effect
RC20054:SellThisRuneCard -- Job Instructor synergy effect
RC20055:SellThisRuneCard -- Knight Commander synergy effect
RC20056:SellThisRuneCard -- Mascot synergy effect
RC20057:SellThisRuneCard -- Guardian synergy effect
RC20058:SellThisRuneCard -- Vanguard synergy effect
RC20059:SellThisRuneCard -- Mage synergy effect
RC20060:SellThisRuneCard -- Strategist synergy effect
RC20061:SellThisRuneCard -- Hunter synergy effect
RC20062:SellThisRuneCard -- Shadow synergy effect
RC20062:InGameDataLoadHandler -- Shadow synergy effect
RC20063:SellThisRuneCard -- Chaser synergy effect
RC20064:SellThisRuneCard -- Brawler synergy effect
RC20065:SellThisRuneCard -- Sniper synergy effect
RC20066:SellThisRuneCard -- Troublemaker synergy effect
RC20067:SellThisRuneCard -- Kerning City synergy effect
RC20067:SetDirectorValue -- Function to set effect values when loading values from DB
RC20068:SellThisRuneCard -- Magatia synergy effect
RC20069:SellThisRuneCard -- MiuMiu synergy effect
RC20070:SellThisRuneCard -- Executioner synergy effect
RC20071:SellThisRuneCard -- Executioner synergy effect
RC20072:SellThisRuneCard -- Fantastic Theme Park synergy effect
RC30002:SetDirectorValue -- Function to set effect values when loading values from DB
RC30002:PlayEffect -- Activation effect
RC30003:SellThisRuneCard -- When purchasing experience points, gains additional 2 experience points
RC30004:PlayEffect_Copy -- Activation effect
RC30004:SellThisRuneCard -- When sold, turns off effect
RC30006:SellThisRuneCard -- Can no longer earn interest
RC30010:GetReward -- Rewards are given based on probability
RC30010:SetDirectorValue -- Function to set effect values when loading values from DB
RC30011:SellThisRuneCard -- Summons Mu Gong equipped with 3 random emblem items
RC30011:InGameDataLoadHandler -- Mu Gong check
RC30017:SetDirectorValue -- Function to set effect values when loading values from DB
RC30019:SetDirectorValue -- Function to set effect values when loading values from DB
RC40002:RuneBuffOn -- When achieving 333 combo, damage taken by all allies decreases by 30%
RC40002:SetDirectorValue -- Function to set effect values when loading values from DB
RC40003:SellThisRuneCard -- Before deletion, deletes copied component
RC40003:CopiedComponent -- When copying rune card, brings existing rune card component to check if property check is needed
RC40003:InGameDataLoadHandler -- Copies right rune card
RC40005:SellThisRuneCard -- Summons Mir
RC40005:InGameDataLoadHandler -- Mir check
BTLogic_New:GetPath -- Function to find optimal path from start point to destination using A* algorithm
BTLogic_New:getDistance -- Function to calculate distance and horizontal/vertical spacing between two nodes
BTLogic_New:getEntities -- AttackAble
BTLogic_New:getTarget -- Returns target determined by type among enemies based on mainTile position
BTLogic_New:getTargets -- Surrounding units within Num range: Around_MinNum_MaxNum
BTLogic_New:getVector -- Line
BTLogic_New:getTile -- Empty tile with most enemies gathered within range: EmptyTileWithMostEnemies_All_Num
BTLogic_New:getTiles -- StraightLine_Num: All line tiles that pass through (target passes) and range (Num)
BTLogic_New:getTileFromTile -- Empty tile with most enemies gathered within range: EmptyTileWithMostEnemies_All_Num
BTLogic_New:CheckAttackAble -- Function to check if skill use or attack is possible
BTLogic_New:getNextMoveTile -- Function to calculate and return path of next movement tile using A* algorithm
CustomizedBattleEffectService:README -- Guide function providing service description
CustomizedBattleEffectService:PlayDamageSkin -- Displays damage font matching damage type on target entity
CustomizedBattleEffectService:PlayEffect -- Function to play effect at specified position
CustomizedBattleEffectService:PlayEffectAttached -- Function to play effect attached to entity
CustomizedBattleEffectService:SetMaterialOnClient -- Function to change entity's material
CustomizedBattleEffectService:SetEntityEnable -- Function to set entity's activation state
CustomizedBattleEffectService:SetEntityVisible -- Function to set entity's visibility
CustomizedBattleEffectService:LineRendererEffect -- Function to create line effect between start point and target
DynamicMapSystemLogic:CreateDynamicMap -- Function to create dynamic map for specified user
DynamicMapSystemLogic:DestoryDynamicMap -- Function to delete dynamic map of specified user
DynamicMapSystemLogic:OnBeginPlay -- Function to set timer and initialize debug log when logic starts
DynamicMapSystemLogic:OnEndPlay -- Function to clean up set timers when logic ends
DynamicMapSystemLogic:PendingUserId -- Function to add user ID that failed dynamic map deletion to pending list
DynamicMapSystemLogic:TryDestroyPendingMap -- Function to attempt deletion of dynamic maps in pending list
IngameEnteranceLogic:InsertQueue -- Function to add user ID to in-game entrance queue
IngameEnteranceLogic:OnUpdate -- Function called every frame to periodically check user loading completion status
IngameEnteranceLogic:CheckUserLoadComplete -- Function to check loading completion status of first user in queue
ItemSetLogic:SetDragStartEntity -- Function called when item drag starts to set UI state and provide visual feedback
ItemSetLogic:OnUpdate -- Function to update position so dragging item follows mouse cursor
ItemSetLogic:SetDragEnd -- Function to restore UI state when item drag ends
ItemSetLogic:OnDragEnd -- self:SetDragEnd()
ItemSetLogic:EquipItem_Check -- Equips teamManager.OwnItems[itemSlotIdx] item to targetUnit
ItemSetLogic:EquipItem -- Equips user.TeamManager.OwnItems[itemIdx] to targetUnit
ItemSetLogic:EquipItemThroughItemID -- Equips user.TeamManager.OwnItems[itemIdx] to targetUnit
ItemSetLogic:OpenItemBox_Check -- If senderUser's teamManager.OwnItems[itemSlotIdx] is an item box
ItemSetLogic:WithdrawAllItems -- Function to retrieve all items when unit is sold or magnet remover is used
ItemSetLogic:WithdrawItem -- Retrieves item equipped at equippedIdx slot
ItemSetLogic:WithdrawCopiedItem -- Logic to delete temporary items when called at battle end
ItemSetLogic:UseConsumableItem -- Consumable item usage logic
ItemSetLogic:ChangeAllItems -- Function to transform and retrieve items when transformation hammer is used on unit
ItemSetLogic:GetItemBox -- Function to give specified index item box to user
ItemSetLogic:GetConsumableItem -- Function to give specified index consumable item to user
ItemSetLogic:GetMaterialItem -- Function to give specified index material item to user
ItemSetLogic:GetNormalItem -- Function to give specified index normal item to user
ItemSetLogic:GetEmblemItem -- Function to give specified index emblem item to user
ItemSetLogic:EmblemSynergyUpdate -- Function to reflect to synergy when emblem item is unequipped
ItemSetLogic:GetItemList -- Function to return item list matching specified type and season
RuneCardSetLogic:SetDraggingEntity -- Called when starting to drag card from rune card inventory
RuneCardSetLogic:OnUpdate -- Function to update position so dragging rune card follows mouse cursor
RuneCardSetLogic:SetDragEnd -- Turns off sell UI
RuneCardSetLogic:OnDraggingEnd -- Called when rune card drag ends
RuneCardSetLogic:SwapUIPositionOnDrag -- Function executed when mouse is placed over another card while dragging rune card
RuneCardSetLogic:SetCurrentMouseHoveringSlot -- Function to set index of slot that mouse is hovering over
RuneCardSetLogic:GetRuneCardList -- getRuneCheck: Whether to exclude currently owned rune cards
S01_SkillDescLogic:OnBeginPlay -- Function to initialize all skill description data when logic starts
StatusChangeLogic:CheckDamage -- Function to calculate damage and separate into normal damage and fixed damage for return
StatusChangeLogic:SetVariableStatus -- Function to change health or mana values
StatusChangeLogic:SetStack -- Function to set unit's stack attribute and limit maximum value
StatusChangeLogic:HitDamage -- Function for attacker to deal damage to target and calculate final damage applying defense and resistance
StatusChangeLogic:KillUnitForce -- Function to forcibly kill by synergy effects etc.
StatusChangeLogic:SetShield -- Function for targetUnit to acquire shield
StatusChangeLogic:ShieldCheck -- Function to comprehensively calculate owned shield values
StatusChangeLogic:GetBuff -- Gives statusType buff to unit
StatusChangeLogic:BuffCheck -- Function to check all buff states of unit and decrease duration
StatusChangeLogic:SetStatus -- Function to give unit status effect with statusEffectID key for setTime seconds
StatusChangeLogic:RemoveStatusEffect -- If unit has statusEffectID status effect, removes it
StatusChangeLogic:RemoveOneoffStats -- Function to remove stats (buffs, shields) applied only during single battle
StatusChangeLogic:PlayStatusEffectAnimation -- Function to play or stop visual animation of status effect
UnitInfoUILogic:SetBar -- Function to update unit's HP, MP, shield bars to UI
UnitInfoUILogic:SetBarcode -- Function to display scale guide above unit's HP and MP bars
UnitInfoUILogic:SetItemList -- Function to update 'equipped item list' of unit health bar
UnitInfoUILogic:RefreshSynergy -- Function to update synergy information to UI and manage pages
UnitInfoUILogic:SetLevelMaterial -- Function to display material information according to unit's level and grade in UI
UnitSetLogic_New:SettingTile -- Function to initialize and set components for all tiles on map
UnitSetLogic_New:DragUnit -- Unit Info
UnitSetLogic_New:Drag -- Function to handle screen touch events during unit dragging
UnitSetLogic_New:TouchRelease -- Function to move selectUnit to selectTile
UnitSetLogic_New:TouchReleaseByForce -- Function to move selectUnit to selectTile
UnitSetLogic_New:SpawnUnit -- Function to acquire new units (purchase, event round rewards, etc.)
UnitSetLogic_New:SpawnOnetimeUnit -- Summons one-time unit that only participates in that battle
UnitSetLogic_New:CheckUnitMerging -- Checks merge availability and performs if possible
UnitSetLogic_New:MergeUnits -- Merges units in unitTable owned by userId
UnitSetLogic_New:SellUnit -- Function to sell unit
UnitSetLogic_New:BattleSetting_UnitSet -- Function to create, remove, or manage enemy units at battle start/end
UnitSetLogic_New:BattleSetting_OnSettingPhase -- Function performed during 'Setting' phase among Preparation > Setting > Battle phases
UnitSetLogic_New:BattleSetting_OnBattlePhase -- Function performed when 'Battle' phase starts among Preparation > Setting > Battle phases
UnitSetLogic_New:UnitSampleSpawn -- Function to pre-spawn entity samples for use as units
UnitSetLogic_New:ProjectileSampleSpawn -- Function to pre-summon entities for use as projectiles
UnitSetLogic_New:UnitSampleDestroy -- Function to delete unit sample entities when user leaves
UnitSetLogic_New:ProjectileSampleDestroy -- Function to delete projectile sample entities when user leaves
UnitSetLogic_New:PlayMergeDirection -- Function to play merge effects
UnitSetLogic_New:SpawnShadow -- Function to summon/dismiss shadow character's shadow partner
UnitSetLogic_New:SpawnDoDo -- Function to summon/dismiss Dodo
UnitSetLogic_New:SpawnOrbisStone -- Function to summon/dismiss Orbis Summoning Stone
UnitSetLogic_New:GetEmptyPooledUnit -- Finds entity to use among pooled entities
UnitSetLogic_New:BattleSetting_EnemyUnit -- Function to summon enemy units
UnitSetLogic_New:BattleSetting_EnemySynergyCheck -- Code to check enemy synergy and perform additional work based on activated synergy
UnitSetLogic_New:SpawnEnemyUnit -- Function to summon enemy units
UnitSetLogic_New:GetProjectileEntity -- Function to summon enemy units
Attack_Sample:Attack -- Performs physical attack on target unit and handles animation and damage
Attack_Sample:SetDamage -- Applies actual damage to target unit and plays hit effects
Attack_Sample:HitEffect -- Displays attack hit effect on target unit
C00004_Mugong_Attack:SetShadow -- Shadow moves
C10001_Slime_Attack:SetShadow -- Shadow gradually gets smaller
C10002_OrangeMushRoom_Attack:SetShadow -- Shadow gradually gets smaller
C10015_Hodori_Attack:SetShadow -- Shadow gradually gets smaller
C10016_Homun_Attack:SetShadow -- Shadow gradually gets smaller
C20001_Hawkeye_Attack:SetShadow -- Shadow briefly disappears
C20002_Pepe_Attack:SetShadow -- Shadow moves
C20007_Eckhart_Attack:SetShadow -- Shadow moves
C20008_Lioner_Attack:SkillLineEffect -- Attacks nearby enemies when multiple enemies take damage
C30010_DarkLord_Attack:SetShadow -- Shadow moves
C30011_Mushmom_Attack:SetShadow -- Shadow gradually gets smaller
C30012_Faust_Attack:PlaySkillEffect -- Range display
C40002_Grendel_Attack:PlaySkillEffect -- Range display
C40008_Shadower_Attack:SetShadow -- Shadow moves
C50001_PinkBean_Attack:AttackEffect -- Displays basic attack particles. Recycles entities as much as possible without deletion since particles appear frequently
C00001_YetiAndPepe_Skill:PlaySkillEffect_Range -- Range display
C00001_YetiAndPepe_Skill:PlaySkillEffect_Particle -- Power display between Yeti's hands: Particles
C00001_YetiAndPepe_Skill:RemoveEffect -- Particle deletion
C00002_Dodo_Skill:SpawnAggressiveIcon -- Taunt mark
C00002_Dodo_Skill:SetShadow -- Shadow gradually gets smaller
C00005_Mir_Skill:SetShadow -- Shadow gradually gets smaller
C10002_OrangeMushRoom_Skill:PlaySkillEffect -- Range display
C10002_OrangeMushRoom_Skill:SetShadow -- Shadow gradually gets smaller
C10008_MemoryMonk_Skill:PlaySkillEffect -- Range display
C10010_Newbie_Skill:SetShadow -- Shadow moves
C10016_Homun_Skill:Reflection -- Exception handling
C10018_Powderbutterfly_Skill:PlaySkillEffect -- Range display
C10019_Goopi_Skill:SetTargetEffect -- Target display
C20002_Pepe_Skill:PlaySkillEffect -- Range display
C20004_DanceswithBalrog_Skill:Reflection -- Exception handling
C20005_QualmMonkTrainee_Skill:PlayRangeSkillEffect -- Range display
C20007_Eckhart_Skill:SetShadow -- Shadow moves
C20008_Lioner_Skill:PlaySkillEffect -- Displays particles on Lioner's horn
C20008_Lioner_Skill:RemoveEffect -- Particle deletion
C20010_IceDrake_Skill:PlaySkillEffect -- Range display
C20011_Archer_Skill:SkillLineEffect -- Connects self and enemy with line
C20013_Monkeyrog_Skill:SetShadow -- Shadow gradually gets smaller
C20014_Blin_Skill:SetShadow -- Shadow disappears
C20014_Blin_Skill:PlayEffect -- Range display
C20015_ThreeTailedFox_Skill:SkillLineEffect -- Attacks nearby enemies when multiple enemies take damage
C20016_DeetAndRoi_Skill:PlayRangeSkillEffect -- Range display
C20017_Homunspeculler_Skill:SkillLineEffect -- Attacks nearby enemies when multiple enemies take damage
C30001_Yeti_Skill:PlaySkillEffect -- Range display
C30004_Taurospear_Skill:SkillLineEffect -- Connects self and enemy with line
C30006_BlazeWizard_Skill:SkillLineEffect -- Connects self and enemy with line
C30007_Priest_Skill:PlaySkillEffect -- Range display
C30009_NightWalker_Skill:PlaySkillEffect -- Range display
C30011_Mushmom_Skill:PlaySkillEffect -- Range display
C30011_Mushmom_Skill:SetShadow -- Shadow gradually gets smaller
C30013_Kyrin_Skill:SkillLineEffect -- Connects self and enemy with line
C30016_WindGuardian_Skill:PlayRangeSkillEffect -- Range display
C30018_SnowWitch_Skill:SkillLineEffect -- Connects self and enemy with line
C30020_Jellybus_Skill:PlaySkillEffect -- Range display
C40004_Timer_Skill:SkillLineEffect -- Connects self and enemy with line
C40005_NeinHeart_Skill:PlaySkillEffect -- Range display
C40006_JuniorBarlog_Skill:PlaySkillEffect -- Range display
C40007_WindArcher_Skill:SetTargetEffect -- Target display
C40014_NineTailedFox_Skill:SkillLineEffect -- Attacks nearby enemies when multiple enemies take damage
C40015_Rurumo_Skill:PlayEffect -- Range display
C40016_SkyGuardian_Skill:SkillLineEffect -- Connects self and enemy with line
C50001_PinkBean_Skill:PlaySkillEffect -- Range display
C50005_Lucid_Skill:SetBattle -- self.skillCount = 0
C50006_CrimsonBalrog_Skill:PlaySkillEffect -- If empty table, first checks if there are particle entities in child entities
C50008_Papulatus_Skill:PlaySkillEffect -- Range display
C50010_Frankenroid_Skill:PlaySkillEffect -- Range display
C50010_Frankenroid_Skill:SetShadow -- Shadow gradually gets smaller
C50013_Scarlion_Skill:GetTreasure -- Treasure hunt (unique)
SkillComponent:Skill -- Uses basic active skill on target unit and plays animation and sound
Skill_Sample:Skill -- Uses skill on target unit and consumes MP to deal damage
Skill_Sample:SetSkillDamage -- Applies skill damage to target unit and plays hit effects
Skill_Sample:HitEffect -- Displays skill hit effect on target unit
AProjectileInfo:SetProjectile -- Sets projectile and moves toward target, applying damage on collision
AProjectileInfo:Destroy -- Destroys projectile and returns to initial state
AProjectileInfo:SetPosition -- Sets projectile's position and rotation
AProjectileInfo:SetFlipX -- Sets projectile sprite X-axis flip
AProjectileInfo:SetOwnerID -- Sets projectile owner ID on server and client
AProjectileInfo:SetOwnerIDInClient -- Sets projectile owner ID on client
SkillProjectile2Info:SetProjectile -- Sets skill projectile and moves toward second target to apply skill damage
SkillProjectile2Info:Destroy -- Destroys skill projectile and removes component
SkillProjectile2Info:SetPosition -- Sets skill projectile's position and rotation
SkillProjectile2Info:SetFlipX -- Sets skill projectile sprite X-axis flip
SkillProjectileInfo:SetProjectile -- Sets skill projectile and moves toward target to apply skill damage
SkillProjectileInfo:Destroy -- Destroys skill projectile and removes component
SkillProjectileInfo:SetPosition -- Sets skill projectile's position and rotation
SkillProjectileInfo:SetFlipX -- Sets skill projectile sprite X-axis flip
SkillShotCheckComponent:SetOwnerID -- Sets skill projectile owner ID on server and client
SkillShotCheckComponent:SetOwnerIDInClient -- Sets skill projectile owner ID on client
MotionComponent:MotionChangeToIdle -- Changes unit motion to Idle state and plays animation
MotionComponent:Check -- Checks unit state and changes motion if necessary
MotionComponent:HandleSpriteAnimPlayerEndFrameEvent -- Handles sprite animation frame end event
UnitAIWanderComponent:OnBeginPlay -- Initializes AI behavior tree nodes and sets root node
UnitAIWanderComponent:BattleEnd -- Initializes all BT-related properties when battle ends
UnitAIWanderComponent:Move -- Function to move unit from current tile to next tile
UnitAIWanderComponent:YetiAndPePe -- Yeti and Pepe special movement (parabolic trajectory flight movement)
UnitAnimationComponent:OnBeginPlay -- Loads character information table on client
UnitAnimationComponent:SetAnimRUID -- Sets animation RUID according to character ID
UnitAnimationComponent:PlayAnimation -- Plays specified animation and sets direction
UnitAnimationComponent:PlayHitDirection -- Changes sprite to red when hit then restores to original color
UnitAnimationComponent:SetDefaultColor -- Sets sprite's default color
UnitAnimationComponent:SetStatusEffectLayerOrder -- Sets layer order of status effect effects
UnitAnimationComponent:SetLayerOrder -- Sets sprite's layer order
UnitAnimationComponent:SetFlip -- Sets sprite X, Y axis flip
UnitBattleStatistics:RoundPropertyInitialize -- Initializes each property value per round
UnitBattleStatistics:SetProperty -- Sets battle statistics property value and accumulates
UnitBattleStatistics:SetPropertyToClient -- Sets battle statistics property value on client
UnitBattleStatistics:RoundPropertyInitializeToClient -- Initializes each property value per round
UnitBattleStatistics:PropertyClear -- Initializes all battle statistics properties
UnitBattleStatistics:PropertyClearToClient -- Initializes all battle statistics properties on client
UnitBattleStatistics:SetPropertyWithKey -- Sets battle statistics property value with specific key
UnitBattleStatistics:SetPropertyInClientWithKey -- Sets battle statistics property value with specific key on client
UnitInfo:OnBeginPlay -- Sets sprite renderer and motion component when unit initializes
UnitInfo:SetCharInfo -- Sets character information and initializes related components
UnitInfo:ChangeCharInfo -- Changes existing character information to new character
UnitInfo:CleanCharInfo -- Initializes character information and resets all states
UnitInfo:SetTransformScale -- Sets unit's size, collider, and UI position
UnitInfo:SetResourceInfo -- Sets resource information to update RectSize and CenterPivot
UnitInfo:SetOutlineMaterial -- Sets unit's outline material or applies color based on level
UnitInfo:SetPosition -- Sets unit's world coordinates
UnitInfo:CleanPosition -- Moves unit off-screen for hiding
UnitInfo:SetPropertyToServer -- Sets property on server and synchronizes to client
UnitInfo:SyncPropertyToClient -- Applies property values received from server on client
UnitInfo:IsOnFieldUnit -- Checks if unit is on battlefield or bench
UnitInfo:DoesHaveSynergy -- Checks if unit has specific synergy
UnitInfo:GetOwnSynergies -- Returns all synergies owned by unit (basic + emblem items)
UnitInfo:SetCenterPivot -- Sets center point based on sprite RUID
UnitInfo:SetUnitStatusUIEnable -- Sets display status of unit status UI (health bar etc.)
UnitInfo:SetDefaultInfo -- Sets unit's default information (commented out code)
UnitInfo:HandleTouchEvent -- Handles unit click event (drag start)
UnitInfo:HandleTouchReleaseEvent -- Handles unit touch release event (drag end)
UnitItem:OnBeginPlay -- Initializes item component and stacks
UnitItem:RefreshItemStatus -- Function to update stat effects gained from items when equipping items
UnitItem:OnSettingPhase -- Executes when 'Setting' phase starts among Preparation > Setting > Battle
UnitItem:OnBattleStart -- Effect at battle start
UnitItem:OnEquippedChangedDuringBattlePhase -- Function to activate battle start effect of corresponding item when item is equipped to idx slot during battle
UnitItem:OnAttacked -- Effect triggered when hit
UnitItem:OnAttacked_Damage -- Effect triggered when attacker has specific items
UnitItem:OnUseSkill -- Effect when using skill
UnitItem:OnKillUnit -- Effect when using skill
UnitItem:OnDefaultAttack -- Effect on attack
UnitItem:OnDefaultAttackHit -- Effect when basic attack hits
UnitItem:OnSkillHit -- Effect when skill hits
UnitItem:OnVamp -- Effect triggered during lifesteal
UnitItem:ClearAllStacks -- Function to reset all item usage effects and accumulated stack values
UnitItem:UseItemAbility_NI10001 -- Flame Katana: Attack power +15% every 5 seconds after battle start (stackable)
UnitItem:UseItemAbility_NI10002 -- NI10002 Steel Mishell: Becomes immune to status effects like stun for 15 seconds after battle start
UnitItem:UseItemAbility_ShieldByHP -- Once per battle, gains shield equal to 20% of max health when remaining health reaches 30%
UnitItem:UseItemAbility_NI10004 -- NI10004 Goblin Club: When health reaches 60%, becomes invisible and invincible for 2 seconds
UnitItem:UseItemAbility_NI10006 -- NI10006 Sword Earring: Inflicts burn and healing reduction status for 6 seconds on targets damaged by basic attacks and skills
UnitItem:UseItemAbility_NI10007 -- (NI10007) 20% chance on physical attack hit to inflict mana overload status on target
UnitItem:UseItemAbility_NI10008 -- NI10008 Red Whip: Third basic attack hit deals 70% additional physical damage to enemies within 1 tile
UnitItem:UseItemAbility_NI10009 -- NI10009 Swift Wings: Attack speed increases by 3% on basic attack. This effect stacks
UnitItem:UseItemAbility_NI10010 -- NI10010 Pot Lid: Third basic attack hit deals 30 physical damage to target and inflicts physical defense reduction for 4 seconds
UnitItem:UseItemAbility_NI10011 -- NI10011 White Nesher: Basic attack hit deals 30 magic damage to target and inflicts magic defense reduction for 4 seconds
UnitItem:UseItemAbility_NI10012 -- NI10012 Dragon Shine Bow: Next basic attack after skill use deals additional magic damage equal to 200% of mana
UnitItem:UseItemAbility_NI10015 -- NI10015 Blue Boxing Gloves: When attacking or taking damage, damage taken -0.4%, damage dealt +0.8% (maximum 25 stacks)
UnitItem:UseItemAbility_NI10017 -- NI10017 Ester Shield: Battle start: Provides +20 physical defense, +20 magic defense to allies within 1 tile except self
UnitItem:UseItemAbility_NI10019 -- NI10019 Timeless Earring: Creates wave every 2 seconds dealing 75 physical damage to random enemy within 2 tiles and applying physical defense reduction for 6 seconds
UnitItem:UseItemAbility_NI10020 -- NI10020, NI10025: Gains shield equal to 100% of max mana for 4 seconds when using skill
UnitItem:UseItemAbility_NI10021 -- NI10021 Blue Robe: Recovers 5% of max health every 2 seconds
UnitItem:UseItemAbility_NI10023 -- Heals ally with lowest health ratio by 20% of damage dealt
UnitItem:UseItemAbility_NI10024 -- NI10024 Sapphire Earring: Creates magic explosion every 2 seconds dealing 75 magic damage to random enemy within 2 tiles and applying magic defense reduction for 6 seconds
UnitItem:UseItemAbility_NI10027 -- Mana +15% every 5 seconds after battle start (stackable)
UnitItem:UseItemAbility_NI10028 -- NI10028 Red Skull Earring: Inflicts burn and healing reduction status for 6 seconds on targets damaged by basic attacks and skills
UnitItem:UseItemAbility_NI10030 -- NI10030 Starlight Bracelet: Becomes immune to status effects like stun for 15 seconds after battle start
UnitItem:UseItemAbility_NI10032 -- NI10032 Gold Drop Earring: Critical chance increases by 30% of MP MAX when using skill (stackable)
UnitItem:UseItemAbility_NI10033 -- NI10033 Santa Gloves:
UnitItem:UseItemAbility_NI10034 -- NI10034: When using skill, provides 10 MP to nearest ally and self
UnitItem:UseItemAbility_NI10035 -- When using skill, grants shield equal to 200% of consumed mana for 4 seconds to ally with lowest health ratio excluding self
UnitItem:UseItemAbility_SI10002 -- Gem of Wrath
UnitItem:UseItemAbility_SI10003 -- Gem of Envy
UnitItem:UseItemAbility_SI10004 -- Gem of Gluttony
UnitItem:UseItemAbility_SI10005 -- Gem of Regret
UnitItem:UseItemAbility_SI10006 -- Gem of Sloth
UnitItem:UseItemAbility_SI10007 -- Gem of Greed
UnitItem:UseItemAbility_SI10008 -- Gem of Jealousy
UnitItem:IsEquipingItem -- Checks if this unit is equipped with item corresponding to itemID, returns true if equipped
UnitStatus:SetUnitStatus -- Function to calculate unit's various stats
UnitStatus:Dead -- Function called when unit dies
UnitStatus:SetUniInfoPopup -- Function to update unit information popup viewed by right-click
UnitStatus:SetProperty -- This component's Properties should only sync to specific user's client and maintain sync state
UnitStatus:ApplyStatusEffect_SE0017 -- Function called when first activating or deactivating burn status effect
UnitStatus:SetUnitStatusByStat -- Function to calculate unit's various stats
UnitSynergy:ClearAllStackProperties -- Reverts stack values acquired/consumed during battle
UnitSynergy:OnActivatedSynergyCountChanged -- Called whenever number of activated synergies on battlefield changes
UnitSynergy:OnBattleStart -- Called when battle starts
UnitSynergy:OnShieldBreak -- Called when shield is destroyed
UnitSynergy:OnHit -- Called when taking damage
UnitSynergy:OnDefaultAttackHit -- Called when my basic attack hits
UnitSynergy:OnSkillHit -- Called when my skill hits
UnitSynergy:OnChangeHP -- Called when dealing damage to enemy HP
UnitSynergy:OnDead -- Function executed when this unit dies
UnitSynergy:S10002_MakeStun -- Guardians: Stuns enemies who destroy Guardian shields
UnitSynergy:S10002_TrueDamage -- Guardians 10 synergy: During basic attack, deals fixed damage equal to 5% of possessed shields
UnitSynergy:S10003_Taunt -- Vanguard: At battle start and when HP drops to 50% or below, taunts all enemies within 2 tiles
UnitSynergy:S10003_DamageDecrease -- Vanguard: Reduces incoming damage
UnitSynergy:S10006_Vamp -- Hunter: Gains lifesteal when HP is 70% or below
UnitSynergy:S10006_GetPhysicalAttack -- Hunter 11 synergy: Gains additional 50% attack power when HP is 70% or below
UnitSynergy:S10009_Recover -- Fighter: When HP is 30% or below, gains recovery and unstoppable for 6 seconds
UnitSynergy:S10010_Sniping -- Sniper: Periodically additionally attacks the character with lowest HP
UnitSynergy:S10010_HPDown -- Sniper(7): When HP is 30% or below, gains stealth for 3 seconds
UnitSynergy:S10013_OnUseSkill -- Legendary Archer (Helena unique synergy): Moves to the farthest tile from enemies each time skill is used
UnitSynergy:S10019_OnDead -- When Ludibrium character is defeated, copies their equipped items and equips them to a random ally without items
UnitSynergy:S10033_Stat -- Meow Meow:
UnitSynergy:S10033_maxMPDown -- Meow Meow:
UnitSynergy:S10034_Execution -- 6+ synergy: Enemies with HP reduced below a certain percentage by damage are executed
UnitSynergy:S10035_Stat -- Duelist gains attack speed with each attack up to maximum 12 times (30 times with rune card use)
UnitSynergy:S10035_RuneAddStat -- Rune effect allows Duelist to start battle with 5 additional attack speed stacks
AttackCheck:OnBehave -- BT node that checks if attack is possible and executes attack
MoveCheck:OnBehave -- BT node that finds path to target and executes movement
MoveCheck:GetTile -- Function to get actual tile entity from tile node coordinates
SkillCheck:OnBehave -- BT node that checks if skill usage is possible and executes skill
TargetCheck:OnBehave -- BT node that searches for and sets attack target
UI_LevelReward:Update_RewardEntity -- Updates UI elements of level reward entity
UI_LevelReward:OnBeginPlay -- Initializes level reward description text
UI_LevelReward:HandleUITouchEnterEvent -- Adjusts tooltip position when mouse hovers
UI_LevelUP_Popup:SetPopup -- Probably will be replaced with image font, but for now with text... [level display starts here]
UI_LevelUP_Popup:OpenPopup -- Opens level up popup and plays sound
UI_LevelUP_Popup:TooltipOpen -- Function assigned to TouchReceive
UI_PlayerLevel:OnBeginPlayCustomButtonFunc_toDotIndicator -- Connects events to dot indicator buttons
UI_PlayerLevel:CreatePopup_LevelRewardList -- Creates level reward list popup and sets pages
UI_PlayerLevel:RefreshLobbyProfile -- Updates player level and experience info in lobby
UI_PlayerLevel:InitializeLobbyProfile -- Sets lobby profile to initial values
UI_PlayerLevel:GetRewardIconInfo -- Returns icon information based on reward ID
UI_PlayerLevel:HandleButtonClickEvent -- Level reward list popup open button click event
UI_PlayerLevel:HandleButtonClickEvent2 -- Previous page button click event
UI_PlayerLevel:HandleButtonClickEvent3 -- Next page button click event
AchievementManager:HandleInGameStart -- Initializes data for some achievements used like stack when game starts
AchievementService:UpdateAchievement -- log("@h",achievementID,value)
AchievementService:SaveAchieveDB -- Achievement: Login count increase / Time when force-quit might exceed 9 o'clock
UI_AchievementList:OnBeginPlay -- Create achievement category Cell UI
UI_AchievementList:HandleButtonClickEvent -- Achievement UI close button click
UI_AchievementService:OnBeginPlay -- Turn off tooltip UI
UI_AchievementService:EnableRewardPopup -- Disable collect all button----
UI_AchievementService:EnableAllRewardButton -- ---
UI_AchievementStep:HandleButtonClickEvent2 -- Achievement step UI close button click
CoachMoveComponent:CoachSleepTimer -- Shows SleepRUID if no interaction with coach for 100 seconds
CoachService:OnBeginPlay -- Master coach animation effect ruid
UI_GachaDirection:OnBeginPlay -- Sets gacha presentation UI initial state
UI_GachaDirection:SetGoodsID -- Function to set gacha product ID
UI_GachaDirection:HandleButtonClickEvent -- Gacha presentation door click event handler
UI_GachaDirection:HandleButtonClickEvent3 -- Gacha presentation skip button click event handler
UI_GachaResult:OnClick_ResultCloseBtn -- Close gacha result screen UI
UI_GachaResult:SetGachaResult_10Times -- 10-pull draw. Receives data and outputs sequentially
CoachShopDataLogic:OnBeginPlay -- Initialization function that loads shop-related datasets when game starts
CoachShopDataLogic:Get_Gacha -- Function to query gacha product information by gacha product ID
CoachShopDataLogic:Get_CoachPrice -- Function to query price information by coach cost
CoachShopDataLogic:Get_CoachPriceById -- Function that returns price information as array by product type and ID
CoachShopDataLogic:DataSync -- Function to synchronize shop data from server to client
CoachShopDataLogic:HandleUserEnterEvent -- Handler that synchronizes shop data and initializes UI when user enters
CoachShopManager:OnBeginPlay -- Connect world coin purchase result function
UI_CoachShopList:OnBeginPlay -- Cost filter list UI, connect button events
UI_CoachShopList:Sort -- func: Function to sort table containing coach list IDs by cost in ascending/descending order
UI_CoachShopList:OnClick_OwnCoachVisible -- func: Function to request showing owned coaches together when coach shop filter button is clicked
UI_CoachShopList:OnClick_OwnMasterCoachVisible -- func: Function to request showing only purchasable master coaches when master coach shop filter button is clicked
UI_CoachShopList:HandleButtonClickEvent -- Shop close button click
UI_CoachShopList:HandleButtonClickEvent2 -- Coach recruitment shop category button click
UI_CoachShopList:HandleButtonClickEvent3 -- Coach shop category button click
UI_CoachShopList:HandleButtonClickEvent4 -- Master coach shop category button click
UI_CoachShopList:HandleButtonClickEvent5 -- Coach shop filter button click
UI_CoachShopList:HandleButtonClickEvent8 -- Master shop filter button click
UI_CoachShopList:HandleButtonClickEvent6 -- Cost filter button click
UI_CoachShopList:HandleButtonClickEvent7 -- Sort button click
UI_CoachShopPopUp:UIClose_Popup -- Close shop popup UI
UI_CoachShopPopUp:Popup_CompletePurchaseInitailize -- Purchase complete popup
UI_CoachShopPopUp:HandleButtonClickEvent -- Close shop popup UI
UI_CoachShopPopUp:HandleButtonClickEvent3 -- Close shop popup UI
UI_CoachShopPopUp:HandleButtonClickEvent2 -- World coin purchase button click
UI_CoachShopPopUp:HandleButtonClickEvent4 -- Royal syrup purchase button click
UI_CoachShopPopUp:HandleButtonClickEvent5 -- Product info tooltip button click
UI_CoachShopService:CheckHaveRoyalSyrup -- Determine if syrup is owned
UI_GachaShopService:RefreshGachaShopUI -- Opens gacha shop
UI_GachaShopService:OnOffShopUI -- Open gacha shop
UI_GachaShopService:RefreshPriceUI -- Display price, change price font color based on current user's currency amount
UI_GachaShopService:SetProbabilityData -- Display probability info: Receive table from server and send data to UI
UI_GachaShopService:SendToUIChanceTable -- Function to display probability data received from server on UI
UI_GachaShopService:HandleButtonClickEvent2 -- Gacha shop open button click event handler
UI_GachaShopService:HandleButtonClickEvent -- Gacha shop close button click event handler
UI_GachaShopService:HandleButtonClickEvent3 -- 1-pull gacha purchase button click event handler
UI_GachaShopService:HandleButtonClickEvent4 -- 10-pull consecutive gacha purchase button click event handler
UI_GachaShopService:HandleButtonClickEvent5 -- Gacha probability table open button click event handler
UI_GachaShopService:HandleButtonClickEvent6 -- Gacha probability table close button click event handler
UI_GachaShopService:HandleButtonClickEvent7 -- 1-pull gacha world coin purchase button click event handler (not implemented)
UI_GachaShopService:HandleButtonClickEvent8 -- 10-pull consecutive gacha world coin purchase button click event handler (not implemented)
UI_Goods:ShowTooltip -- Function to show or hide coach info tooltip when mouse hovers
UI_Goods:HandleButtonClickEvent -- Handler that checks purchase conditions and starts purchase process when product is clicked
UI_Goods:HandleButtonStateChangeEvent -- Handler that controls tooltip display when button state changes
DailyMissionComponent:OnLoadData -- Executed when daily mission related data is loaded from DB
DailyMissionComponent:InitDailyMission -- Function executed daily at UTC 0:00
DailyMissionComponent:RefreshMission_Check -- Called when client requests refresh
DailyMissionComponent:RefreshMission -- Changes mission in missionIndex slot. When changed, progress is also reset
DailyMissionComponent:AddDailyMissionProgress -- Called in specific situations to change daily mission progress
DailyMissionComponent:ReceiveReward -- Verification
DailyMissionComponent:ReceiveBonusReward -- Function to provide step-by-step rewards based on bonus points
DailyMissionComponent:OnSyncProperty -- Function to update UI based on data synchronized from server
DailyMissionComponent:SetRedDot -- Checks red dot conditions and activates them
DailyMissionLogic:OnBeginPlay -- Initialization function that loads daily mission dataset when game starts
DailyMissionLogic:LoadDataSet -- Function to load daily mission info from dataset and store in internal table
DailyMissionLogic:UI_RefreshMissionList -- Function to refresh daily mission list UI
DailyMissionLogic:UI_RefreshPointArea -- Function to refresh bonus point area UI
DailyMissionLogic:ShowUI_RefreshCheckPopup -- Function to display mission refresh confirmation popup
DailyMissionLogic:HandleButtonClickEvent3 -- Bonus reward receive button click event handler
DailyMissionLogic:HandleButtonClickEvent4 -- Mission refresh confirm button click event handler
DailyMissionLogic:HandleButtonClickEvent5 -- 'Don't ask again' checkbox toggle button click event handler
UI_DailyMisison_RefreshButton:HandleButtonClickEvent -- Daily mission refresh button click event handler
UI_DailyMission_Reward:HandleUITouchEnterEvent -- Tooltip display event handler when mouse enters reward icon
UI_DailyMission_Reward:HandleUITouchExitEvent -- Tooltip hide event handler when mouse exits reward icon
UI_DailyMission_RewardReceiveButton:HandleButtonClickEvent -- Daily mission reward receive button click event handler
UI_DailyMission_Slot:Initialization -- Function to initialize UI entities
UI_DailyMission_Slot:RefreshUI -- Function to refresh daily mission slot UI
DictionaryFavoriteListManager:Initialize -- Initialize all favorite UI
DictionaryFavoriteListManager:Update_FavoriteUI -- Updates favorite panel
DictionaryFavoriteListManager:Update_EnableSynergy -- Called when character favorites are updated
DictionaryFavoriteListManager:RefreshUI_SynergyList -- Reflect on UI
DictionaryFavoriteListManager:GetSynergyList -- Returns calculated synergy list
DictionaryFavoriteListManager:IsSettedFave_Char -- Check if this character is registered in favorites
DictionaryFavoriteListManager:IsSettedFave_Item -- Check if this item is registered in favorites
DictionaryFavoriteListManager:IsSettedFave_Rune -- Check if this rune card is registered in favorites
DictionaryFavoriteListManager:Initialize_CharList -- Initialize character favorite list and reset UI
DictionaryFavoriteListManager:Initialize_ItemList -- Initialize item favorite list and reset UI
DictionaryFavoriteListManager:Initialize_RuneList -- Initialize rune card favorite list and reset UI
DictionaryFavoriteListManager:Initialize_SynergyList -- Initialize synergy list (not implemented)
DictionaryFavoriteListManager:HandleButtonClickEvent -- Handle favorite initialization button click
DictionaryFavoriteListManager:HandleDictionaryFavoriteEvent -- Handle favorite toggle event and refresh list
DictionaryFavoriteListManager:HandleButtonClickEvent2 -- When button is pressed, automatically register current player's units and rune cards to favorites
DictionaryFavoriteListManager:HandleButtonClickEvent3 -- Handle synergy list page navigation button click
DictionaryManager:OnBeginPlay -- Initialize dictionary system and set season list
DictionaryManager:OnOpenDictionary -- Executed when opening dictionary by clicking UI
DictionaryManager:Initialize -- Initialize dictionary category page index and refresh favorite UI
DictionaryManager:OnSelectCategory_1st -- Function to select 1st category and change subcontent accordingly
DictionaryManager:OnSelectCategory_2nd -- Function to select 2nd category and change subcontent accordingly
DictionaryManager:RefreshCategory_3rd -- Function to refresh 3rd category list based on selected 1st, 2nd categories and season
DictionaryManager:OnSelectCategory_3rd -- Function to select 3rd category and change subcontent accordingly
DictionaryManager:UpdateUI_CharList -- Refresh Dictionary > Character list
DictionaryManager:Character_Favorite -- Send character favorite toggle event
DictionaryManager:Item_Favorite -- Send item favorite toggle event
DictionaryManager:RuneCard_Favorite -- Send rune card favorite toggle event
DictionaryManager:UpdateUI_ItemList -- Refresh Dictionary > Item list
DictionaryManager:UpdateUI_RuneCardList -- Refresh Dictionary > Rune card list
DictionaryManager:UpdateUI_GameRulesList -- Update game rules text and image UI based on game rules category
DictionaryManager:SetUI_SeasonDropDownList -- Create and set season dropdown list UI
DictionaryManager:HandleTabChangedEvent -- Handle 1st category tab change
DictionaryManager:HandleTabChangedEvent2 -- Handle 2nd category tab change
DictionaryManager:HandleTabChangedEvent4 -- Handle 3rd category tab change
DictionaryManager:HandleButtonClickEvent4 -- Save favorite data and deactivate UI when dictionary close button is clicked
DictionaryManager:HandleButtonClickEvent -- (De)activate season change dropdown
DictionaryManager:HandleTabChangedEvent3 -- Refresh dictionary content and update UI when season selection changes
UI_CharDictionaryInfo:UpdateInfo -- Update entire character detailed info UI (stats, synergy, skills, etc.)
UI_dictionary_CharacterBT:Initialize -- Leave blank...
UI_dictionary_CharacterBT:UpdateIcon -- Update character icon and background color, reflect favorite status
UI_dictionary_CharacterBT:HandleDictionaryFavoriteEvent -- Update mark display state when favorite change event is received
UI_dictionary_CharacterBT:HandleUITouchDownEvent -- Handle favorite toggle when mouse clicks
UI_dictionary_CharacterBT:HandleUITouchEnterEvent -- Display character info panel and activate outline when mouse hovers
UI_dictionary_CharacterBT:HandleUITouchExitEvent -- Hide info panel and deactivate outline when mouse hover ends
UI_Dictionary_ItemBT:Initialize -- Initialize item button UI component
UI_Dictionary_ItemBT:UpdateIcon -- Update item icon and background, reflect favorite status
UI_Dictionary_ItemBT:HandleDictionaryFavoriteEvent -- Update mark state when item favorite change event is received
UI_Dictionary_ItemBT:HandleUITouchDownEvent -- Handle item favorite toggle when mouse clicks
UI_Dictionary_ItemBT:HandleUITouchEnterEvent -- Display item info panel and activate outline when mouse hovers
UI_Dictionary_ItemBT:HandleUITouchExitEvent -- Hide info panel and deactivate outline when mouse hover ends
UI_dictionary_OpenBT:HandleButtonClickEvent -- Handle dictionary open button click
UI_dictionary_RuneCard:Initialize -- Initialize rune card button UI component
UI_dictionary_RuneCard:UpdateCard -- Update rune card image and background color, reflect favorite status
UI_dictionary_RuneCard:HandleDictionaryFavoriteEvent -- Update mark state when rune card favorite change event is received
UI_dictionary_RuneCard:HandleUITouchDownEvent -- Handle rune card favorite toggle when mouse clicks
UI_dictionary_RuneCard:HandleUITouchEnterEvent -- Display rune card info panel and activate outline when mouse hovers
UI_dictionary_RuneCard:HandleUITouchExitEvent -- Hide info panel and deactivate outline when mouse hover ends
UI_dictionary_SynergyBT:SynergyButtonInitialize -- Initialize synergy button and set icon, character list
UI_dictionary_SynergyBT:FavoriteSynergy -- Simple update of only favorite synergy icon (temporary implementation)
UI_dictionary_SynergyBT:HandleButtonClickEvent -- Display detailed info panel when synergy button is clicked
UI_FavoriteSynergy:Initialize -- Initialize favorite synergy UI component
UI_FavoriteSynergy:UpdateFaveSynergy -- Update favorite synergy UI (icon, activation stage, member count)
UI_FavoriteSynergy:GetSynergyCountText -- Judge from full-time instructor onward
UI_FavoriteSynergy:HandleUITouchEnterEvent -- Display synergy name tooltip when mouse hovers
UI_FavoriteSynergy:HandleUITouchExitEvent -- Hide tooltip when mouse hover ends
UI_ItemDictionaryInfo:OnInitialize -- Initialize item info panel
UI_ItemDictionaryInfo:UpdateUI -- Update entire item info UI and display type-specific extended info
UI_ItemDictionaryInfo:GetItemStatusText -- Format and return item stat info as text
UI_ItemDictionaryInfo:UpdateUI_Extra_Recipes -- In ingredient item screen / Shows all recipes that can be made with this ingredient item
UI_ItemDictionaryInfo:UpdateUI_Extra_Recipe -- In completed item screen / Shows the combination recipe of this item
UI_ItemDictionaryInfo:ItemList_Update -- Update UI for items obtainable from box items
UI_ItemDictionaryInfo:SetItemList_intheBox -- Is this item an 'Item Box'?
UI_LinkedSynergy_BT:UpdateButton -- Update linked synergy button icon and name
UI_LinkedSynergy_BT:Init -- Initialize linked synergy button UI component
UI_RuneCardDictionaryInfo:UpdateInfo -- Update rune card detailed info UI (name, grade, description, etc.)
UI_SynergyDictionaryInfo:UpdateInfo -- Update synergy detailed info UI (icon, description, linked synergies, etc.)
UI_SynergyDictionaryInfo:LinkedCharacterList -- Returns list of characters sharing linked synergy with current synergy
UI_SynergyDictionaryList:CreateSynergyList -- Create synergy list GridView and display initial information
DictionaryDataManager:DataSetInitialize -- Initialize all dictionary data and set to loading complete state
DictionaryDataManager:SetCharacterData -- Function to set character data
DictionaryDataManager:SortCharacterKeyIDs -- Sort and return character IDs by cost
DictionaryDataManager:SetSynergyData -- Sets synergy data
DictionaryDataManager:SetItemData -- Load item status, effects, and season-specific information to build item dictionary
DictionaryDataManager:SetStatusEffectData -- Load status effect data to build status effect dictionary
DictionaryDataManager:SetRuneCardData -- Load rune card information and season-specific data to build rune card dictionary
DictionaryDataManager:GetSortedCharacterIDList -- When season and synergy ID are input, returns corresponding character ID list in sorted state
DictionaryDataManager:GetItemIDList -- When season and synergy ID are input, returns corresponding item ID list in sorted state
DictionaryDataManager:GetRuneIDList -- When season and synergy ID are input, returns corresponding rune card ID list in sorted state
DictionaryDataManager:SetAllGameRulesData -- Function to load game rules text data
UIToggle:OnClick -- Handler that inverts state when toggle button is clicked
UIToggle:SetToggleGroup -- Set and register group that toggle belongs to
UIToggle:SetIsOn -- Set toggle state and call callback
UIToggle:Set -- Internally set toggle state and handle group and callback processing
UIToggle:SetIsOnWithoutNotify -- Set toggle state only without callback
UIToggle:OnInitialize -- Initialize toggle component and connect button events
UIToggle:OnBeginPlay -- Initialize toggle visual effects when game starts
UIToggle:PlayEffect -- Apply visual effects based on toggle state
UIToggleGroup:RegisterToggle -- Register toggle to group
UIToggleGroup:UnRegisterToggle -- Remove toggle from group
UIToggleGroup:NotifyToggleOn -- When specific toggle is activated, deactivate other toggles
UIToggleGroup:AnyToggleOn -- Check if any toggle in group is activated
UIToggleGroup:Contains -- Check if toggle belongs to group and return index
UIToggleGroup:OnBeginPlay -- Ensure valid state of toggle group when game starts
UIToggleGroup:EnsureValidState -- Verify toggle group state and modify if necessary
UIToggleGroup:ActiveToggles -- Return list of all activated toggles
UI_GameResult:SetUI_GameResultPanel -- Set and display all UI elements of game result panel
UI_GameResult:SetUI_LevelInfo_inGameResultPanel -- Set level and experience information in game result panel
UI_GameResult:PlayAnim_EXP -- Plays experience gain animation
ExtendAvatarStateAnimationComponent:ReceiveStateChangeEvent -- Process state change event only when avatar renderer is activated
ExtendPlayerControllerComponent:ActionAttack -- Check if attack is possible in transformed state and execute attack
ExtendPlayerControllerComponent:ActionCrouch -- Execute crouch action if not in transformation
ExtendPlayerControllerComponent:ActionJump -- Check if jump is possible in transformed state and execute jump
ExtendPlayerControllerComponent:OnMapEnter -- Randomly set player position when entering lobby
NewPlayerAvatarComponent:StateChange -- Change transformation avatar state and apply corresponding animation
NewPlayerAvatarComponent:HandleSpriteAnimPlayerEndFrameEvent -- Transition from attack state to current state when animation ends
NewPlayerAvatarComponent:HandleSpriteAnimPlayerStartEvent -- Disable player controller only during attack state when animation starts
PlayerAvatarChangeCompoenent:ClientInitialize -- Initialize transformation avatar and effect entities on client
PlayerAvatarChangeCompoenent:AvatarChange -- Transformation state switching
PlayerAvatarChangeCompoenent:False_change -- Function used when handling complete cancellation rather than transformation switching
PlayerAvatarChangeCompoenent:SetPossibleAction -- Set player's action possibility and movement speed in transformed state
PlayerAvatarChangeCompoenent:ManualAttackEnd -- Manually end attack state and transition to idle state
PlayerAvatarChangeCompoenent:AvatarFlip_forServer -- Set transformation avatar's left-right flip according to player's direction
PlayerAvatarChangeCompoenent:SoundPlay_ForMap -- Play sound and activate effect during transformation
PlayerAvatarChangeCompoenent:EffectPlay_ForServer -- Activate transformation effect on server
PlayerAvatarChangeCompoenent:HandleKeyHoldEvent -- Adjust transformation avatar's direction to match player movement direction during key hold
PlayerAvatarChangeCompoenent:HandleStateChangeEvent -- Detect player state changes and synchronize transformation avatar state
PlayerAvatarChangeCompoenent:HandleKeyDownEvent -- Adjust transformation avatar's direction to match player movement direction on key down
PlayerAvatarChangeCompoenent:HandleEntityMapChangedEvent -- When moving to lobby on map change, initialize other users' transformation states
temp_Effect_Bomb:EnableFalse_forServer -- Disable sprite renderer on server
temp_Effect_Bomb:HandleSpriteAnimPlayerEndFrameEvent -- Handler that disables effect when animation ends
PlayerCollectionDataComponent:InitializeCollection -- Initialize collection data component
PlayerCollectionDataComponent:InitializeCharacterCollectionData -- Function to create on first execution (in each season)
PlayerCollectionDataComponent:InitializeSynergyCollectionData -- Function to create on first execution (in each season)?
PlayerCollectionDataComponent:UpdateCharacterCollectionData -- Update only as much as updateData received during game. Receive data, modify corresponding variable, then save data
PlayerCollectionDataComponent:GetGameOverUnitSet -- For filtering unit data received when game over (character units)
PlayerCollectionDataComponent:UpdateSynergyCollectionData -- Update synergy collection data, save to database, and send UI event
PlayerCollectionDataComponent:GetGameOverSynergySet -- For filtering unit data received when game over (synergy)
PlayerCollectionDataComponent:Get_CharMaxCount -- Call dictionary data structure
PlayerCollectionDataComponent:Get_SynergyMaxCount -- Call dictionary data structure
PlayerCollectionDataComponent:Get_nowCharCount -- Call dictionary data structure
PlayerCollectionDataComponent:Get_nowSynergyCount -- Call dictionary data structure
PlayerCollectionDataComponent:UpdateUI -- Update collection UI and display new collection notification red dot
PlayerCollectionDataComponent:Check_AvaliableChange -- Check if character is level 4 or higher and return avatar change availability
UI_CollectionCharacterCard:Initialize -- Entity set
UI_CollectionCharacterCard:Set_CollectLevel -- Collection level in collection only goes up, never down
UI_CollectionCharacterCard:Set_Star -- Set star display count and position based on collection level
UI_CollectionCharacterCard:Set_NameTag -- Display character name or ??? based on collection status
UI_CollectionCharacterCard:Set_CardImage -- Set card image color and background material based on collection level
UI_CollectionCharacterCard:Set_PlatinumCard -- Card background, outline effect
UI_CollectionCharacterCard:HandleButtonClickEvent -- Display character detailed info UI when character card is clicked
UI_CollectionCharacterCard:HandleCollectionUpdateEvent -- Re-initialize card when collection data is updated
UI_CollectionCharacterInfo:SetInfo -- Set character info UI based on character's collection level and ID
UI_CollectionCharacterInfo:SetInfo_OnlyCharID -- Find collection data with character ID only and set info UI
UI_CollectionCharacterInfo:HandleButtonClickEvent -- Handle character transformation and cooldown when avatar change button is clicked
UI_CollectionManager:OnBeginPlay -- Initialize collection background material and set first open state
UI_CollectionManager:CreateCharColList_NewGrid -- Create character collection list for specified season as GridView
UI_CollectionManager:CreateSynergyColList -- Create synergy collection list for specified season and display on UI
UI_CollectionManager:OnEnable -- Camera zoom in/out
UI_CollectionManager:Set_RateUI -- Set collection rate UI according to selected collection type and display animation
UI_CollectionManager:CloseUI -- Close collection UI and reset camera zoom
UI_CollectionManager:CharList_OnFilter -- Filter and display only level 4 or higher characters
UI_CollectionManager:ChangeSeason -- Change collection list to selected season and refresh UI
UI_CollectionManager:InitSeasonDropdown -- Season dropdown Initialization
UI_CollectionManager:OpenNewSeasonTab -- Check unlocked seasons and create season buttons in dropdown
UI_CollectionManager:HandleButtonClickEvent -- Handle character collection tab button click
UI_CollectionManager:HandleButtonClickEvent2 -- Handle synergy collection tab button click
UI_CollectionManager:HandleButtonClickEvent3 -- (De)activate dropdown when close button is pressed
UI_CollectionManager:HandleButtonClickEvent4 -- Handle collection refresh button click
UI_CollectionManager:HandleButtonClickEvent5 -- Handle level 4 or higher character filter checkbox toggle
UI_CollectionManager:HandleButtonClickEvent6 -- (De)activate dropdown when season button is pressed
UI_CollectionManager:HandleTabChangedEvent -- Handle changing collection to corresponding season when season is changed in season dropdown
UI_CollectionSynergyBC:Initialize -- Initialize synergy collection card and set all stage badges
UI_CollectionSynergyBC:HandleCollectionUpdateEvent -- Update corresponding synergy's grade when synergy collection data is updated
PlayerTouch:HandleTouchEvent -- Player touch event handler (currently disabled)
UI_Profile:RequestData -- Request specified user's profile data and set information to display on UI
UI_Profile:OnOpenUI -- Open profile UI, initialize loading state, and monitor data loading completion
UI_Profile:SetData_DefaultProfile -- Set user's basic profile information (title, level, nickname, avatar) on UI
UI_Profile:SetData_IsPublic -- Reflect profile record and match history public/private settings on UI
UI_Profile:SetData_Record -- Set player's record tab data (highest tier, ranking, play statistics, collection rate)
UI_Profile:SetData_History -- Set player's game history data (wins/losses, mode, rounds, unit info, etc.)
UI_Profile:SetUI_Record -- Update and display record tab UI elements according to data
UI_Profile:SetUI_History -- Update and display game record list on history tab UI
UI_Profile:SetUI_History_GameDetail -- Display selected game's detailed information (rounds, hearts, units, synergies, etc.) on UI
UI_Profile:GetSortedUsedSynergyList -- Sort and return used synergies by priority (stage, count)
UI_Profile:RequestChangePublicInfo -- Save profile public/private setting requested by client to server
UI_Profile:HandlePlayerTouchEvent -- Display profile view button when player is touched
UI_Profile:HandleButtonClickEvent -- Open profile UI and request data when profile view button is clicked
UI_Profile:HandleTabChangedEvent -- Update corresponding UI and tab style when profile tab (record/history) changes
UI_Profile:HandleTabChangedEvent2 -- Display detailed info and update selection style when specific game is selected from game record list
UI_Profile:HandleButtonClickEvent2 -- Handle record public/private toggle button click
UI_Profile:HandleButtonClickEvent3 -- Handle match history public/private toggle button click
UI_Profile:HandleButtonClickEvent4 -- Open own profile UI when view my profile button is clicked
UI_Profile:HandleButtonClickEvent5 -- Open title setting UI when title setting button is clicked
Ranking_UILogic:OnBeginPlay -- Set season time UI and initialize ranking data when game starts
Ranking_UILogic:OnUpdate -- Update time every frame and periodically refresh ranking data
Ranking_UILogic:SetUI_NextOrdinalTime -- Updates 'time remaining until season end' in Lobby HUD
Ranking_UILogic:SetRankingInfo -- Method to set ranking information (currently not implemented)
Ranking_UILogic:HandleButtonStateChangeEvent -- Handle tooltip display/hide when season info tooltip button hover state changes
UI_RewardPopup:HandleButtonClickEvent -- Hide popup and deactivate reward items when reward popup close button is clicked
UI_Reward_inPopup:UpdateReward -- Set reward item ID and quantity and update UI
UI_Reward_inPopup:HandleUITouchExitEvent -- Turn on tooltip entity
TitleLogic:getOtherUserTitle -- Get other user's title data from database and set on client
TitleLogic:setTitle -- Generate and display title text based on title ID
TitleManager:TitleSet -- Change title elements and update title
TitleManager:MakeTitleEntity -- Create title entity when title entity doesn't exist
TitleManager:TitleSet_Client -- Set title entity on client and reflect on UI
TitleManager:Random_Title -- Set title by randomly selecting from owned title elements
TitleManager:TitleDataInitialize -- Function to initialize title data table on first connection
TitleManager:TitleDataUpdate -- Function to update current title data
TitleManager:GetTitle -- Function to acquire title elements
TitleManager:DataSyncToClient -- Synchronize title data sent from server to client
TitleManager:GetAllTitle -- Function to acquire all title elements. (cheat code)
TitleManager:AddtoRedDotTable -- Add newly acquired title elements to red dot display list
TitleManager:InitializeTitle -- Initialize title system and create entities
TitleManager:OnMapEnter -- Event handler called when entering map (currently disabled)
TitleManager:CheckTitleAvaliable -- Check if title element is actually owned on server, and if so, change the title
CooldownType:OnBeginPlay -- Initialize cooldown data table when game starts
KinematicLayerOrderController:HandleChangedMovementInputEvent -- Parameters
PlayerCooldownComponent:CheckAndSetCooldown -- Check cooldown state and set new cooldown if none exists
PlayerCooldownComponent:SetCooldown -- Set cooldown time for specified type
PlayerCooldownComponent:CheckCooldown -- Check only cooldown state of specified type (don't set)
PlayerCooldownComponent:OnDestroy -- Remove corresponding player's map from dynamic map system when entity is destroyed
PlayerLevelLogic:GetRewardEXPAmount -- Function that returns experience amount gained based on game mode and difficulty (clear standard)
PlayerLevelLogic:IsLevelUpCondition -- When current level and experience amount are input, returns whether level up is possible
PlayerLevelLogic:GetRequiredEXP -- Returns experience amount needed to level up to targetLevel. Returns -1 if invalid value is input
PlayerLevelLogic:SetUI_LevelUpPopup -- Changes content of level up popup. Does not enable UI. (separate processing required)
PlayerLevelLogic:EnableUI_LevelUpPopup -- Activates level up popup. Makes it appear gradually over 1 second when activated
PlayerLevelLogic:OnBeginPlay -- Load level up reward list when game starts
PlayerLevelLogic:LoadRewardList -- Load and save level up reward list from data table
GuideToRulesManager:OnBeginPlay -- Initialize guide popup and game rules dataset when game starts
GuideToRulesManager:InitGuideList -- Initialize all guide popups to unwatched state
GuideToRulesManager:PopupWatched -- Record that specific guide popup has been watched
GuideToRulesManager:ActivatePopupMessage -- Activates guide popup
GuideToRulesManager:OffGuideList -- Function to change all guide popups to watched state
GuideToRulesManager:HandleButtonClickEvent -- Open dictionary and navigate to corresponding category when game rules button is clicked
GuideToRulesManager:HandleButtonClickEvent2 -- Mark as watch completed when popup close button is clicked
GuideToRulesManager:HandleNotEnoughCoin -- Display coin-related guide popup when coins are insufficient
GuideToRulesManager:HandleRoundStart -- Display stage-specific guide popup when round starts
GuideToRulesManager:HandleBattleEnd -- Display guide popup when team power is insufficient at battle end
GuideToRulesManager:HandleBuyUnit -- Display placement guide or cost-related guide when purchasing unit
GuideToRulesManager:HandleMergeUnit -- Display upgrade guide when merging units
GuideToRulesManager:HandleBuyItem -- Display item-related guide when purchasing item
GuideToRulesManager:HandleRerollCharacterShop -- Display reroll-related guide when rerolling shop
GuideToRulesManager:HandleBuyEXP -- Display team level related guide when purchasing experience
GuideToRulesManager:HandleLevelUpTeam -- Display team level related guide when team levels up
GuideToRulesManager:HandlePlaceUnit -- Display synergy-related guide when placing unit
GuideToRulesManager:HandleBuyRuneCard -- Display rune card related guide when purchasing rune card
TutorialManager_New:TutorialInitialize -- Initialize all restriction states and flags to default values when tutorial starts
TutorialManager_New:CallAdviceMessage -- Display tutorial guidance message with specified ID on screen
TutorialManager_New:ReRollTest -- Refresh character shop with specified characters in tutorial
TutorialManager_New:SetAllowFeature -- Set allow/restrict state of specific features according to tutorial progress
TutorialManager_New:CheckIsRewardReceived -- Check if tutorial completion reward has been received and give reward if not received
TutorialManager_New:SetRewardReceived -- Give syrup as tutorial completion reward and record receipt status
TutorialManager_New:SetBattleStart -- Function to proceed to battle phase in tutorial
TutorialManager_New:EnableRewardPopup -- Activate reward popup UI and display list of rewards to receive
TutorialManager_New:SetDraggableCharID -- Set currently draggable character ID
TutorialManager_New:SetItemTargetCharID -- Set target character ID to equip item to
TutorialManager_New:SetCurrentTargetTile -- Specify target tile to highlight in tutorial and display on UI
TutorialManager_New:SyncSelectedTile -- Synchronize selected target tile information from server
TutorialManager_New:SetTutorialRejected -- Record that player has skipped tutorial in data
TutorialManager_New:ActivateTutoSelectForServer -- Display tutorial selection UI to players who haven't rejected tutorial
TutorialManager_New:CallShowTile -- Highlight waiting line tile corresponding to specified character
TutorialManager_New:HandleRoundStart -- Set shop for each tutorial stage and display guidance message when round starts
TutorialManager_New:HandlePlaceUnit -- Handle guidance message and tile display according to tutorial stage when placing unit
TutorialManager_New:HandleBuyUnit -- Display guidance message according to tutorial progress when purchasing character
TutorialManager_New:HandleBattleEnd -- Display guidance message according to result and initialize flags when battle ends
TutorialManager_New:HandleMergeUnit -- Check number of level 2 or higher units and display guidance message when merging units
TutorialManager_New:HandleBuyItem -- Display guidance message according to tutorial stage when purchasing item
TutorialManager_New:HandleEquipedItem -- Display guidance message according to specific character and item combination when equipping item
TutorialManager_New:HandleCombinationItem -- Add consumable item and display guidance message when combining items
TutorialManager_New:HandleBuyRuneCard -- Display guidance message according to owned count and activate refresh function when purchasing rune card
TutorialManager_New:HandleBattleOverTime -- Display guidance message only when first occurring during battle overtime
TutorialManager_New:HandleLevelUpTeam -- Display guidance message when reaching specific level during team level up
TutorialManager_New:HandleSellUnit -- Enable features and display guidance message according to specific character sale when selling unit
TutorialManager_New:HandleUseConsumableItem -- Display guidance message according to specific item when using consumable item
TutorialManager_New:HandleButtonClickEvent -- Handle button click that deactivates all tutorial UI elements
TutorialManager_New:HandleButtonClickEvent2 -- Handle button click that deactivates refresh function
TutorialManager_New:HandleKeyDownEvent -- Handle keyboard and mouse input interaction during tutorial
TutorialManager_New:HandleButtonStateChangeEvent -- Display guidance message under specific conditions when button hover state changes
TutorialManager_New:HandleKeyDownEvent2 -- Proceed to next step in specific tutorial situations when ESC key is pressed
CursorPosManager:CheckHoverEntity -- Check entity at mouse cursor position and apply highlight effect
CursorPosManager:HandleMouseMoveEvent -- Check entity at cursor position and handle highlighting when mouse moves
CursorPosManager:HandleKeyDownEvent -- Display unit info and handle player touch events according to mouse click when key is pressed
UI_AlphaDesolve:DesolveToDisable -- Gradually make UI transparent and disable
UI_AlphaDesolve:DesolveToEnable -- Gradually make UI appear and enable
UI_AlphaDesolve:HandleButtonStateChangeEvent -- Handle feedback message display when button state changes
UI_CameraZoomLogic:Zoom -- Toggle camera zoom in/out in lobby to enlarge/reduce character display
UI_DragMoverComponent:HandleUITouchDragEvent -- Move target UI within specified boundaries during UI touch drag
UI_FlyingUIEntity:OnUpdate -- Move UI entity from start point to destination with flight animation
UI_GameResultTooltipEnabler:OnUpdate -- Update tooltip position to match cursor position while mouse is hovering
UI_GameResultTooltipEnabler:HandleUITouchEnterEvent -- Activate tooltip message when mouse enters
UI_GameResultTooltipEnabler:HandleUITouchExitEvent -- Deactivate tooltip when mouse exits
UI_HideButtonComponent:InitHideState -- Initialize hide state
UI_HideButtonComponent:HideTargetUI -- Turn off all entities except self
UI_HideButtonComponent:HandleButtonClickEvent -- Toggle UI hide/show state when button is clicked
UI_HUD_HoverSynergy:SetSynergyHoverOutline -- When mouse is placed on synergy, display tiles for units with that synergy
UI_HUD_HoverSynergy:HandleUITouchEnterEvent -- Display tooltip and highlight units when mouse enters synergy UI
UI_HUD_HoverSynergy:HandleUITouchExitEvent -- Hide tooltip and remove unit highlighting when mouse exits synergy UI
UI_LevelUpPopup_RewardButton:OnUpdate -- Dynamically adjust tooltip size to match content while hovering
UI_LevelUpPopup_RewardButton:HandleUITouchEnterEvent -- Display reward tooltip when mouse enters
UI_LevelUpPopup_RewardButton:HandleUITouchExitEvent -- Hide tooltip when mouse exits
UI_Mask:SetMask -- Set mask based on target UI and darken surrounding background
UI_Mask:SetMaskWithPos -- Set mask by receiving mask position and size
UI_Mask:OnBeginPlay -- Apply pulse animation in highlight mode
UI_Mask:SetMaskWithRUID -- Set mask image and size using resource ID
UI_Mask:SetMaskSizeMatch -- Adjust background area size to match current mask size
UI_ShortCutKeyChangeButton:HandleButtonClickEvent -- Activate shortcut key change mode when button is clicked
UI_SynergyList_EachSlotBackground:OnBeginPlay -- Find and save synergy name and level UI elements when game starts
UI_SynergyList_EachSlotBackground:OnUpdate -- Dynamically adjust background size to match synergy name and level text size
UI_Tooltip:OnBeginPlay -- Initialize tooltip system and set UI list when game starts
UI_Tooltip:ClearAllTooltipUI -- Deactivate all tooltip UIs to clear screen
UI_Tooltip:SetMouseHoveredUI -- Set UI entity currently being hovered by mouse
UI_Tooltip:OnUpdate -- Real-time update of size and position of activated tooltip UI every frame
UI_Tooltip:SetSkillInfo -- Activate/deactivate tooltip displaying character's skill information
UI_Tooltip:Update_SkillInfo -- Dynamically adjust size and position based on skill info tooltip content length
UI_Tooltip:Update_RecommendItemInfo -- Dynamically adjust recommended item tooltip position based on unit info window position
UI_Tooltip:SetSynergyInfo -- Set synergy info tooltip and update content based on activation state
UI_Tooltip:Update_SynergyInfo -- Adjust synergy info tooltip position to prevent going off screen
UI_Tooltip:SetStatInfo -- Set unit's stat info tooltip and display detailed information
UI_Tooltip:Update_StatInfo -- Adjust size based on stat tooltip content length and set position to match unit info window
UI_Tooltip:SetItemInfo -- Set item info tooltip and display item's detailed information
UI_Tooltip:SetItemEquipInfo -- Set tooltip information displayed when equipping item to specific character
UI_Tooltip:Update_ItemInfo -- Adjust size based on item tooltip content and set position based on display type
UI_Tooltip:SetGoldsRewardInfoUI -- Calculate and display information about gold acquisition methods and reward amounts in tooltip
UI_Tooltip:SetEXPInfoUI -- Calculate and display experience acquisition methods and quantity information in tooltip
UI_Tooltip:SetRuneInfoUI -- Set tooltip displaying rune card information and status
UI_Tooltip:Update_RuneInfo -- Adjust size based on rune card tooltip content and tags, and set position by display type
UI_Tooltip:SetGameModeInfo -- Set tooltip content displaying game mode and season information
UI_Tooltip:Update_GameModeInfo -- Dynamically adjust game mode tooltip size based on presence of penalty information
UI_Tooltip:SetCharShopInfo -- Set tooltip displaying character information and skills in character shop
UI_Tooltip:Update_CharShopInfo -- Adjust UI element positions and overall size based on character shop tooltip content length
UI_Tooltip:SetRuneInfoUI_OnBattlePhase -- Set tooltip displaying simple rune card information during battle phase
UI_Tooltip:SetBattleStatValue -- Set tooltip displaying name and value of specific stat in battle statistics
UI_Tooltip_SynergyInfo:OnUpdate -- Adjust positions of component entities
UI_TutoButtonAnimation:AdjustTutoSelectButtonSize -- Animation for adjusting size of button to select whether to proceed with tutorial
UI_TutoButtonAnimation:HandleButtonClickEvent -- Handle state change and animation when tutorial play button is clicked
UI_TutoButtonAnimation:HandleButtonClickEvent2 -- Handle state change and animation when tutorial skip button is clicked
UI_TutoButtonAnimation:HandleButtonClickEvent3 -- Handle third button click event (toggle play state)
UI_TutorialLogic:OnBeginPlay -- Initialize tutorial system and load necessary datasets
UI_TutorialLogic:ActivateTutoSelect -- Activate UI to select tutorial proceed or skip
UI_TutorialLogic:ActivateAdviceMessage -- Activates guidance message from guide character
UI_TutorialLogic:DeactivateAdviceMessage -- Deactivates Pink Bean's message
UI_TutorialLogic:BattleButtonOnOff -- Function to show/hide battle start button during tutorial progress
UI_TutorialLogic:SetDragGuide -- Activate inter-entity interaction guide
UI_TutorialLogic:SetSkipButton -- Set activation state of tutorial skip button
UI_TutorialLogic:DeactivateMaskAndHighlight -- Deactivate all tutorial masks and highlight effects
UI_TutorialLogic:ActivateInteractionArrow -- Activate or deactivate specified interaction arrow guide
UI_TutorialLogic:DeactivateAllTutorialUI -- Deactivate all tutorial-related UI
UI_TutorialLogic:ClickAdviceMessage -- Move to next page or exit when guidance message is clicked
UI_TutorialLogic:ShowSynergyTile -- Highlight characters corresponding to specified synergy
UI_TutorialLogic:ShowFieldTile -- Show battlefield tiles
UI_TutorialLogic:ShowTargetTile -- Display currently targeted tile on screen
UI_TutorialLogic:checkAvailableTile -- Search for empty tiles before placement
UI_TutorialLogic:checkTargetWaitLine -- Search for waiting seat tile where specified character is located
UI_TutorialLogic:showTargetWaitLine -- Show target waiting seat
UI_TutorialLogic:setUnitArrow -- Activate or deactivate unit arrow with specified number
UI_TutorialLogic:DragEntityWithPos -- Activate inter-vector interaction guide
UI_TutorialLogic:SetTutoTileRUID -- Set tutorial tile sprite to destination or normal tile
UI_TutorialLogic:CheckFieldcharTile -- Search for battlefield tile where specified character is located
UI_TutorialLogic:SetUnitGuideLine -- Determine position of line guiding unit placement
UI_TutorialLogic:GetArenaTile -- Get TileNum-th tile from LineNum-th row among battlefield tiles
UI_TutorialLogic:SetUnitGuideLine_Entity -- Determine position of line guiding unit placement
UI_TutorialLogic:SetMaskStretchAll -- Change size and position according to maskType
UI_TutorialLogic:GetMaskOffsetFromArena -- Get offset coordinates for masking
UI_TutorialLogic:OnUpdate -- When mask is on, get current screen size and update in real-time
UI_TutorialLogic:ScreenPostoUIPos -- Convert screenpos to UIpos
UI_TutorialLogic:SetDragItemGuide -- Activate inter-vector interaction guide
UI_TutorialLogic:SetHPGaugePos -- Adjust current position of gauge guidance mask
UI_TutorialLogic:SetArenaMapPath -- Generate and return current player's arena map path
UI_TutorialLogic:HandleKeyDownEvent -- Process keyboard input for tutorial progression and UI control
UI_TutorialLogic:HandleButtonClickEvent6 -- Handle button click event (currently disabled)
UI_TutorialLogic:HandleButtonClickEvent8 -- Handle movement to lobby when tutorial reject/skip button is clicked
UI_WorldExitTooltipEnabler:HandleMouseMoveEvent -- Activate world exit tooltip in upper right area of screen when mouse moves
UnitSkillDescLogic:GetDefaultDesc -- Generate and return unit's skill description in default format
UnitSkillDescLogic:GetDetailDesc -- Generate and return unit's detailed skill description by level
UnitSkillDescLogic:GetStatusEffectList -- Return list of status effects possessed by unit
UnitSkillDescLogic:GetColorTextFromNumberValue -- Convert value to text with rich text added according to specified colorType and return
UnitSkillDescLogic:GetColorTextFromStringValue -- Convert value to text with rich text added according to specified colorType and return
LoadingManager:SetEnableUI -- Set activation state of loading UI and handle background music fade
LoadingManager:SetProgressUI -- Reflect loading progress to UI
LoadingManager:OnSyncProperty -- Calculate and update loading progress when synchronized property changes
LoadingManager:ClearLoadedCount -- Initialize loading count and set necessary loading items
LoadingManager:GameStart -- Start game after loading completion and move to next phase
UI_Loading:SetEnableUI -- Set activation state of loading UI elements and apply fade animation
UI_Loading:SetProgressUI -- Function to change progress and update UI accordingly. Apply animation effects when changing
UI_Loading:PlayLoadingAnim -- Play animation at front of queue
UI_Loading:OnUpdate -- Manage loading tip update timer
UI_Loading:UpdateUI_Tip -- Randomly update tip text to display on loading screen
UI_Loading:HandleButtonClickEvent -- Check loading completion when game start button is clicked and request game start
UI_Loading_Spinner:OnBeginPlay -- Initialize child entities for spinner animation
UI_Loading_Spinner:OnUpdate -- Update spinner animation every frame
UI_Loading_TextBlinker:OnUpdate -- Implement blinking effect by periodically changing text color
UI_Color:OnBeginPlay -- Load and initialize various color information used in game from data table
UI_ActivateTooltipOnMouseHover:OnUpdate -- Update tooltip position in real-time
UI_ActivateTooltipOnMouseHover:HandleUITouchEnterEvent -- Activate tooltip when mouse enters UI area (PC platform only)
UI_ActivateTooltipOnMouseHover:HandleUITouchExitEvent -- Deactivate tooltip when mouse leaves UI area (PC platform only)
UI_AutoScroll:OnBeginPlay -- Initialize auto scroll component and set scroll type
UI_AutoScroll:OnUpdate -- Update auto scroll position every frame
UI_AutoScroll:InitScroll -- Initialize scroll position
UI_ButtonClickSoundComponent:HandleButtonClickEvent -- Play designated sound when button is clicked
UI_ButtonClickSoundComponent:HandleUITouchDownEvent -- Play designated sound when UI touch down occurs
UI_ExitButton:HandleButtonClickEvent -- Deactivate designated target UI when button is clicked
UI_OpenButton:HandleButtonClickEvent -- Activate designated target UI when button is clicked
CustomScrollLayoutComponent:OnBeginPlay -- Initialize custom scroll layout and connect drag events
CustomScrollLayoutComponent:SortingChildrenEntities -- Arrange child entities according to specified sorting method
CustomScrollLayoutComponent:SetCurrentScroll -- Set current scroll position and send event
CustomScrollLayoutComponent:SetChildrenCount -- Set child entity count and calculate maximum scroll count
CustomScrollLayoutComponent:MoveScroll -- Move scroll position according to scroll wheel input
CustomScrollLayoutComponent:SetScrollBar -- Set scrollbar size and position according to current scroll state
CustomScrollLayoutComponent:OnDragScrollBar -- Update scroll position when dragging scrollbar
CustomScrollLayoutComponent:HandleMouseScrollEvent -- Handle mouse scroll wheel event
CustomScrollLayoutComponent:HandleUITouchEnterEvent -- Set flag when mouse enters scroll area
CustomScrollLayoutComponent:HandleUITouchExitEvent -- Clear flag when mouse leaves scroll area
CustomScrollLayoutComponent:HandleEntityCreateEditorEvent -- Perform automatic sorting when child entity is created in editor
DropDownBtnComponent:OnBeginPlay -- Set parent entity reference for dropdown button
DropDownBtnComponent:ChangeStateOfTheList -- Show/hide dropdown list and change selected text
DropDownBtnComponent:HandleButtonClickEvent -- Change list state when dropdown button is clicked
DropDownComponent:OnBeginPlay -- Set dropdown button list entity reference
DropDownComponent:ChangeStateOfTheList -- Toggle dropdown list show/hide state
DropDownComponent:HandleButtonClickEvent -- Change list state when dropdown main button is clicked
ImageFontComponent:SetText -- Set image font text and update UI
ImageFontComponent:SetColor -- Set image font color and update UI
ImageFontComponent:SetShadow -- Set image font shadow effect and update UI
ImageFontComponent:HandleScreenTouchEditorEvent -- Handle image font update when screen is touched in editor
ImageFontComponent:HandleTextInputSubmitEditorEvent -- Handle when text input is submitted in editor
ImageFontComponent:HandleTextInputEndEditEditorEvent -- Handle when text input ends in editor
UI_ImageFontService:OnBeginPlay -- Load image font data from dataset and store in cache
UI_ImageFontService:IsValidCharacter -- Check if specified character is valid character supported by image font
UI_ImageFontService:Refresh -- Decompose image font entity's text into individual character images and display
TabComponent:OnBeginPlay -- Initialize tab component and activate first tab
TabComponent:ChangeTab -- Switch to tab with specified index and send event
TabComponent:EnableChildrenEntities -- Control activation state of all tab buttons
TabComponent:OnTabButtonClicked -- Switch to corresponding tab and send event when tab button is clicked
TabComponent:SetChildren -- Find tab buttons from child entities, register to list, and connect events
UITweenAlpha:OnBeginPlay -- Initialize UI alpha tween component and set auto play
UITweenAlpha:OnUpdate -- Update alpha tween animation every frame
UITweenAlpha:Play -- Start alpha tween animation playback
UITweenAlpha:PoingPonng -- Calculate time value in ping-pong mode (back and forth)
UITweenAlpha:Repeat -- Calculate repeating time value in loop mode
UITweenAlpha:Stop -- Stop alpha tween animation
UITweenAlpha_GroupCanvas:OnBeginPlay -- Initialize UI group canvas alpha tween component
UITweenAlpha_GroupCanvas:OnUpdate -- Update group alpha tween animation every frame
UITweenAlpha_GroupCanvas:Play -- Start group alpha tween animation playback
UITweenAlpha_GroupCanvas:Stop -- Stop group alpha tween animation
UITweenPosition:OnBeginPlay -- Initialize UI position tween component
UITweenPosition:OnUpdate -- Update position tween animation every frame
UITweenPosition:Play -- Start position tween animation playback
UITweenPosition:Stop -- Stop position tween animation
UITweenPosition_Stretch:OnBeginPlay -- Initialize UI stretch position tween component
UITweenPosition_Stretch:OnUpdate -- Update stretch position tween every frame
UITweenPosition_Stretch:Play -- Start stretch position tween playback
UITweenPosition_Stretch:Stop -- Stop stretch position tween
UITweenRotate:OnBeginPlay -- Initialize UI rotation tween component
UITweenRotate:OnUpdate -- Update rotation tween every frame
UITweenRotate:Play -- Start rotation tween playback
UITweenRotate:Stop -- Stop rotation tween
UITweenScale:OnBeginPlay -- Initialize UI scale tween component
UITweenScale:OnUpdate -- Update scale tween every frame
UITweenScale:Play -- Start scale tween playback
UITweenScale:Stop -- Stop scale tween
ArenaUI_BattleStartButton:OnUpdate -- Handle time counting and UI update while battle start button is pressed
ArenaUI_BattleStartButton:PressButton -- Battle start button press/cancel logic and game phase transition handling
ArenaUI_BattleStartButton:HandleButtonClickEvent -- Execute button press when battle start button is clicked
ArenaUI_BattleStartButton:HandleButtonClickEvent2 -- Handle battle preparation cancellation when cancel button is clicked
ArenaUI_BattleStartButton:HandleKeyDownEvent -- Handle battle preparation cancellation when ESC key is pressed
UIManager_ArenaReadyPhase:UI_ChangeUIDisplay_Default -- Change to default UI display state (empty)
UIManager_ArenaReadyPhase:HandleButtonClickEvent2 -- Handle UI toggle when inventory panel expand/collapse button is clicked
UI_BattleTeamInfo_RuneButton:SetProperty -- Set rune button's name, description, grade, and cost information
UI_BattleTeamInfo_RuneButton:HandleButtonStateChangeEvent -- Handle tooltip display and special effects when rune button is moused over/out
UI_CharShopProduct:InitProperty -- Initialize references for character shop product UI elements
UI_CharShopProduct:CheckTutorial -- Check if character purchase is possible for corresponding slot during tutorial progress
UI_CharShopProduct:HandleButtonClickEvent -- Handle purchase processing and validation when character product is left-clicked
UI_CharShopProduct:HandleUITouchEnterEvent -- Display tooltip information when mouse hovers over character product
UI_CharShopProduct:HandleUITouchDownEvent -- Display detailed information popup when character product is right-clicked
UI_CharShopProduct:HandleUITouchExitEvent -- Turn off all tooltips when touch leaves
UI_HPShrinkBar:OnUpdate -- Update HP bar shrink animation
UI_HPShrinkBar:Lerp -- Calculate linear interpolation between two values
UI_HPShrinkBar:OnBeginPlay -- Initialize HP bar entity and set target HP bar reference
UI_Inventory:OnBeginPlay -- Initialize inventory system and update UI
UI_Inventory:ResistCache -- Load item information from dataset and store in cache
UI_Inventory:RefreshUI_ItemInventory -- Update inventory UI with item list owned by player
UI_Inventory:RefreshUI_ByOnSyncProperty -- Initialize inventory UI to first page and update when sync property changes
UI_Inventory:ShowItemSelectPopup -- Control item selection popup UI display when opening/closing item box and handle tween animation
UI_Inventory:RefreshPageMoveButton -- Update inventory page movement button activation/deactivation state and page information
UI_Inventory:RefreshUI_RuneInventory -- Display rune card information owned by player on UI and apply visual effects
UI_Inventory:SetReddot -- Control whether to display red dot on inventory next page button
UI_Inventory:RefreshUI_BattleRuneList -- Update player's rune card description information in battle phase
UI_Inventory:HandleButtonClickEvent -- Move to previous page and update UI when inventory previous page button is clicked
UI_Inventory:HandleButtonClickEvent2 -- Move to next page and update UI when inventory next page button is clicked
UI_InventoryItemSlot:HandleUITouchEnterEvent -- Display outline and tooltip when mouse hovers over inventory item slot
UI_InventoryItemSlot:HandleUITouchExitEvent -- Deactivate outline and tooltip when mouse leaves inventory item slot
UI_InventoryItemSlot:HandleUITouchBeginDragEvent -- Activate outline and set drag state when inventory item drag starts
UI_InventoryItemSlot:HandleUITouchEndDragEvent -- Deactivate outline and clear drag state when inventory item drag ends
UI_InventoryItemSlot:HandleUITouchDownEvent -- Display item combination table tooltip when inventory item is right-clicked
UI_ItemSelect_ItemSlot:HandleUITouchEnterEvent -- Display outline and tooltip when mouse hovers over item selection slot
UI_ItemSelect_ItemSlot:HandleUITouchExitEvent -- Deactivate outline and tooltip when mouse leaves item selection slot
UI_ItemSelect_ItemSlot:HandleUITouchDownEvent -- Select item when item selection slot is clicked and display combination table when right-clicked
UI_ItemShopSlot:HandleUITouchDownEvent -- Display combination table tooltip when item slot is right-clicked
UI_ItemShopSlot:HandleUITouchEnterEvent -- Display item info tooltip when mouse enters item slot
UI_ItemShopSlot:HandleUITouchExitEvent -- Hide tooltip when mouse exits item slot
UI_RuneInventroyItemButton:OnBeginPlay -- Initialize rune inventory item button
UI_RuneInventroyItemButton:SetProperty -- Set rune card's attribute information
UI_RuneInventroyItemButton:HandleButtonStateChangeEvent -- Display tooltip when rune inventory button hover state changes
UI_RuneInventroyItemButton:HandleUITouchBeginDragEvent -- Handle when rune card drag starts
UI_RuneInventroyItemButton:HandleUITouchEndDragEvent -- Handle when rune card drag ends
UI_RuneInventroyItemButton:HandleUITouchEnterEvent -- Set current hovering slot when mouse enters rune card slot
UI_RuneRerollButton:HandleButtonClickEvent -- Perform reroll when rune card reroll button is clicked
UI_RuneShopProductButton:SetProperty -- Set rune shop product's attribute information
UI_RuneShopProductButton:HandleButtonStateChangeEvent -- Display tooltip when rune shop product button hover state changes
UI_SynergyList:SetEnableSynergyHoverUI -- Activate/deactivate synergy hover UI and display information
UI_SynergyList:RefreshSynergyList -- Sort current synergy list to reflect on UI
UI_SynergyList:RefreshUI -- Function to refresh synergy list
UI_SynergyList:OnBeginPlay -- Initialize synergy list
UI_SynergyList:GetSortedSynergyList -- Sort and return synergy list acquired through units, items, rune cards, and coaches
UI_SynergyList:GetSortedSynergyListByCharID -- Sort and return synergy list based on character ID
UI_SynergyListComponent:SetEnableSynergyHoverUI -- Activate/deactivate synergy hover UI and display information
UI_SynergyListComponent:RefreshSynergyList -- Sort current synergy list to reflect on UI
UI_SynergyListComponent:RefreshUI -- Function to refresh synergy list
UI_SynergyListComponent:OnBeginPlay -- Initialize synergy list component
UI_SynergyListNextPageButton:HandleButtonClickEvent -- Switch page when synergy list next page button is clicked
UI_UnitInfoPopup:OnBeginPlay -- Initialize unit info popup and load dataset
UI_UnitInfoPopup:ConnectToSelectedUnit -- Make right-clicked entity the connected entity
UI_UnitInfoPopup:UI_Close -- Disconnect from unit when closing popup
UI_UnitInfoPopup:UI_Init -- Initialize UI based on connected unit's basic information
UI_UnitInfoPopup:UI_Update -- Function to update info window by receiving unit stat information
UI_UnitInfoPopup:UI_Update_WhenMerged -- Function to update information if merged character was the character being viewed with right-click during character merge
UI_UnitInfoPopup:UI_Update_StarInfo -- Update information related to star rating of currently viewed unit
UI_UnitInfoPopup:UI_MoveOnPhaseChanged -- Move UI position when phase changes
UI_UnitInfoPopup:UI_ShowCoachInfoTooltip -- Display coach information tooltip
UI_UnitInfoPopup:UI_ShowFromCharacterShop -- Display detailed information of corresponding character when right-clicking each product in character shop
UI_UnitInfoPopup:HandleKeyDownEvent -- Handle keyboard/mouse input
UI_UnitInfoPopup:HandleButtonStateChangeEvent -- Handle skill info button hover state change
UI_UnitInfoPopup:HandleButtonStateChangeEvent2 -- Handle recommended item button hover state change
UI_UnitInfo_HoverSkill:HandleButtonStateChangeEvent -- Display skill tooltip when skill info button hover state changes in unit info
UI_UnitInfo_HoverStat:HandleUITouchEnterEvent -- Display stat info tooltip when mouse enters unit stat
UI_UnitInfo_HoverStat:HandleUITouchExitEvent -- Hide stat info tooltip when mouse exits unit stat
UI_UnitInfo_HoverSynergy:HandleUITouchEnterEvent -- Display synergy info tooltip when mouse enters unit synergy
UI_UnitInfo_HoverSynergy:HandleUITouchExitEvent -- Hide synergy info tooltip when mouse exits unit synergy
UI_UnitInfo_ItemSlot:HandleUITouchEnterEvent -- Display item info tooltip when mouse enters unit item slot
UI_UnitInfo_ItemSlot:HandleUITouchExitEvent -- Hide item info tooltip when mouse exits unit item slot
UI_UnitInfo_ItemSlot:HandleUITouchDownEvent -- Display combination table tooltip when unit item slot is right-clicked
UI_UnitSkillInfo:SetEnableSkillHoverUI -- Activate/deactivate unit skill info hover UI and display information
UI_ChanceExpandButton:SetButtonShape -- Change arrow UI
UI_ChanceExpandButton:HandleButtonClickEvent -- Handle probability table expand/collapse button click
UI_ChanceTable:ShowTooltip -- Display/hide duplicate reward tooltip
UI_ChanceTable:Init -- Initialize coach probability table
UI_ChanceTable:RequestShopProbability -- Request shop probability data
UI_ChanceTable:OnBeginPlay -- Initialize probability table
UI_ChanceTable:ShowSmallSlots -- Display/hide detailed probability slots
UI_ChanceTable:HandleButtonStateChangeEvent -- Tooltip appears when mouse hovers over duplicate reward button
UI_CoachInventory_CoachSlot:HandleButtonStateChangeEvent -- Display coach info tooltip when coach slot button hover state changes
UI_CoachInventory_CoachSlot:HandleButtonClickEvent -- Set coach companionship when coach slot button is clicked
UI_CombineTable_ItemTooltipActivator:HandleButtonStateChangeEvent -- Display item info tooltip when hovering over item in combination table
UI_LobbyCoachInventory:OnBeginPlay -- Initialize coach inventory UI and connect events
UI_LobbyCoachInventory:RefreshFollowingCoach -- Update accompanying coach panel content
UI_LobbyCoachInventory:RefreshCoachList -- Update coach list in coach inventory
UI_LobbyCoachInventory:RefreshCurrencyList -- Update currency information UI
UI_LobbyCoachInventory:ChangeFollowingCoach_Check -- Send selected accompanying coach to server and validate
UI_LobbyCoachInventory:ChangeFollowingCoach_Client -- Client processing after coach change completion
UI_LobbyCoachInventory:ChangeCoachList_OnClient -- Display toast message after coach change completion
UI_LobbyCoachInventory:SetCoachUnfollow -- Function to unfollow currently accompanying coach
UI_LobbyCoachInventory:SetCoachFollow -- Execute when specific coach is selected from coach inventory
UI_LobbyCoachInventory:OnClick_MasterCoachEffect -- Function to turn master coach effect On/Off
UI_LobbyCoachInventory:EnableMasterCoachEffect -- Activate/deactivate master coach effect button
UI_LobbyCoachInventory:HandleButtonClickEvent -- Update list when coach inventory open button is clicked
UI_LobbyCoachInventory:HandleTabChangedEvent -- Execute when grade filter is changed in coach inventory UI
UI_LobbyCoachInventory:HandleButtonClickEvent2 -- Send changes to server when coach change complete button is clicked
UI_LobbyCoachInventory:HandleButtonClickEvent4 -- Toggle sorting option when owned coach sort button is clicked
UI_LobbyCoachInventory:HandleButtonClickEvent3 -- Refresh coach list when opening coach inventory
UI_LobbyHUD:RefreshUI_LobbyHUD_GameStart -- Function to update lobby HUD UI when saved data exists
UI_LobbyHUD:HandleButtonClickEvent -- Empty event handler
UI_LobbyHUD:HandleButtonClickEvent2 -- Empty event handler
UI_LobbyHUD:HandleButtonClickEvent3 -- Open ESC menu when settings button is clicked
UI_LobbyLevelSelect:OnBeginPlay -- Initialize level select UI and connect events
UI_LobbyLevelSelect:RefreshUI_SeasonLevelInfo -- Update season and difficulty related information UI
UI_LobbyLevelSelect:SetCoachChangeMode -- Activate/deactivate coach change mode
UI_LobbyLevelSelect:RefreshCurrentSelectedCoaches -- Refresh currently selected coach list UI
UI_LobbyLevelSelect:RefreshCoachList -- Update coach list in 'coach selection popup'
UI_LobbyLevelSelect:SelectCoach -- Execute when specific coach is selected in coach selection popup
UI_LobbyLevelSelect:UnselectCoach -- Execute when specific coach is deselected while coach selection popup is open
UI_LobbyLevelSelect:ChangeCoachList_Check -- Validate and save selected coach list on server
UI_LobbyLevelSelect:ChangeCoachList_OnClient -- Client UI processing after coach change completion
UI_LobbyLevelSelect:SetEnteranceMode -- Switch between (default mode <-> entrance waiting mode)
UI_LobbyLevelSelect:Cancle_CoachSelectMode -- Execute when 'close' is pressed in coach change popup
UI_LobbyLevelSelect:RefreshUI_LevelSelectPanel -- Refresh level selection panel (level list)
UI_LobbyLevelSelect:RefreshUI_ModeSelectPanel -- Check entrance conditions of mode selection panel and update UI
UI_LobbyLevelSelect:OnButtonClick_ModeSelect -- Function to execute when each mode button is pressed in mode selection screen
UI_LobbyLevelSelect:OnEndPlay -- Clean up timers when script ends
UI_LobbyLevelSelect:HandleButtonClickEvent8 -- When "continue" is pressed in HUD
UI_LobbyLevelSelect:HandleButtonClickEvent3 -- Execute when "change coach (open popup)" button is pressed in main panel
UI_LobbyLevelSelect:HandleButtonClickEvent4 -- Handle coach selection popup close button
UI_LobbyLevelSelect:HandleButtonClickEvent5 -- Execute when 'replacement complete' is pressed in coach change popup
UI_LobbyLevelSelect:HandleTabChangedEvent2 -- Execute when grade filter is changed in coach selection UI
UI_LobbyLevelSelect:HandleCustomScrollChangedEvent -- Execute when coach list scroll changes
UI_LobbyLevelSelect:HandleButtonClickEvent6 -- Switch to entrance mode when game entrance button is clicked
UI_LobbyLevelSelect:HandleButtonClickEvent7 -- Execute when 'yes' button is pressed in 'continue' popup that appears when there is previously saved game
UI_LobbyLevelSelect:HandleButtonClickEvent9 -- Handle new game start button in continue popup
UI_LobbyLevelSelect:HandleButtonClickEvent10 -- Execute when 'close' is pressed in main panel
UI_LobbyLevelSelect:HandleTabChangedEvent3 -- Execute when coach preset button changes
UI_LobbyLevelSelect:HandleButtonClickEvent12 -- Open level selection panel when level selection button is clicked
UI_LobbyLevelSelect:HandleTabChangedEvent4 -- Execute when season tab changes in level selection panel
UI_LobbyLevelSelect:HandleButtonClickEvent13 -- Execute when 'game start' button is pressed in HUD, opens game mode selection screen
UI_LobbyLevelSelect_LevelSlot:HandleButtonClickEvent -- Select corresponding level and close level selection panel when level slot is clicked
UI_LobbyLevelSelect_ModeButton:HandleButtonStateChangeEvent -- Handle description text animation when mode button hover state changes
UI_LobbyLevelSelect_ModeButton:HandleButtonClickEvent -- Switch to corresponding mode when mode button is clicked
UI_PlayerTitleButton:callTitleElementList -- Load title elements matching current button to list
UI_PlayerTitleButton:TitleElementChange -- Change title element and upload to server
UI_PlayerTitleButton:elementSelected -- Update currently equipped title element to UI
UI_PlayerTitleButton:SetNameTagFontColor -- Function to set font color according to nametag's Rank value
UI_PlayerTitleButton:TitleSettingInit -- Display currently equipped title information when initializing title setting UI
UI_PlayerTitleButton:ButtonChangeColor -- Change color according to button selection state
UI_PlayerTitleButton:ActivateButton -- Initialize list and set UI when activating title element button
UI_PlayerTitleButton:HandleButtonClickEvent -- Execute corresponding function when title-related button is clicked
UI_PlayerTitleButton:HandleButtonClickEvent2 -- Activate profile UI and camera zoom when profile open button is clicked
UI_PlayerTitleSetting:InitOwnedTable -- Create table of currently owned title elements
UI_PlayerTitleSetting:CheckOwnedOnly -- Toggle owned titles only view option and update list
UI_PlayerTitleSetting:GetNextTitleList -- Update list with next 8 title elements
UI_PlayerTitleSetting:GetPreviousTitleList -- Update list with previous 8 title elements
UI_PlayerTitleSetting:AddToOwnedTable -- Add newly acquired title element to owned list
UI_PlayerTitleSetting:HandleButtonClickEvent -- Toggle filter when owned titles only view button is clicked
UI_PlayerTitleSetting:HandleButtonClickEvent2 -- Update list when next page arrow button is clicked
UI_PlayerTitleSetting:HandleButtonClickEvent3 -- Update list when previous page arrow button is clicked
UI_PlayerTitleSetting:HandleButtonClickEvent4 -- Generate random title when random title combination button is clicked
UI_PlayerTitleSetting:HandleMouseScrollEvent -- Move title list pages with mouse scroll
UI_SimpleTooltipActivator:HandleUITouchEnterEvent -- Display tooltip when mouse hovers
UI_SimpleTooltipActivator:HandleUITouchExitEvent -- Hide tooltip when mouse hover ends
