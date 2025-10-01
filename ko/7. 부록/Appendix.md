UIPopup:Open -- 팝업을 열고 메시지와 콜백 함수를 설정
UIPopup:OnClickOk -- 확인 버튼 클릭 시 콜백 실행 후 팝업 닫기
UIPopup:OnClickCancel -- 취소 버튼 클릭 시 콜백 실행 후 팝업 닫기
UIPopup:Close -- 팝업을 닫고 이벤트 연결 해제
UIPopup:StartTween -- 팝업 열기/닫기 트윈 애니메이션 시작
UIToast:ShowMessage -- 토스트 메시지를 화면에 표시
UIToast:StartTween -- 토스트 메시지의 페이드 인/아웃 트윈 애니메이션 시작
UIToast:ShowMessageByLocalizingKey -- 로컬라이제이션 키를 사용하여 토스트 메시지 표시
CheatButton:HandleButtonClickEvent -- 치트 버튼 클릭 시 해당 치트 명령어 실행
CheatButton_DictionaryType:HandleButtonClickEvent -- 타입별 치트 아이템 획득 버튼 클릭 처리
CheatButton_New:HandleButtonClickEvent -- 새로운 치트 버튼 클릭 시 입력값과 함께 치트 실행
CheatManager:OpenCheatPanel -- 치트 패널 열기 (권한 확인 후)
CheatManager:OpenCheatPanelOnClient -- 클라이언트에서 치트 UI 활성화
CheatManager:OnBeginPlay -- 치트 허용 사용자 목록 초기화
CheatManager:IsAllowedUser -- 사용자가 치트 사용 권한이 있는지 확인
CheatManager:UseCheat -- 치트 키를 파싱하여 해당 치트 기능 실행
CheatManager:Cheat_PhaseOver -- 현재 페이즈 강제 종료
CheatManager:Cheat_GoStage -- 지정된 스테이지-라운드로 이동
CheatManager:Cheat_ChangeLife -- 팀 체력(하트) 변경
CheatManager:Cheat_ChangeLevel -- 팀 레벨 변경
CheatManager:Cheat_GetCoin -- 지정된 양의 코인 획득
CheatManager:Cheat_GetCharacter -- 지정된 캐릭터 1성 획득
CheatManager:Cheat_GetCharacterBySynergy -- 시너지별 모든 캐릭터 1성 획득
CheatManager:Cheat_GetItem -- 지정된 아이템 획득
CheatManager:Cheat_GetRuneCard -- 지정된 룬 카드 획득
CheatManager:Cheat_OutGame_GetSyrup -- 일반 시럽 획득
CheatManager:Cheat_OutGame_GetRoyalSyrup -- 로얄 시럽 획득
CheatManager:Cheat_OutGame_GetEXP -- 경험치 획득 (레벨업 처리 포함)
CheatManager:Cheat_OutGame_ChangeLevel -- 플레이어 레벨 직접 변경
CheatManager:Cheat_OutGame_ChangeCoachOwnInfo -- 코치 소유 정보 변경 (개별/코스트별/전체)
CheatManager:Cheat_OutGame_SetAchievementProgress -- 업적 진행도 설정
CheatManager:Cheat_OutGame_GetCollection_Character -- 캐릭터 컬렉션 등급 설정
CheatManager:Cheat_OutGame_GetCollection_Synergy -- 시너지 컬렉션 등급 설정
CheatManager:Cheat_OutGame_GetTitle -- 타이틀 획득 (네임태그/키워드)
CheatManager:Cheat_OutGame_RemoveAllTitles -- 모든 타이틀 제거
CheatManager:Cheat_OutGame_OpenSingleModeLevel -- 싱글 모드 레벨 해금
CheatManager:Cheat_OutGame_OpenRankModeLevel -- 랭크 모드 레벨 해금
CheatManager:Cheat_OutGame_GetChallengeChance -- 챌린지 모드 도전 횟수 설정
CheatManager:PrintUnitStatusInfo -- 유닛의 현재 스테이터스 정보를 콘솔에 출력
CheatManager:OpenCharShopBoard -- 캐릭터 상점 보드 열기
CheatManager:RefreshCharShopBoard -- 캐릭터 상점 보드 UI 갱신
CheatManager:OpenCharShopBoard_Client -- 클라이언트에서 캐릭터 상점 보드 UI 활성화
CheatManager:InitCheatDictUI -- 치트 사전 UI 초기화 (캐릭터/아이템/룬카드)
CheatManager:HandleKeyDownEvent -- 키보드 단축키로 치트 기능 실행
CheatManager:HandleButtonClickEvent -- 아웃게임 치트 탭 활성화
CheatManager:HandleButtonClickEvent2 -- 인게임 치트 탭 활성화
CheatManager:HandleButtonClickEvent3 -- 캐릭터 치트 목록 표시
CheatManager:HandleButtonClickEvent4 -- 아이템 치트 목록 표시
CheatManager:HandleButtonClickEvent5 -- 룬카드 치트 목록 표시
CustomChatLogic:OnBeginPlay -- 채팅 시스템 초기화 및 브로드캐스트 타이머 설정
CustomChatLogic:RequestChat -- 채팅 메시지 요청 처리 및 큐에 추가
CustomChatLogic:OnGetMessage -- 서버에서 받은 채팅 데이터를 파싱하여 이벤트 발생
CustomChatLogic:ReplaceNonSpaceWithAsterisk -- 공백이 아닌 모든 문자를 별표로 치환 (검열용)
CustomChatLogic:AddSystemMessage -- 클라이언트에서 시스템 메시지 출력
CustomChatLogic:GetTypeByMessage -- 메시지 내용으로 채팅 타입 판별
CustomChatLogic:StartsWith -- 문자열이 특정 접두사로 시작하는지 확인
CustomChatLogic:SendMegaphone -- 전체 서버에 확성기 메시지 전송
CustomChatLogic:RequestReport -- 채팅 신고 요청 처리 및 신고 팝업 표시
CustomChatLogic:ShowReportPopup -- 신고 팝업 UI 표시
CustomChatLogic:ShowReportSuccessPopup -- 신고 성공 팝업 표시
CustomChatLogic:OnEndPlay -- 게임 종료 시 타이머 정리
CustomChatLogic:HandleUserEnterEvent -- 사용자 입장 시 캐시된 채팅 메시지 전송
CustomChatLogic:HandleOnGetChatMessage -- 다른 서버에서 온 채팅 메시지 처리
UICustomChat:OnBeginPlay -- 채팅 UI 초기화 및 이벤트 연결
UICustomChat:OnSumitMessage -- 채팅 메시지 제출 처리 및 명령어 파싱
UICustomChat:SetWhisper -- 귓속말 대상 설정
UICustomChat:Refresh -- 채팅 목록 UI 갱신
UICustomChat:ActivateInputField -- 채팅 입력 필드 활성화
UICustomChat:OnTextInputEndEdit -- 텍스트 입력 종료 처리
UICustomChat:OnActivateInputField -- 입력 필드 활성화 상태 설정
UICustomChat:HandleOnGetChatMessage -- 새로운 채팅 메시지 수신 처리
UICustomChat:HandleKeyUpEvent -- 키보드 입력 처리 (채팅 활성화)
UI_CustomChat_New:OnBeginPlay -- 새로운 채팅 UI 초기화 및 설정
UI_CustomChat_New:OnSumitMessage -- 채팅 메시지 제출 처리 및 명령어 파싱
UI_CustomChat_New:ActivateInputField -- 채팅 입력 필드 활성화/비활성화
UI_CustomChat_New:Refresh -- 채팅 메시지 목록 UI 갱신
UI_CustomChat_New:ChangeCurrentWatcingLineIndex -- 현재 보고 있는 채팅 라인 인덱스 변경 (스크롤)
UI_CustomChat_New:HandleOnGetChatMessage -- 새로운 채팅 메시지 수신 처리 및 UI 갱신
UI_CustomChat_New:HandleKeyDownEvent -- 키보드 입력 처리 (채팅 활성화/비활성화)
UI_CustomChat_New:HandleTextInputSubmitEvent -- 텍스트 입력 제출 처리
UI_CustomChat_New:HandleMouseScrollEvent -- 마우스 스크롤로 채팅 목록 스크롤
UI_CustomChat_New:HandleUITouchEnterEvent -- 터치 영역 진입 시 플래그 설정
UI_CustomChat_New:HandleUITouchExitEvent -- 터치 영역 벗어날 시 플래그 해제
UI_CustomChat_New:HandleUITouchBeginDragEvent -- 스크롤바 드래그 시작
UI_CustomChat_New:HandleUITouchDragEvent -- 스크롤바 드래그 중 처리
UI_CustomChat_New:HandleUITouchEndDragEvent -- 스크롤바 드래그 종료
UI_CustomChat_New:HandleButtonClickEvent -- 신고 버튼 클릭 처리
UI_CustomChat_NicknameButton:HandleButtonClickEvent -- 닉네임 버튼 클릭 시 신고 팝업 표시
CharacterSynergyLogic:OnBeginPlay -- 게임 시작 시 캐릭터 시너지 데이터 로드
CharacterSynergyLogic:LoadTable -- 캐릭터 시너지 데이터셋을 메모리에 캐싱
ExpTableLogic:OnBeginPlay -- 게임 시작 시 경험치 테이블 데이터 로드
ExpTableLogic:LoadTable -- 레벨별 필요 경험치 데이터를 메모리에 캐싱
ExpTableLogic:GetNeedExp -- 특정 레벨에 필요한 경험치량 반환
PlaySoundLogic:OnBeginPlay -- 게임 시작 시 사운드 테이블 로드
PlaySoundLogic:LoadTable -- 사운드 및 BGM 데이터를 메모리에 캐싱
PlaySoundLogic:PlaySound -- 사운드 타입에 따라 효과음 재생 (중첩 및 우선순위 처리)
PlaySoundLogic:StopSound -- 지정된 타입의 사운드 정지
PlaySoundLogic:PlayBGM_Ver2 -- 스테이지에 맞는 배경음악 재생 (페이드 효과 포함)
PlaySoundLogic:PlayTileSettingSound -- 유닛 배치 시 스테이지별 효과음 재생
PlaySoundLogic:FadeInFadeOut -- 배경음악 볼륨 페이드 인/아웃 처리
PlaySoundLogic:SetBgmVolume -- 배경음악 볼륨 설정
PlaySoundLogic:HandleSliderValueChangedEvent -- BGM 볼륨 슬라이더 값 변경 처리
PlaySoundLogic:HandleSliderValueChangedEvent2 -- SFX 볼륨 슬라이더 값 변경 처리
GameModeDataManager:OnBeginPlay -- 게임 시작 시 게임 모드 데이터 초기화
GameModeDataManager:Initialize -- 싱글모드와 랭크모드 데이터를 메모리에 캐싱
InGameInfoDataLogic:SaveInGameData -- 데이터를 저장하는 함수입니다.
InGameInfoDataLogic:LoadInGameData -- 데이터를 가져오는 함수입니다.
InGameInfoDataLogic:SaveInGameInfoData -- 기본적인 GameInfo를 저장하는 함수입니다.
InGameInfoDataLogic:LoadInGameInfoData -- 저장한 GameInfo를 불러와 적용하는 함수입니다.
InGameInfoDataLogic:SaveInGameTeamInfoData -- Team 데이터를 저장하는 함수입니다.
InGameInfoDataLogic:LoadInGameTeamInfoData -- Team 데이터를 불러오는 함수입니다.
InGameInfoDataLogic:SaveInGameRuneInfoData -- Rune 데이터를 저장하는 함수입니다.
InGameInfoDataLogic:LoadInGameRuneInfoData -- Rune 데이터를 불러오는 함수입니다.
InGameInfoDataLogic:SaveInGameUnitInfoData -- Unit 데이터를 저장하는 함수입니다.
InGameInfoDataLogic:LoadInGameUnitInfoData -- Unit 데이터를 저장하는 함수입니다.
InGameInfoDataLogic:SaveInGameTeamPropertyInfoData -- 인게임 기타 프로퍼티 데이터를 저장하는 함수입니다.
InGameInfoDataLogic:LoadInGameTeamPropertyInfoData -- 인게임 기타 프로퍼티 데이터를 불러오는 함수입니다.
InGameInfoDataLogic:SaveGameUnitBattleStatisticsData -- 유닛 통계를 저장하는 함수입니다.
InGameInfoDataLogic:LoadInGameUnitBattleStatisticsData -- 유닛 통계를 불러오는 함수입니다.
InGameInfoDataLogic:SaveGameTeamBattleStatisticsData -- 팀 내 통계를 저장하는 함수입니다.
InGameInfoDataLogic:LoadInGameTeamBattleStatisticsData -- 팀 내 통계를 불러오는 함수입니다.
InGameInfoDataLogic:SetSavedDataDB -- SetSavedData : 저장된 데이터가 있는지 확인할 수 있도록 체크하는 프로퍼티입니다.
InGameInfoDataLogic:GetSavedDataDB -- SetSavedData : 저장된 데이터가 있는지 확인할 수 있도록 체크하는 프로퍼티입니다.
InGameInfoDataLogic:LoadInGameInfoDataInLobby -- 로비에서 GameInfo 중 필요한 데이터 일부만 불러오는 함수입니다.
InGameInfoDataLogic:SaveGameEndData -- 게임이 끝났을 때, 데이터를 저장하는 함수입니다.
InGameInfoDataLogic:LoadEndInGameData -- 로드가 완료되면, 이어하기 데이터를 더 불러오지 않도록 합니다.
ModeDataLogic:OnBeginPlay -- 게임 시작 시 모드 데이터 초기화 및 시즌 정보 로드
ModeDataLogic:OnUpdate -- 300초+ 무작위 시간마다 분기 업데이트 여부를 검사합니다.
ModeDataLogic:CountUserToSeason -- 해당 시즌에, 접속한 인원 수를 기록합니다.
ModeDataLogic:GetModeClearCountData -- 클리어 카운트
ModeDataLogic:SaveRankModeScoreData -- 랭크 모드 점수를 측정하여 저장하는 함수입니다.
ModeDataLogic:LoadRankingData -- 랭킹 데이터를 불러오는 곳입니다.
ModeDataLogic:GetRankModeUserClearPercent -- 시즌 n차 기록 중에서 상위 몇 퍼센트인지 구합니다.
ModeDataLogic:GetSeasonData -- 시즌 데이터를 불러오는 함수입니다.
ModeDataLogic:SetSeasonData -- 시즌 데이터를 설정하는 곳입니다.
ModeDataLogic:GetRankTierString -- level에 해당하는 랭크모드의 티어를 string 형태로 반환합니다. (예: lv1 = 아이언, lv2 = 브론즈1, ...)
ModeDataLogic:GetVersionInfo -- UTC.DateTime을 기반으로 현재의 월드 버전(string), 시즌, 분기 번호를 가져옵니다.
ModeDataLogic:GetLeftTimeToNextOrdinal -- 다음 분기까지 남은 시간을 가져옵니다.
ModeDataLogic:SaveClearStageNumData -- 일정 순위권 밖의 유저는, 따로 순위를 측정하지 않고 현재 순위 구간을 보여줍니다 (상위 n%)
ModeDataLogic:SaveModeClearCountData -- 클리어한 타입, 레벨에 따라 데이터를 저장합니다.
ModeDataLogic:CheckFirstRank -- 랭크 첫 판인지 확인합니다.
ModeDataLogic:SetRankPenaltyAndRankScoreCriteriaData -- 패널티 및 랭크 점수 측정 기준 데이터 DB 저장하는 함수입니다.
PlayerDataComponent:OnBeginPlay -- 플레이어 데이터 컴포넌트 초기화 및 데이터 로드
PlayerDataComponent:AddSyrup -- 시럽 종류별로 지정된 양만큼 추가
PlayerDataComponent:AddEXP -- 경험치를 획득하는 함수. 레벨 업이 됐다면, 변동된 레벨 값을 return 합니다.
PlayerDataComponent:SubtractSyrup -- 시럽을 차감하고 성공/실패 여부 반환
PlayerDataComponent:AddBoxPurchaseCount -- 가챠 박스 구매 횟수를 누적하여 카운트
PlayerDataComponent:SetGameRecordProperty -- 최근 플레이한 게임 기록을 프로필 프로퍼티에 저장
PlayerDataComponent:SetFavoriteTable -- 즐겨찾기 테이블을 타입별로 설정
PlayerDataComponent:SetChallengeModeTryCount -- 챌린지 모드 남은 도전 횟수 설정
PlayerDataComponent:OnSyncProperty -- 프로퍼티 동기화 시 UI 갱신 처리
PlayerDataLogic:GetPlayerData -- 유저가 게임에 접속하면 필요한 데이터를 불러오기 위해 호출하는 함수입니다.
PlayerDataLogic:GetAchievementData -- 업적과 관련된 프로퍼티를 불러오는 함수입니다.
PlayerDataLogic:SetPlayerAchievementData -- PlayerAchievementData 프로퍼티를 저장하는 함수입니다.
PlayerDataLogic:SetPlayerAchievementCategoryData -- PlayerAchieveCategoryData 프로퍼티를 저장하는 함수입니다.
PlayerDataLogic:GetCoachesData -- 코치 관련 프로퍼티를 불러오는 함수입니다.
PlayerDataLogic:SetPlayerOwnedCoachesData -- PlayerOwnedCoachesID 프로퍼티를 저장하는 함수입니다.
PlayerDataLogic:SetPlayerCoachPresetsData -- SetCoachPresetInfo 프로퍼티를 저장하는 함수입니다.
PlayerDataLogic:SetPlayerFollowingCoachIDData -- FollowingCoachID 프로퍼티를 저장하는 함수입니다.
PlayerDataLogic:SetPlayerPickAdjustmentCountData -- PickAdjustmentCount 프로퍼티를 저장하는 함수입니다.
PlayerDataLogic:GetCollectionData -- Collection 관련 프로퍼티를 저장하는 함수입니다.
PlayerDataLogic:SetCharCollectionData -- CharacterCollection 프로퍼티를 저장하는 함수입니다.
PlayerDataLogic:SetSynergyCollectionData -- SynergyCollection 프로퍼티를 저장하는 함수입니다.
PlayerDataLogic:GetTitleData -- TitleManager의 프로퍼티를 불러오는 함수입니다
PlayerDataLogic:SetTitleData -- TitleManager의 프로퍼티를 저장하는 함수입니다
PlayerDataLogic:GetPlayerRecordData -- 플레이어 기록용 데이터를 불러옵니다.
PlayerDataLogic:GetPlayerSyrupsData -- 플레이어 아웃게임용 재화(시럽) 상태를 불러옵니다.
PlayerDataLogic:SetPlayerSyrupData -- 플레이어의 아웃 게임 재화 _ Syrup 을 저장합니다.
PlayerDataLogic:SetPlayerRoyalSyrupData -- 플레이어의 아웃 게임 재화 _ RoyalSyrup을 저장합니다.
PlayerDataLogic:SetPlayerRepechageData -- 플레이어의 아웃 게임 재화 _ Repechage를 저장합니다.
PlayerDataLogic:GetPlayerFavoriteDicData -- 사전 즐겨찾기 데이터를 불러옵니다.
PlayerDataLogic:GetPlayerFavoriteDicDataInClient -- 클라이언트에 즐겨찾기를 저장합니다.
PlayerDataLogic:SetPlayerFavoriteDicData -- 플레이어의 사전 내 즐겨찾기 정보를 저장합니다.
PlayerDataLogic:GetLastLoginDateData -- 플레이어가 가장 최근에 로그인한 일시를 불러옵니다.
PlayerDataLogic:SetLastLoginDateData -- 그 다음, 지금 접속한 날짜를 새로 저장합니다.
PlayerDataLogic:SetPlayerInfoData -- 플레이어의 기본 정보를 저장합니다.
PlayerDataLogic:GetPlayerNickNameData -- 플레이어의 닉네임을 불러옵니다.
PlayerDataLogic:GetPlayerCumulativeBoxPurchasesAmountData -- 플레이어의 가챠 구매 횟수를 불러옵니다.
PlayerDataLogic:SetPlayerCumulativeBoxPurchasesAmountData -- 플레이어의 가챠 구매 횟수를 저장합니다.
PlayerDataLogic:CheckPlayerHighRankData -- 플레이어가 가진 데이터를 확인한 후, 더 높다면 기록
PlayerDataLogic:GetPlayerLevelData -- 플레이어 계정 레벨 상태를 불러옵니다.
PlayerDataLogic:SetPlayerLevelData -- 플레이어 계정 레벨 상태를 저장합니다.
PlayerDataLogic:SetPlayerProfileIsPublicData -- 플레이어의 프로필 공개 여부를 저장합니다.
PlayerDataLogic:GetPlayerProfileIsPublicData -- 플레이어의 프로필 공개 여부를 불러옵니다.
PlayerDataLogic:SetPlayerTutorialData -- 플레이어의 튜토리얼 관련 정보를 저장합니다.
PlayerDataLogic:GetPlayerTutorialData -- 플레이어의 튜토리얼 관련 정보를 불러옵니다.
PlayerDataLogic:SetPlayerChallengeInfoData -- 플레이어의 챌린지 관련 정보를 저장합니다.
PlayerDataLogic:GetPlayerChallengeInfoData -- 플레이어의 챌린지 관련 정보를 불러옵니다.
PlayerDataLogic:SetPlayerDailyMissionData -- 플레이어의 일일 미션 관련 정보를 저장합니다.
PlayerDataLogic:GetPlayerDailyMissionData -- 플레이어의 일일 미션 관련 정보를 불러옵니다.
PlayerDataLogic:GetPlayerGachaCountData -- 플레이어 가챠 횟수를 불러옵니다.
PlayerDataLogic:SetPlayerGachaCountData -- 플레이어의 가챠 횟수를 저장합니다.
ArcaneRiverColleague:SetColleagueVisible -- 지정된 개수만큼 동료 엔터티를 보이게 설정하고 스폰 시작
ArcaneRiverColleague:SpawnColleague -- 동료들을 1초간 페이드인 효과와 함께 등장시키는 연출
ArcaneRiverColleague:VisibleOff -- 동료들을 사라지게 하고 이펙트 재생 후 엔터티 제거
ChangeLifeColorComponent:OnUpdate -- 플레이어 체력에 따라 하트 UI 색상을 변경하는 업데이트 로직 (현재 비활성화)
InfoTileComponent:HandleKeyDownEvent -- PC 플랫폼에서 마우스 클릭 시 타일 정보 UI를 숨기는 핸들러
LineEffectCompo:OnUpdate -- 다양한 캐릭터 스킬의 라인 이펙트를 렌더링하는 업데이트 로직
NowStageProfileComponent:OnBeginPlay -- 현재 스테이지 프로필 UI의 원래 위치를 저장
NumChange:Swaping -- 숫자 풀에서 순환하며 텍스트를 변경하는 애니메이션 시작
NumChange:StopTimer -- 숫자 변경 타이머를 중지하고 초기화
NumChange:StopNum -- 타이머를 중지하고 최종 숫자 값으로 텍스트 설정
OverTileComponent:SetTileEnable -- 타일 오버레이 표시 상태를 설정
RuneCardBuffComponent:ChangeUnitEffect -- 룬카드 버프 효과에 따른 파티클 이펙트 생성 및 재생
RuneCardBuffComponent:Init_ver2 -- 스탯 타입에 따른 버프 UI 초기화 및 설정
S10011TakePower:MoveToParent -- 시너지 효과로 파워를 흡수하는 연출 재생
ScrollComponent:SpawnScroll -- 1초동안 알파값 0.5로, 좌표 0.3이동
TileSetAlpha:Starttoalpha100 -- 점점 알파값이 100으로 감
TileSetAlpha:Starttoalpha0 -- 점점 알파값이 0으로 감
UnitShadowComponent:Init -- 캐릭터 ID와 레벨에 따른 유닛 그림자 초기화 설정
BackgroundChangeLogic:OnBeginPlay -- 배경 및 스테이지 아이콘 데이터를 초기화하고 캐싱
BackgroundChangeLogic:GotoNextNode -- 다음 스테이지로 이동하는 연출을 재생하고 배경을 설정
BackgroundChangeLogic:SetBg -- 스테이지 인덱스에 따라 배경 이미지를 변경
BackgroundChangeLogic:BGUIOff -- 배경 UI를 페이드아웃하고 전투 필드를 표시
BackgroundChangeLogic:Init -- 스테이지 UI 요소들을 초기 상태로 설정
BackgroundChangeLogic:SetNodeForce -- DB 데이터를 기반으로 이전 스테이지들을 클리어 상태로 표시
BackgroundChangeLogic:SetWinLoseUI -- 라운드 승패 표시
BackgroundChangeLogic:SetBestClearInfoUI -- 해당 게임의 가장 멀리 다다른 스테이지를 표시합니다.
BackgroundChangeLogic:SetStageIconTween -- 스테이지 아이콘의 트윈 애니메이션을 켜거나 끄는 함수
BackgroundChangeLogic:HandleKeyDownEvent -- 키보드 입력 이벤트 핸들러 (현재 비어있음)
BackgroundChangeLogic:HandleEntityMapChangedEvent -- 플레이어 맵 변경 시 UI 초기화 핸들러
CursorManager_check:OnBeginPlay -- 커스텀 커서 초기화 로직 (현재 비활성화)
CursorManager_check:OnUpdate -- 커스텀 커서 위치 업데이트 로직 (현재 비활성화)
GeneralDirectorLogic:OnBeginPlay -- 게임 시작 시 UI 및 데이터 초기화
GeneralDirectorLogic:ShowReadyPhaseUI -- 준비단계UI들 보여주기
GeneralDirectorLogic:ShowBattleUI -- 적팀 시너지리스트UI 생김
GeneralDirectorLogic:ResetReadyPhaseUI -- 버튼 취소 등 기타 이유로 초기화
GeneralDirectorLogic:ShowFreeCost -- 코스트가 0원일 때 코인 UI 처리
GeneralDirectorLogic:LockCharacterShopSlot -- 캐릭터 상점의 지정된 개수만큼 슬롯을 잠그거나 해제
GeneralDirectorLogic:SpawnRuneCard -- 룬카드 획득 시 변화 이펙트를 재생하는 함수
GeneralDirectorLogic:BattleBuffEffect -- 전투 중 스탯 버프를 받을 때 재생하는 연출
GeneralDirectorLogic:PlayBuff -- 순차 재생
GeneralDirectorLogic:UnitOnTileDirector -- 유닛이 스폰될 때, 드래그로 타일에 놓을 때 재생
GeneralDirectorLogic:InsertItemDirectorData -- 아이템 연출용 테이블에 데이터를 넣어둡니다.
GeneralDirectorLogic:StarttoPlayItemDirector -- 큐에 쌓인 아이템 연출들을 순차적으로 재생 시작
GeneralDirectorLogic:PlayItemDirector -- 아이템 획득 시, 연출.
GeneralDirectorLogic:PlayCoinDirector_Text -- 코인 획득 연출 : 텍스트 변경 연출입니다.
GeneralDirectorLogic:PlayCoinDirector_Sprite -- 코인 획득 연출 : 스프라이트 연출입니다.
GeneralDirectorLogic:SetTileDirection_Main -- 전장 타일 표시 관련 로직입니다. 시너지 제외 전장타일은 이 함수를 거쳐서 표시합니다.
GeneralDirectorLogic:BattleDebuffEffect -- 전투 중 유닛이 디버프를 받을 때 파티클 이펙트 생성
GeneralDirectorLogic:Init -- 게임 시작 시 UI 위치와 데이터를 초기화하는 함수
GeneralDirectorLogic:RemoveHectorEffect -- 헥터 캐릭터의 위협 이펙트를 제거하는 함수
GeneralDirectorLogic:ShowRedTile -- 레벨 초과로 배치된 유닛들에게 빨간 타일 표시
GeneralDirectorLogic:ShowBattleField -- 게임 시작 시 전장 타일들을 순차적으로 표시하는 연출 (현재 비활성화)
GeneralDirectorLogic:OffInventoryUI -- 준비 단계 종료 시 인벤토리 UI를 화면에서 숨기는 함수
GeneralDirectorLogic:OffShopUI -- 카운트에 맞춰 UI가 순차적으로 꺼집니다.
GeneralDirectorLogic:SetEffectAlpha -- 서버에서 알파값을 수정해야할 때 이 함수 호출
GeneralDirectorLogic:CheckLife -- 남은 하트 개수를 체크. 2개 이하라면 하트 UI가 붉은색으로 깜빡
GeneralDirectorLogic:MinusLifeCount -- 하트 감소 연출을 재생(리소스 정리 필요)
GeneralDirectorLogic:AddLifeCount -- 하트 증가 연출을 재생(리소스 정리 필요)
GeneralDirectorLogic:SetResultCoinTable -- 라운드 결과 화면 : 룬카드/코치 항목에 출력한 정보목록입니다.
GeneralDirectorLogic:ShowResultCoins -- 라운드 결과 화면에서 룬카드/코치 보상을 순차적으로 표시
GeneralDirectorLogic:ShowSynergyTile -- 유닛의 시너지 타일을 보여줍니다.
GeneralDirectorLogic:ShowSkillRangeInBattle -- 유닛 공격범위를 표시합니다.
GeneralDirectorLogic:GetTileDistance -- 두 타일 간의 거리를 계산하는 함수 (헥사곤 타일 기준)
GeneralDirectorLogic:OnOffTileVisible -- 타일 엔터티의 아웃라인을 표시합니다.
GeneralDirectorLogic:InsertRangeEntity -- 스킬 범위 표시용 타일 엔터티를 리스트에 추가
GeneralDirectorLogic:SetClientRedTile -- 유닛의 빨간 타일 표시 상태를 설정하는 함수
GeneralDirectorLogic:SetClientShadow -- 그림자 세팅
GeneralDirectorLogic:HandleEntityMapChangedEvent -- 플레이어 맵 변경 시 UI와 시너지 타일을 초기화하는 핸들러
RuneCardDirectEnum:OnBeginPlay -- 룬카드 스탯 관련 데이터 테이블 초기화
RuneCardDirectEnum:GetBuffDirectorType -- 스탯 타입 문자열을 버프 연출 타입 번호로 변환
RuneCardDirector:OnBeginPlay -- 룬카드 연출에 필요한 아이콘과 데이터를 초기화
RuneCardDirector:ShakingCard_Battle -- 전투 중 룬카드가 발동할 때 흔들림 연출을 재생
RuneCardDirector:ShakingCard_Ready -- 준비 단계에서 룬카드 발동 시 흔들림 연출을 재생
RuneCardDirector:IconToastDirector_Ready -- 준비 단계에서 룬카드 위에 효과 아이콘과 수치를 표시하는 토스트 UI 생성
RuneCardDirector:IconToastDirector_Battle -- 전투 중 룬카드 위에 다중 효과 아이콘과 수치를 표시하는 토스트 UI 생성
RuneCardDirector:GoldenMaterial -- 특정 룬카드에 황금 머티리얼 효과를 적용하는 함수
RuneCardDirector:InitDirector -- 룬카드에 적용된 연출 효과들을 초기화하는 함수
RuneCardDirector:RuneCardItemDirector_Ready -- 준비 단계에서 룬카드로 아이템 획득 시 연출을 재생하는 함수
RuneCardDirector:RC10010Director -- 비셔스 룬카드 효과 연출 (코인 획득 및 회색조 처리)
RuneCardDirector:Setgraysprite -- 룬카드의 스택 게이지를 0으로 초기화하는 함수
RuneCardDirector:RC30001Director -- 기억하는 자 룬카드 효과 연출 (유닛 이미지 변경 및 깜빡임)
RuneCardDirector:RC10022Director -- 대기석 타일의 사용 가능 여부를 설정하는 함수
RuneCardDirector:BattleResultDirector -- 전투 결과에 따라 발동하는 룬카드 효과들을 처리하는 함수
RuneCardDirector:CheckRuneCardManagingValue -- 특별한 관리가 필요한 룬카드들의 상태를 확인하고 연출을 적용
RuneCardDirector:SetFillAmount -- 룬카드의 스택 게이지를 채우는 연출을 재생하는 함수
RuneCardDirector:InitRuneCardManagingValue -- 특별 관리 룬카드들의 값을 초기화하는 함수
RuneCardDirector:GetRuneCardIndex -- 룬카드 엔터티로부터 인덱스를 찾는 함수
RuneCardDirector:RuneCardCoinDirector -- 룬카드에서 코인을 획득할 때 코인 스프라이트 연출을 재생
RuneCardDirector:ChangeInvenItem -- 인벤토리 아이템 변경 시 이펙트를 재생하는 함수
RuneCardDirector:DestroyRuneCard -- 룬카드 파괴 시 소각 또는 일반 파괴 연출을 재생
RuneCardDirector:RC20008Director -- 카르카사 룬카드의 시너지 아이콘 변경 연출
RuneCardDirector:ChangeShopCharacterValues -- 해나와 팬텀 룬카드 효과로 상점 캐릭터 구매 개수 변경 UI 표시
RuneCardDirector:RC20030Director -- 폭탄마 룬카드 파괴 시 폭발 연출과 사운드 재생
RuneCardDirector:ChangeUnifEffect -- 유닛 변화 효과를 재생하는 함수 (덴마 룬카드 효과)
RuneCardDirector:StrongerSynergyDirector -- 강화된 시너지 효과 표시를 위한 UI 연출 함수
RuneCardDirector:RC20014Director -- 해나 룬카드 효과로 선택된 슬롯 외 다른 슬롯의 숫자 표시 제거
RuneCardDirector:RC40003Director -- 팬텀 룬카드 효과로 룬카드들의 강조 표시를 제어하는 함수
RuneCardDirector:RC30004Director_New -- 타우로스피어 룬카드 효과로 대기석 타일 상태를 변경하는 함수
RuneCardDirector:RC40001Director -- 메르세데스 룬카드 효과로 유닛에게 엘비쉬 블레싱 이펙트 재생
RuneCardDirector:RC40002Director -- 아란 룬카드 효과로 화면 가장자리에 불꽃 UI를 표시하거나 숨김
RuneCardDirector:RC40004Director_1 -- 아델 룬카드 1단계 연출 (대기석 타일 순차 확인)
RuneCardDirector:RC40004Director_2 -- 아델 룬카드 2단계 연출 (보상 지급)
RuneCardDirector:RC40005SpawnDirector -- 제로 룬카드 효과로 유닛 스폰 시 사운드와 이펙트 재생
RuneCardDirector:StrongerSynergyDirector_Init -- 강화된 시너지 연출 효과를 초기화하는 함수
RuneCardDirector:RuneCardItemDirector_Battle -- 전투 중 룬카드로 아이템 획득 시 연출을 재생하는 함수
RuneCardDirector:RC20009Director -- 토푸 룬카드 효과로 하트 감소 방지 연출을 재생
RuneCardDirector:HandleUserLeaveEvent -- 유저 퇴장 시 룬카드 관리 값들을 초기화하는 핸들러
RuneCardDirector:HandleEntityMapChangedEvent -- 플레이어 맵 변경 시 룬카드 관리 값들을 초기화하는 핸들러
SampleClientSpawnLogic:SpawnUnitSample -- 유닛으로 사용할 엔티티 샘플을 미리 스폰해두는 함수입니다.
SampleClientSpawnLogic:SpawnUnitChildren -- 유닛에 필요한 자식 컴포넌트들을 생성하는 함수
ShadowTableLogic:OnBeginPlay -- 클라이언트에서 그림자 테이블 데이터를 로드
ShadowTableLogic:LoadTable -- 그림자 정보 테이블을 메모리에 캐싱하여 성능 최적화
ShadowTableLogic:GetShadowScaleType -- 캐릭터 ID에 따른 그림자 크기 타입을 반환
ShadowTableLogic:GetShadowPos -- 캐릭터 ID와 레벨에 따른 그림자 위치를 Vector3로 반환
SynergyBattleDirectorLogic:S10017SurviveEffect -- 살아난 유닛들 이펙트 표시
SynergyBattleDirectorLogic:S10019GetItem -- 루디브리엄 시너지 효과로 아이템 획득 시, 호출
SynergyBattleDirectorLogic:S10023Status -- 모험가 시너지 유닛 가져오기
SynergyBattleDirectorLogic:S10025Tree -- 기사단장 유닛이 버프받을 때 호출
SynergyBattleDirectorLogic:S10009RecoverHP -- 회복 이펙트
SynergyBattleDirectorLogic:S10008TargetShow -- 추격자 타겟 표시
SynergyBattleDirectorLogic:S10010TargetShow -- 타겟 표시
SynergyBattleDirectorLogic:S10016ColdAir -- 엘나스 냉기 중첩 표현
SynergyBattleDirectorLogic:S10016IceBomb -- 엘나스 냉기 터지기
SynergyBattleDirectorLogic:S10018Curse -- 요르문간드 저주 표시
SynergyBattleDirectorLogic:S10002Wave -- 수호대 방어막 파괴
SynergyBattleDirectorLogic:S10021OrbisStoneBuff -- 오르비스 버프 제공 표현
SynergyBattleDirectorLogic:S10003Bigger -- 선봉장 유닛이 일시적으로 커지면서 유닛들을 도발합니다.
SynergyBattleDirectorLogic:S10003Angry -- 분노표시
SynergyBattleDirectorLogic:S10011ChangePos -- 두 유닛이 서로 자리바꿀 때
SynergyBattleDirectorLogic:S10011TakePower -- 강탈 시, 재생
SynergyBattleDirectorLogic:S10032Status -- 마가티아 유닛 가져오기
SynergyReadyDirectorLogic:OnBeginPlay -- 클라이언트 시작 시 시너지 연출 관련 테이블 데이터를 로드
SynergyReadyDirectorLogic:LoadTable -- 시너지 연출에 필요한 모든 리소스와 데이터를 메모리에 캐싱하여 성능 최적화
SynergyReadyDirectorLogic:ReceiveFieldSynergyCount -- 필드 시너지 개수가 변경될 때 호출되어 해당 시너지의 연출을 재생
SynergyReadyDirectorLogic:BasicDirection -- 기본적인 시너지 연출을 재생 (사운드와 이펙트)
SynergyReadyDirectorLogic:S10001Direction -- 마스코트 시너지 연출을 처리하고 인기도 시스템을 관리
SynergyReadyDirectorLogic:S10001GetReward -- 마스코트 시너지에서 인기도 보상을 받을 때의 연출을 처리
SynergyReadyDirectorLogic:S10005Direction -- 시간의 신전 시너지 연출을 단계별로 처리
SynergyReadyDirectorLogic:S10011Direction -- 도적 시너지 연출을 처리하고 첫 활성화 시 안내 메시지를 표시
SynergyReadyDirectorLogic:S10015Direction -- 시간의 신전 시너지 연출을 처리하며 도도 엔터티 중심으로 이펙트를 재생
SynergyReadyDirectorLogic:S10016Direction -- 엘나스 시너지 연출로 전장을 얼음으로 덮고 눈보라 이펙트를 재생
SynergyReadyDirectorLogic:S10019Direction -- 루디브리엄 시너지 연출로 공장장 카호를 소환하고 관련 이펙트를 재생
SynergyReadyDirectorLogic:S10020Direction -- 아케인리버 시너지 연출로 각 유닛에 맞는 동료를 소환하고 이펙트를 적용
SynergyReadyDirectorLogic:S10021Direction -- 오르비스 시너지 연출로 사운드와 이펙트를 재생
SynergyReadyDirectorLogic:Set10021TilesEffect -- 오르비스 소환석의 영향을 받는 타일들의 시각적 효과를 관리
SynergyReadyDirectorLogic:S10023Direction -- 모험가 시너지 연출을 처리하고 시너지 단계에 따라 인형의 모습을 변경
SynergyReadyDirectorLogic:S10024Direction -- 전직교관 시너지 연출을 처리하며 교관 종류에 따라 다른 이펙트를 재생
SynergyReadyDirectorLogic:S10025Direction -- 기사단장 시너지 연출을 처리하고 성역 타일의 위치와 효과를 관리
SynergyReadyDirectorLogic:S10025TileBless -- 기사단장 시너지의 성역 타일에 축복 이펙트를 적용
SynergyReadyDirectorLogic:S10025TileBuff -- 기사단장 시너지의 성역 타일 위에 유닛이 있을 때 버프 이펙트를 재생
SynergyReadyDirectorLogic:GetOnFieldUnit -- 필드에 배치된 유닛들 중 특정 시너지 ID를 가진 유닛들을 필터링하여 반환
SynergyReadyDirectorLogic:GetSynergyStep -- 시너지 개수에 따른 시너지 단계를 계산하여 반환 (0이면 비활성화)
SynergyReadyDirectorLogic:PlayEffect -- 시너지 이펙트를 재생하며 부착 타입에 따라 맵, 시너지 유닛, 모든 유닛에 적용
SynergyReadyDirectorLogic:GetPos -- 이펙트 위치를 계산하며 pivot 기반 위치와 절대 위치를 지원
SynergyReadyDirectorLogic:Set10001MascotInfo -- 마스코트 시너지의 인기도에 따라 마스코트와 관중의 모습을 변경
SynergyReadyDirectorLogic:S10007ShadowSpawnEffect -- 그림자 시너지로 그림자 유닛이 소환될 때 소환 이펙트를 재생
SynergyReadyDirectorLogic:S10021SpawnStone -- 오르비스 소환석이 소환될 때 소환 이펙트를 재생
SynergyReadyDirectorLogic:InitOrbistile -- 오르비스 타일 효과를 초기화하고 모든 타일의 오르비스 효과를 비활성화
SynergyReadyDirectorLogic:S10031Direction -- 동화 시너지 연출을 처리하며 캐릭터별로 다른 동화책 이펙트를 재생
SynergyReadyDirectorLogic:PlayEffect_Solo -- 특정 유닛에게만 개별적으로 이펙트를 재생 (동화 시너지 전용)
SynergyReadyDirectorLogic:SetS10001StackText -- 마스코트 시너지의 인기도 수치를 UI 텍스트에 업데이트
Util:IsContainStringkey -- 딕셔너리에 특정 문자열 키가 존재하는지 확인
Util:Stringf -- 문자열 포맷팅 함수로 {1}, {2} 등의 플레이스홀더를 값으로 치환
Util:GenerateShuffle -- 배열의 키들을 무작위로 섞어서 반환
Util:IsContain -- 테이블에 특정 요소가 포함되어 있는지 확인
Util:GetDegreeByTan -- 벡터의 탄젠트 값을 이용해 각도를 도 단위로 계산
Util:GetDistance -- 두 점 사이의 유클리드 거리를 계산
Util:GetRadianByAtan -- 벡터의 탄젠트 값을 이용해 라디안 값을 계산
Util:DegToRad -- 도 단위를 라디안 단위로 변환
Util:RadToDeg -- 라디안 단위를 도 단위로 변환
Util:DeepCopy -- 테이블의 깊은 복사를 수행하여 중첩된 테이블까지 완전히 복제
Util:toBoolean -- 문자열을 불린 값으로 변환
Util:GenerateShuffleTable -- 지정된 범위의 숫자들로 구성된 무작위 순서의 테이블 생성
Util:LogTableItem -- 테이블의 모든 아이템을 순회하는 로그용 함수 (현재 비어있음)
Util:ArrShuffle -- 배열의 요소들을 무작위로 섞어서 새로운 배열 반환
Util:GetRemovedRangeTable -- 테이블에서 지정된 범위의 요소들을 제거한 새 테이블 반환 (현재 비활성화)
Util:MergeTable -- 두 테이블을 병합하여 새로운 테이블 반환
Util:TableToString -- 테이블의 모든 요소를 구분자로 연결하여 문자열로 변환
Util:SumTable -- 테이블의 모든 숫자 요소들의 합계 계산 (현재 비활성화)
Util:IntToString -- 숫자를 정수 문자열로 변환
Util:TableShuffle -- 테이블의 모든 요소를 재귀적으로 무작위 섞기 수행
Util:RemoveDuplicatedElements -- 테이블에서 중복된 요소들을 제거한 새 테이블 반환 (현재 비활성화)
Util:ConvertToOneDimentionaryTable -- 다차원 테이블을 1차원 테이블로 변환
Util:IsContainType -- 테이블에 특정 타입의 요소가 포함되어 있는지 확인
Util:SortByKey -- 테이블을 키 기준으로 오름차순 또는 내림차순 정렬
Util:GetRandElement -- 테이블에서 무작위로 하나의 요소를 선택하여 반환
Util:GetRandElementByRate -- 확률 가중치에 따라 테이블에서 무작위 요소 선택
Util:GetMaxValue -- 테이블에서 가장 큰 값을 찾아 반환
Util:GetKeySameValue -- 특정 값과 같은 값을 가진 첫 번째 키를 반환
Util:ChageElementsType -- 테이블의 모든 요소를 지정된 타입으로 변환
Util:IsElementsSame -- 두 테이블의 모든 요소가 같은지 비교
Util:GetTableRemoveElements -- 기본 테이블에서 타겟 요소들을 제거한 새 테이블 반환
Util:AddElement -- 테이블에 특정 요소를 지정된 개수만큼 추가
Util:GetRandVec3 -- 지정된 범위 내에서 무작위 3D 벡터 생성
Util:GetRandVec2 -- 지정된 범위 내에서 무작위 2D 벡터 생성
Util:Clamp -- 값을 지정된 최소값과 최대값 사이로 제한
Util:GetStringMultiLine -- 긴 문자열을 지정된 길이로 나누어 여러 줄로 변환
Util:GetTextLineCount -- 텍스트의 줄 수를 계산 (현재 비활성화)
Util:GetImageRectSizeByResourceSizeRate -- 이미지 리소스의 비율에 따라 사각형 크기 조정 (현재 비활성화)
Util:MultiTableToString -- 다차원 테이블을 타입 정보가 포함된 문자열로 변환
Util:StringToMultiTable -- 문자열을 다차원 테이블로 변환 (현재 비활성화)
Util:Round -- 지정된 소수점 자리에서 반올림 수행
Util:IsSameValueVector2 -- 두 Vector2의 값이 같은지 비교
Util:GetNegativeOrPositive -- 숫자의 부호를 판별하여 1, -1, 0 중 하나를 반환
Util:IsPassedTargetPos -- 현재 위치가 방향에 따라 목표 위치를 지나쳤는지 확인
Util:QuickSort -- 비교 함수를 사용한 퀵 정렬 수행
Util:QuickSortWith -- 두 배열을 동시에 정렬하는 퀵 정렬 (첫 번째 배열 기준)
Util:MergeTableByKey -- 키 기준으로 두 테이블을 병합하며 중복 키 처리 옵션 제공
Util:GetTableRange -- 테이블에서 지정된 인덱스 범위의 요소들만 추출
Util:GetPositionWithDistance -- 원점에서 지정된 거리와 회전각도로 새로운 위치 계산
Util:NumberToPercent -- 소수를 백분율 정수로 변환
Util:PercentToNumber -- 백분율 정수를 소수로 변환
Util:GetCreateTimeElapsedETCFromMapCode -- 맵 코드에서 생성 시간 정보를 Base62 디코딩으로 추출
Util:DecimalToBase62 -- 10진수를 Base62 문자열로 변환
Util:Base62ToDecimal -- Base62 문자열을 10진수로 변환
Util:OnBeginPlay -- 유틸리티 로직 초기화 시 랜덤 시드 설정 및 Base62 테이블 초기화
Util:UTCTimeToHourValue -- UTC 경과 시간을 시간 단위로 변환
Util:TableLen -- 테이블의 요소 개수를 계산
Util:ClampInteger -- 정수 값을 지정된 최소값과 최대값 사이로 제한
Util:InitializeBase62Table -- Base62 인코딩/디코딩용 문자 테이블 초기화
Util:Lerp -- 두 수 사이의 선형 보간 수행
Util:ILerp -- 선형 보간의 역함수로 t 값을 계산
Util:IsDev -- 개발자 계정인지 확인 (특정 PPSN으로 판별)
Util:MaxInteger -- 두 정수 중 큰 값을 반환
Util:MinInteger -- 두 정수 중 작은 값을 반환
Util:Vector2ToString -- Vector2를 문자열로 변환 (x,y 형태)
Util:StringToVector2 -- 문자열을 Vector2로 변환 (x,y 형태 파싱)
Util:Utf8StringListToList -- UTF-8 문자열을 유니코드 코드 포인트 리스트로 변환
Util:ListToUtf8StringList -- 유니코드 코드 포인트 리스트를 UTF-8 문자열로 변환
Util:ConvertIntegerToUTF8 -- 정수를 UTF-8 유효 범위로 변환 (서러게이트 쌍 영역 회피)
Util:ConvertUTF8ToInteger -- UTF-8 값을 원래 정수로 역변환
Util:IsEmptyTable -- 테이블이 비어있는지 확인
Util:Vector3ToString -- Vector3를 문자열로 변환 (x,y,z 형태)
Util:StringToVector3 -- 문자열을 Vector3로 변환 (x,y,z 형태 파싱)
Util:UTCtoLocalTime -- UTC 시간을 로컬 시간 문자열로 변환
Util:UIPostoScreenPos -- UI 좌표를 화면 좌표로 변환
Util:ScreenPostoUIPos -- 화면 좌표를 UI 좌표로 변환
AStarAlgorithm:Algorithm -- A* 알고리즘을 사용하여 시작점에서 목표점까지의 최적 경로를 계산
AStarAlgorithm:OnBeginPlay -- 컴포넌트 시작 시 A* 알고리즘 테스트 실행
CustomCameraComponent:OnBeginPlay -- 맵별로 적절한 UI를 활성화하고 카메라를 전환하는 초기화 작업
PersonalRoomStatus:OnBeginPlay -- 개인 방의 헥사 타일들을 초기화하고 좌표별로 매핑
PersonalRoomStatus:GetUserID -- 사용자 ID를 설정하여 개인 방 소유자를 식별
PersonalRoomStatus:CharLocationSet -- 캐릭터의 위치를 설정하고 타일 배치 정보를 업데이트
TileComponent:TileSet -- 타일의 속성들을 설정하여 게임 내 위치와 타입을 정의
TileComponent:TouchReleaseCheck -- 터치 해제 시 유닛이나 아이템 배치 가능 여부를 확인하고 처리
TileComponent:HandleTouchReleaseEvent -- 클라이언트에서 터치 해제 이벤트를 받아 서버로 전달하는 핸들러
TileComponent_New:TileSet -- 새로운 타일 시스템에서 타일의 영역과 타입, 좌표를 설정
BattleStatItemHoverInfo:HandleUITouchEnterEvent -- 마우스가 아이템 위에 올라갔을 때 아이템 정보 툴팁을 표시
BattleStatItemHoverInfo:HandleUITouchExitEvent -- 마우스가 아이템에서 벗어났을 때 아이템 정보 툴팁을 숨김
DropDownBoxCloser:HandleUITouchExitEvent -- 마우스가 드롭다운 박스 영역을 벗어나면 드롭다운을 닫음
DropDownMain:Initialize -- 현재 stage round 정보에 따라 라운드 선택 슬롯을 활성화 (이전의 모든 스테이지-라운드)
DropDownMain:Close -- -- 창을 닫을 시 슬롯을 제거한다
DropDownMain:HandleUITouchDownEvent -- 드랍다운 버튼을 누르면 박스 목록을 열거나 닫습니다.
DropDownMain:HandleTabChangedEvent -- 드롭다운에서 특정 라운드 탭을 선택했을 때 해당 라운드의 전투 통계로 전환
DropDownSlot:HandleUITouchDownEvent -- 드롭다운 슬롯을 클릭했을 때 해당 라운드의 전투 통계 데이터로 전환 (현재 미사용)
StatCloseBtn:HandleButtonClickEvent -- 전투 통계 창 닫기 버튼을 클릭했을 때 통계 창과 관련 UI를 모두 비활성화
StatCoachHoverInfo:HandleUITouchEnterEvent -- 마우스가 코치 아이콘 위에 올라갔을 때 코치 정보 툴팁을 표시
StatCoachHoverInfo:HandleUITouchExitEvent -- 마우스가 코치 아이콘에서 벗어났을 때 코치 정보 툴팁을 숨김
StatRuneCard:HandleUITouchEnterEvent -- 마우스가 룬 카드 위에 올라갔을 때 룬 카드 정보 툴팁을 표시
StatRuneCard:HandleUITouchExitEvent -- 마우스가 룬 카드에서 벗어났을 때 룬 카드 정보 툴팁을 숨김
UI_BattleStatistics:StatValueFormatter -- 받은 수치를 해당 스탯에 적절한 포멧의 스트링으로 변환하여 반환. 치명타률 등의 소수점 표기 처리를 위한 것.
UI_BattleStatistics:Initialize -- 창 오픈 시, UnitBattleStatistics의 데이터를 본 로직의 테이블에 넣고 유닛 슬롯, 그래프를 생성하는 함수
UI_BattleStatistics:ClearGameProperties -- 게임 종료 시 전투 통계 관련 프로퍼티들을 초기화
UI_BattleStatistics:ChangeTab_1stCategory -- 1차 카테고리 탭을 변경하고 해당 탭에 맞는 2차 카테고리 메뉴를 설정 (누적/최대값)
UI_BattleStatistics:ChangeTab_2ndCategory -- 2차 카테고리 탭을 변경하고 해당 통계 데이터로 그래프와 순위를 새로고침
UI_BattleStatistics:RefreshUI_GraphList -- UnitCombatStats를 선택한 탭에 따라 내림차순으로 정렬한다
UI_BattleStatistics:DrawGraphs -- 생성되어 있는 그래프의 크기를 수치에 맞게 바꾼다
UI_BattleStatistics:BattleStatRuneCardSetter -- 해당 라운드에 유저가 보유한 룬카드를 표시
UI_BattleStatistics:RefreshUI_RoundInfo -- 라운드가 변경될 때 갱신되는 정보들을 UI에 반영합니다.
UI_BattleStatistics:GetData -- UnitBattleStatistics의 데이터 중 stage round 조건에 맞는 데이터를 본 로직의 테이블로 로딩
UI_BattleStatistics:SetManagerName -- 플레이어와 상대 감독 이름을 세팅
UI_BattleStatistics:RoundSynergySetter -- 유닛과 룬의 정보를 바탕으로 해당 라운드에 유저가 보유한 시너지 정보를 정리
UI_BattleStatistics:HandleButtonClickEvent -- '누적' 탭 버튼을 누른 경우
UI_BattleStatistics:HandleButtonClickEvent2 -- '최대' 탭 버튼을 누른 경우
UI_BattleStatistics:HandleButtonClickEvent4 -- 최후의 결과 화면에서 전투 통계를 여는 경우, '최후의 결과 화면'을 끕니다.
UI_BattleStatistics:HandleButtonClickEvent5 -- 전투 통계 창 닫기 버튼 클릭 시 게임 결과 화면에서 열었다면 결과 화면을 다시 표시
UI_BattleStatistics_GraphTooltipActivator:HandleUITouchEnterEvent -- 마우스가 그래프 영역에 진입했을 때 해당 캐릭터의 세부 통계 정보를 툴팁으로 표시
UI_BattleStatistics_GraphTooltipActivator:HandleUITouchExitEvent -- 마우스가 그래프 영역에서 벗어났을 때 툴팁을 숨김
UI_BattleStatistics_UnitTooltipActivator:HandleUITouchEnterEvent -- 마우스가 유닛 초상화 위에 올라갔을 때 유닛 정보 툴팁을 표시
UI_BattleStatistics_UnitTooltipActivator:HandleUITouchExitEvent -- 마우스가 유닛 초상화에서 벗어났을 때 유닛 정보 툴팁을 숨김
UI_Tooltip_BattleStatisticsGraph:OnUpdate -- 마우스 위치를 따라다니는 툴팁의 위치를 업데이트하고 화면 경계를 벗어나지 않도록 조정
ChallengeManager:InitNewGameChallengeSet -- 인게임 시작 전, 챌린지 컴포넌트를 불러옵니다.
ChallengeManager:SetChallenge -- 챌린지 번호를 받아 해당 챌린지 ID를 설정하거나 초기화
ChallengeManager:OnSyncProperty -- 서버에서 동기화된 프로퍼티 변경을 클라이언트에서 처리
CoachIngameComponent:CoachSleepTimer -- 100초동안 코치와 아무 상호작용이 없다면 SleepRUID를 보여줍니다. 단, 준비단계에서만 보이는 연출입니다.
CoachIngameComponent:Interaction -- 코치와의 상호작용을 처리하여 랜덤 애니메이션을 재생
CoachIngameComponent:CheckRUID -- 현재 RUID와 비교하여 슬립 타이머를 재설정
CoachIngameComponent:PlayRollAction -- 코치가 회전하며 점프하는 특별한 액션을 재생
CoachIngameComponent:BattleResultCoachReaction -- 전투 결과에 따라 코치의 반응을 설정
CoachIngameComponent:TalkAnim -- 코치의 대화 애니메이션을 켜거나 끄는 함수
CoachIngameComponent:PlayCoachAbilityEffect -- 코치 능력 발동 시 이팩트와 애니메이션을 재생
CoachIngameComponent:HandleTouchEvent -- 코치 터치 이벤트를 처리하여 상호작용 실행
CoachManager:SetCoachID -- 세팅 화면에 쓰이는 함수로 코치를 입력한 type에 맞게 세팅합니다.
CoachManager:SetCoachRUID -- 코치의 RUID를 타입에 맞게 변경합니다.
CoachManager:SetCoachPreset -- 프리셋 넘버에 맞는 코치 프리셋을 변경합니다.
CoachManager:InitNewGameCoachSet -- 인게임 시작 전, 장착된 코치의 컴포넌트를 불러옵니다.
CoachManager:ModifyPlayerOwnedCoachesID -- func: 코치 보유 정보를 수정하는 함수
CoachManager:OnSyncProperty -- 서버에서 동기화된 코치 데이터를 클라이언트 UI에 반영하는 함수
CoachManager:GetOwnedCoachList -- cost에 해당하는 보유한 코치 아이디 목록을 반환합니다.
CoachManager:setCoachEntityOwner -- 동행 코치 엔티티를 서버에서 설정하고 클라이언트에 동기화하는 함수
CoachManager:setCoachEntityOwner_Client -- 클라이언트에서 동행 코치 엔티티를 설정하는 함수
CoachManager:GetHasType -- 지정된 코치의 보유 상태를 반환하는 함수 (0:미보유, 1:보유, 2:마스터코치)
CoachManager:GetAllOwnedCoachCount -- 플레이어가 보유한 전체 코치 수를 반환하는 함수
CoachManager:setCoachMasterEffect -- 마스터 코치 이팩트 설정을 제어하는 함수 (현재 비활성화)
CoachManager:SetBattleResultRUID -- 배틀 결과에 따라 코치의 반응 애니메이션을 설정하는 함수
CoachManager:OnMapEnter -- 맵 입장 시 동행 코치 상태를 초기화하는 함수
ESCMenuService:ResetSetting -- 설정한 내용을 초기화합니다.
ESCMenuService:OpenESCMenu -- ESC 메뉴를 열 때 연출을 재생하는 함수
ShortCutKeyService:ActivateChangingKeyMode -- 단축키 변경 모드를 실행하거나 종료하는 함수입니다.
ShortCutKeyService:ChangeKey -- 중복된 키가 있는지 검사합니다.
ShortCutKeyService:DeleteKey -- 지정한 단축키를 해제하는 함수입니다.
ShortCutKeyService:HandleKeyDownEvent -- Arena 맵에서의 이벤트 핸들러
ShortCutKeyService:HandleKeyDownEvent2 -- Lobby 맵에서의 이벤트 핸들러
ItemCombineService:LoadData -- 테이블 ItemCombine의 데이터를 미리 저장해둡니다.
ItemCombineService:GetNormalItemIDByMaterialItemIDs -- 아이디가 itemId1, itemId2인 아이템들을 조합해서 생기는 결과(완성) 아이템 아이디를 찾아서 반환합니다.
ItemCombineService:GetMateiralIDinUnitEquippedItems -- 유닛에게 장착된 아이템 중 재료아이템이 있는지 찾아서 반환합니다
ItemCombineService:GetMaterialItemIDsByNormalItemID -- ID가 normalItemID인 아이템을 만들기 위한 재료 아이템 리스트를 반환합니다.
ItemCombineService:ShowCombineTableTooltip -- 상점, 보관함에서 우클릭했을 때 조합표 툴팁을 보여주는 함수
ItemStatusLogic:GetItemStatusCalculatingType -- -@type table<string, string>
CharacterShopManager_New:Initiate -- 기물 수 리셋 / 초기 목록 갱신 / 프로퍼티 초기화
CharacterShopManager_New:ChooseRandomCharacterFromSameCost -- 구매비용이 targetCost인 캐릭터 중 무작위 하나를 선택합니다.
CharacterShopManager_New:ChooseRandomCharacterFromSameCostNSynergy -- 구매비용이 targetCost인 캐릭터 중, 타겟 캐릭터와 시너지를 공유하는 캐릭터를 선택합니다.
CharacterShopManager_New:CreateCharacterPoolFromSameSynergy -- 타겟 캐릭터와 시너지를 공유하는 캐릭터 풀을 만듭니다.
CharacterShopManager_New:ChooseRandomCharacterFromTable -- 구매비용이 targetCost인 캐릭터 중 무작위 하나를 캐릭터 풀에서 선택합니다.
CharacterShopManager_New:Reroll -- 상점을 새로고침하는 함수입니다.
CharacterShopManager_New:Reroll_Setting -- 정해진 캐릭터와 비용을 상점에 세팅하는 함수입니다.
CharacterShopManager_New:Reroll_Special -- 초대장(사기 주사위)의 효과로 같은 시너지만 나오도록 상점을 새로고침하는 함수입니다.
CharacterShopManager_New:BuyCharacter -- 구매 처리 시도 (대기석 등 조건에 따라 구매 가능 여부를 체크합니다.)
CharacterShopManager_New:Lock -- 함수 호출자 검증
CharacterShopManager_New:UI_RefreshShopList -- 상점UI 내 상품 목록을 새로고침합니다.
CharacterShopManager_New:UI_RefreshChanceList -- 상점 내 '코스트 별 등장 확률 표기'를 변경합니다.
CharacterShopManager_New:UI_RefreshUIByOwnGoldsCondition -- 골드 보유 조건에 따라 새로고침 및 경험치 구매 버튼을 흑백으로 만듭니다.
CharacterShopManager_New:UI_RefreshLockButtonUI -- 잠금 상태에 따라 버튼, 툴팁을 수정합니다.
CharacterShopManager_New:Reroll_Select -- 캐릭터ID를 직접 지정하여 상점에 나타나게 하는 함수입니다.
GameManager:GoToNextPhase -- 다음 페이즈로 넘기는 함수입니다.
GameManager:Ready -- 준비 단계 시작 시 수행되어야 하는 함수들을 실행합니다.
GameManager:InitUI_BattleTeamInfo -- 전투UI 중 '팀 정보' UI를 처음 세팅합니다.
GameManager:Clean_OnClient -- 연장전 UI를 끕니다.
GameManager:SetGameOver -- 아직 패자 부활권을 사용할 기회가 남았다면
GameManager:SetUI_BattleOver -- 매 전투 종료 시마다 획득한 보상을 확인하는 팝업을 발생시킵니다.
GameManager:ClearGameInfo -- 로비로 퇴장할 때 진행한 게임 정보를 모두 삭제하는 함수
GameManager:MoveToLobby_OnClient -- 로비로 이동할 때 로딩창을 활성화합니다.
GameManager:RestartArena -- 1-1부터 다시 시작하는 함수입니다.
GameManager:UseRepechage -- 패자부활권을 사용했을 때 호출하는 함수입니다.
GameManager:GiveUpRepechage -- 패자부활권 사용을 포기했을 때 호출하는 함수입니다.
LoadResourcesInfo:ResourceLoad -- 빠른 리소스로드속도를 위해 미리 다운받습니다.
LoadResourcesInfo:GetUILocalPositionScale -- UI에서 리소스를 적절하게 맞추고 싶을 때 사용하세요
LoadResourcesInfo:GetColliderOffsetScale -- TriggerComponent, physicsColliderComponent같이 충돌범위 offset, scale을 지정할 때 사용합니다
MatchManager:OnBeginPlay -- 8x8 행렬을 사용합니다.
MatchManager:SetCurrentRoundMatchInfo -- 플레이어 전투 라운드(N-1 ~ N-3)일 때, 매칭 정보를 생성합니다.
MatchManager:SetCurrentRoundMatchInfo2 -- 플레이어 전투 라운드(N-1 ~ N-3)일 때, 매칭 정보를 생성합니다.
MatchManager:SetNextMatchInfoUI_OnServer -- 다음 매칭 가능한 후보를 추리고, 클라이언트로 해당 정보를 보내는 함수입니다.
MatchManager:GetRandomCloneOpponentUserID -- (userID를 가진) 유저가 클론을 상대해야 하는 경우, 무작위 클론 대상 ID를 지정해 반환합니다.
SpecialShopManager:PurchaseItem_Check -- 아이템 상점에서 구매 버튼을 눌렀을 때 호출하는 함수입니다.
SpecialShopManager:GetRuneCard_Check -- 룬 카드를 획득하는 효과에 의해 얻어질 때 실행합니다.
SpecialShopManager:RemoveRuneCard -- 룬카드가 파괴 될 때 호출합니다.
SpecialShopManager:RemoveRuneCard_Check -- 룬카드가 파괴 될 때 호출합니다.
SpecialShopManager:PurchaseRunecard_Check -- 룬 카드 상점에서 구매 버튼을 눌렀을 때 호출하는 함수입니다.
SpecialShopManager:ResellRuneCard_Check -- 룬 카드 인벤토리에서 카드를 sellZone으로 drag&drop 했을 때 호출합니다.
SpecialShopManager:CheckReroll_Runes -- 함수 호출자 검증
SpecialShopManager:RerollList_RunesSpecial -- 튜토리얼 진행을 위해, 룬카드 상점에 지정한 룬카드가 나오게 하는 함수입니다.
SynergyManager_New:InitAllStacks -- 모든 시너지 관련 스택값을 0 으로 지정합니다.
SynergyManager_New:OnGameStart -- 게임을 최초 시작할 때 한 번 호출합니다. (불러오기 시에는 호출하지 않음)
SynergyManager_New:OnMergeUnit -- 유닛이 머지될 때 호출합니다.
SynergyManager_New:OnActivatedSynergyCountChanged -- 전장에 활성화된 시너지 숫자가 변경될 때마다 호출합니다.
SynergyManager_New:OnReadyPhase -- 준비 단계 시작 시 실행
SynergyManager_New:OnFieldUnitCountChanged -- 전장 내 배치된 유닛 수가 변경되었을 때 호출합니다.
SynergyManager_New:OnBattleStart -- 전투가 시작할 때 호출합니다.
SynergyManager_New:OnSkillUsedByAllies -- 아군이 스킬을 사용했을 때
SynergyManager_New:RefreshUnitStatus_AllOwnUnits -- 아군 전체의 스탯을 refresh 합니다.
SynergyManager_New:S10001_GetStack -- 마스코트 캐릭터가 플레이어 전투에 참여하면 인기도를 얻습니다.
SynergyManager_New:S10001_GiveReward_Check -- 보상 받기 버튼을 눌렀을 때, 누적된 인기도에 따라보상을 받습니다.
SynergyManager_New:S10001_GiveReward -- 보상 받기 버튼을 눌렀을 때, 누적된 인기도에 따라보상을 받습니다.
SynergyManager_New:S10004_UseSkill -- 마법사가 스킬을 사용할 때마다 아군 마법사들이 추가 마력을 얻습니다.
SynergyManager_New:S10004_Default -- 마법사 : 아군의 마력이 증가
SynergyManager_New:S10008_Stat -- 추격자 : 이동 속도가 100% 증가합니다.
SynergyManager_New:S10009_Default -- 싸움꾼 : 모든 아군이 체력 획득
SynergyManager_New:S10011_WithdrawItem -- '방해꾼의 가면'을 장착한 유닛을 대기석에 놓았을 때, 해당 아이템을 회수합니다.
SynergyManager_New:S10012_GetInvincible -- 숭고한 영혼 (미하일 고유 시너지) :
SynergyManager_New:S10014_Kill -- 여제 (시그너스 고유 시너지) : 아군이 적 유닛을 처치할 때마다 모든 아군의 상태 이상을 해제하고 공격속도를 4% 증가시킵니다.
SynergyManager_New:S10015_ApplySumOfStarLevel -- SettingPhase에 도도의 스탯을 설정합니다. (팀원들의 별 레벨 합에 따라)
SynergyManager_New:S10015_SpawnUnitBattlePhase -- BattlePhase 에 도도의 스탯을 설정하고 소환하는 함수입니다.
SynergyManager_New:S10018_Curse -- 슬리피우드 : 모든 적에게 저주를 내려 3초마다 최대 체력에 비례한 고정 피해를 입힙니다.
SynergyManager_New:S10018_RecoverHP -- 슬리피우드 : 적이 처치될 때마다 슬리피우드 캐릭터들이 체력을 회복합니다.
SynergyManager_New:S10019_OnBattleStart -- 루디브리엄 : 전투 시작 시, 아군이 장착한 아이템 수에 비례하여 루디브리엄 캐릭터들이 최대 체력 및 마력을 얻습니다.
SynergyManager_New:S10021_OnKilled -- 방해꾼 (7) 적 처치시, (방해꾼의 가면을 장착한 아군 유닛이) 2초간 은신
SynergyManager_New:S10022_GainMP -- 시그너스(11) : 아군 유닛이 처치되면 생존한 모든 아군 유닛이 MP 30 회복
SynergyManager_New:S10023_GetCoin -- 모험가 : 9 시너지, 적 처치 시 50% 확률로 1코인을 획득합니다.
SynergyManager_New:S10023_StatSet -- 모험가 : 팀 레벨에 비례해 스탯이 오릅니다.
SynergyManager_New:S10024_BattleStart -- 전직교관 중 하인즈(시작 MP 증가) or 헬레나(전투 시작 후 x초간 저지 불가)
SynergyManager_New:S10025_SetSaintArea -- 기사단장 : 성역 위치 무작위 지정 - "y00x" 형태로 지정 (예:3행 5열인 경우 3005)
SynergyManager_New:S10025_SetSainAreaTarget -- 기사단장 버프를 받을 타겟을 지정합니다.
SynergyManager_New:S10026_Spawn -- [예티와 페페] (2) : 전투 시작 시, '예티'와 '페페' 유닛들이 힘을 합칩니다. 예티와 페페를 소환합니다.
SynergyManager_New:S10027_Dead -- 발록 : 아군이 처치될 때마다 발록 유닛들이 추가 최대 체력을 얻고 거대해집니다.
SynergyManager_New:S10032_Default -- 마가티아 유닛 별 합계에 따라 아군 유닛의 능력치가 증가합니다.
SynergyManager_New:S10034_Default -- 처형자 : 추가 크리티컬 확률 및 크리티컬 피해량 획득
SynergyManager_New:S10037_Dead -- 분노 : 아군이 둘 이상 죽으면 도깨비가 분노합니다. 전투가 끝날 때까지 저지 불가 상태에 돌입하며, 이동 속도와 공격 속도가 증가합니다.
SynergyManager_New:S10031_SetItemOrder -- 아랫마을
SynergyManager_New:S10031_GetItem -- 아랫마을
SynergyManager_New:S10038_Blessing -- 여우신의 가호
SynergyManager_New:S10032_GetItem -- 마가티아 "알카드노" 전투 시작 후, 그리고 8초마다 살아있는 랜덤한 아군 유닛에게 알맞은 완성 아이템을 장착합니다.
SynergyManager_New:S10031_BattleStart -- 아랫마을 룬카드 효과
SynergyManager_New:S10036_BattleStart -- 판타스틱 테마파크 : 퍼레이드가 열렸습니다! 일정한 간격으로 다양한 효과를 받습니다. 퍼레이드의 효과는 아군 판타스틱 테마파크 유닛의 레벨당 10%씩 더 강해집니다.
TeamBattleStatistics:RoundPropertyInitialize -- 전투 시작 시, 각 프로퍼티에 초기값 기록
TeamBattleStatistics:RoundPropertyInitializeToClient -- 전투 시작 시, 각 프로퍼티에 초기값 기록
TeamBattleStatistics:SetProperty -- 프로퍼티에 기록
TeamBattleStatistics:SetPropertyToClient -- 프로퍼티에 기록
TeamBattleStatistics:SetPropertyWithKey -- 프로퍼티에 기록
TeamBattleStatistics:SetPropertyToClientWithKey -- 프로퍼티에 기록
TeamBattleStatistics:SetCoachesProperty -- 게임 시작 시, 코치 리스트 기록
TeamBattleStatistics:SetCoachesPropertyToClient -- 게임 시작 시, 코치 리스트 기록
TeamManager:UnitInfo_ToString -- UnitID / 별등급 / 장착한 아이템 3종의 id (없으면 0) / 영구증가 버프 / 배치 정보
TeamManager:InitNewGame -- 게임 시작을 위한 준비 함수입니다.
TeamManager:LoadContinuedGame -- 진행 중이던 게임이 있다면 불러옵니다.
TeamManager:SaveCurrentGame -- 강제 종료, 튕김 등의 사유 발생을 예방하기 위해 현재 상태를 저장합니다.
TeamManager:AddEXP -- 경험치를 올립니다.
TeamManager:OnSyncProperty -- 팀 체력 UI를 갱신합니다.
TeamManager:SetBattleResult -- 배틀의 승패 및 남은 유닛 수에 따라 체력을 깎습니다.
TeamManager:SetItemBoxList -- 아이템 박스를 열었을 때, 선택지를 결정하는 함수입니다.
TeamManager:SetEmblemBoxList -- 메달 박스를 열었을 때, 선택지를 결정하는 함수입니다.
TeamManager:GetItemFromItemBox -- 아이템 박스에서 selectIdx번 슬롯을 선택하면, 해당 슬롯의 아이템을 얻도록 처리합니다.
TeamManager:GetOnFieldSynergyCount -- 활성화된 시너지 수를 count만큼 증감시킵니다.
TeamManager:GetEnemyOwnedFieldSynergyCount -- 활성화된 시너지 수를 count만큼 증감시킵니다.
TeamManager:SwapRuneCardIndex -- 룬 카드의 배치 순서를 변경 요청을 받아 실행하는 함수입니다.
TeamManager:CheckActiveSynergy -- 현재 활성화된 시너지들의 수를 리턴해주는 함수입니다.
TeamManager:CheckSpecificSynergy -- 특정 시너지 활성화 여부를 리턴해주는 함수입니다.
PenaltyManager:InitNewGamePenaltySet -- 인게임 시작 전, 패널티 컴포넌트를 불러옵니다.
RC10003:InGameDataLoadHandler -- 전투 시작 시 보유한 룬 카드 1개마다 모든 아군의 공격 속도가 5%씩 증가합니다.
RC10009:SellThisRuneCard -- 황금 카르마의 가위를 획득합니다.
RC10010:SetDirectorValue -- DB에서 값을 불러왔을 떄 연출용 값들을 세팅하는 함수입니다.
RC10011:SellThisRuneCard -- 레벨 업에 필요한 경험치가 3 감소합니다.
RC10011:InGameDataLoadHandler -- 레벨 업에 필요한 경험치가 3 감소합니다.
RC10018:PlayEffect -- 유닛 소환 사운드
RC10020:SetDirectorValue -- DB에서 값을 불러왔을 떄 연출용 값들을 세팅하는 함수입니다.
RC10021:SellThisRuneCard -- 캐릭터를 판매하면 해당 캐릭터가 장착했던 완성 아이템들을 조합 아이템으로 분리합니다.
RC10022:SellThisRuneCard -- 전장에 배치 가능한 인원 수 +1
RC10023:SellThisRuneCard -- 전투에서 승리한 경우 4코인을 추가로 획득합니다.
RC10024:PlayEffect -- 발동 연출
RC10024:SetDirectorValue -- DB에서 값을 불러왔을 떄 연출용 값들을 세팅하는 함수입니다.
RC10026:SetDirectorValue -- DB에서 값을 불러왔을 떄 연출용 값들을 세팅하는 함수입니다.
RC10028:SetDirectorValue -- DB에서 값을 불러왔을 떄 연출용 값들을 세팅하는 함수입니다.
RC10034:PlayEffect -- 룬 카드 발동 연출
RC10036:SetDirectorValue -- DB에서 값을 불러왔을 떄 연출용 값들을 세팅하는 함수입니다.
RC10041:SellThisRuneCard -- 무작위 상징 아이템 2개를 장착한 허수아비를 소환합니다.
RC10041:InGameDataLoadHandler -- SetUnit 설정 필요
RC10042:SellThisRuneCard -- 시간의 신전 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10042:InGameDataLoadHandler -- 시간의 신전 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10043:SellThisRuneCard -- 엘나스 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10043:InGameDataLoadHandler -- 엘나스 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10044:SellThisRuneCard -- 빅토리아아일랜드 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10044:InGameDataLoadHandler -- 빅토리아아일랜드 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10045:SellThisRuneCard -- 루디브리엄 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10045:InGameDataLoadHandler -- 루디브리엄 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10046:SellThisRuneCard -- 아케인리버 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10046:InGameDataLoadHandler -- 아케인리버 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10047:SellThisRuneCard -- 오르비스 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10047:InGameDataLoadHandler -- 오르비스 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10048:SellThisRuneCard -- 시그너스 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10048:InGameDataLoadHandler -- 시그너스 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10049:SellThisRuneCard -- 모험가 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10049:InGameDataLoadHandler -- 모험가 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10050:SellThisRuneCard -- 기사단장 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10050:InGameDataLoadHandler -- 기사단장 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10051:SellThisRuneCard -- 마스코트 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10051:InGameDataLoadHandler -- 마스코트 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10052:SellThisRuneCard -- 수호대 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10052:InGameDataLoadHandler -- 수호대 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10053:SellThisRuneCard -- 선봉장 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10053:InGameDataLoadHandler -- 선봉장 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10054:SellThisRuneCard -- 마법사 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10054:InGameDataLoadHandler -- 마법사 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10055:SellThisRuneCard -- 책사 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10055:InGameDataLoadHandler -- 책사 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10056:SellThisRuneCard -- 사냥꾼 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10056:InGameDataLoadHandler -- 사냥꾼 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10057:SellThisRuneCard -- 추격자 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10057:InGameDataLoadHandler -- 추격자 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10058:SellThisRuneCard -- 싸움꾼 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10058:InGameDataLoadHandler -- 싸움꾼 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10059:SellThisRuneCard -- 저격수 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10059:InGameDataLoadHandler -- 저격수 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10060:SellThisRuneCard -- 방해꾼 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10060:InGameDataLoadHandler -- 방해꾼 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10061:SellThisRuneCard -- 아랫마을 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10061:InGameDataLoadHandler -- 아랫마을 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10062:SellThisRuneCard -- 마가티아 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10062:InGameDataLoadHandler -- 아랫마을 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10063:SellThisRuneCard -- 마가티아 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10063:InGameDataLoadHandler -- 아랫마을 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10064:SellThisRuneCard -- 처형자 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10064:InGameDataLoadHandler -- 처형자 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10065:SellThisRuneCard -- 결투가 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10065:InGameDataLoadHandler -- 결투 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10066:SellThisRuneCard -- 판타스틱 테마파크 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC10066:InGameDataLoadHandler -- 판타스틱 테마파크 시너지가 1개 추가로 포함된 것으로 간주합니다.
RC20001:SellThisRuneCard -- 이자로 획득 가능한 코인 한도가 5원 증가합니다. (최대 10코인)
RC20007:SetDirectorValue -- DB에서 값을 불러왔을 떄 연출용 값들을 세팅하는 함수입니다.
RC20008:InGameDataLoadHandler -- '특정 시너지'는 새 라운드가 시작할 때마다 바뀝니다.
RC20009:PlayEffect -- 하트 방어 연출
RC20011:SetDirectorValue -- DB에서 값을 불러왔을 떄 연출용 값들을 세팅하는 함수입니다.
RC20012:SetDirectorValue -- DB에서 값을 불러왔을 떄 연출용 값들을 세팅하는 함수입니다.
RC20013:PlayEffect -- 발동 연출
RC20013:SetDirectorValue -- DB에서 값을 불러왔을 떄 연출용 값들을 세팅하는 함수입니다.
RC20014:PlayEffect -- 발동 연출
RC20014:SetDirectorValue -- DB에서 값을 불러왔을 떄 연출용 값들을 세팅하는 함수입니다.
RC20015:PlayEffect -- 발동 연출
RC20021:SetDirectorValue -- DB에서 값을 불러왔을 떄 연출용 값들을 세팅하는 함수입니다.
RC20022:SellThisRuneCard -- 아이템 구매 비용이 50% 감소합니다.
RC20023:PlayEffect -- 사운드
RC20024:SellThisRuneCard -- 배치 가능한 유닛 수 +1
RC20030:PlayEffect -- 룬 카드 발동 연출 없음
RC20031:SetDirectorValue -- DB에서 값을 불러왔을 떄 연출용 값들을 세팅하는 함수입니다.
RC20032:PlayEffect -- 발동 연출 없음
RC20033:SellThisRuneCard -- __이 항상 유닛에게 최적의 아이템을 제공합니다.
RC20033:PlayEffect -- 발동 연출
RC20034:SellThisRuneCard -- 상점 캐릭터 판매 칸이 2칸 줄어듭니다. 대신 새로고침 비용이 1코인 줄어듭니다. (새로고침 비용은 1코인 아래로 내려갈 수 없습니다.)
RC20037:PlayEffect -- 발동연출
RC20038:SellThisRuneCard -- 경험치 구매에 필요한 비용이 1코인 줄어듭니다.
RC20040:PlayEffect -- 발동 연출
RC20043:SellThisRuneCard -- 허수아비를 둘 획득합니다.
RC20043:InGameDataLoadHandler -- 허수아비 체크
RC20044:SellThisRuneCard -- 현재 팀 레벨보다 한 단계 높은 상점 확률이 적용됩니다.
RC20045:SellThisRuneCard -- 시간의 신전 시너지 강화
RC20046:SellThisRuneCard -- 엘나스 시너지 강화
RC20047:SellThisRuneCard -- 빅토리아 아일랜드 시너지 효과
RC20048:SellThisRuneCard -- 슬리피우드 시너지 효과
RC20049:SellThisRuneCard -- 루디브리엄 시너지 효과
RC20050:SellThisRuneCard -- 아케인리버 시너지 효과
RC20051:SellThisRuneCard -- 오르비스 시너지 효과
RC20052:SellThisRuneCard -- 시그너스 시너지 효과
RC20053:SellThisRuneCard -- 모험가 시너지 효과
RC20054:SellThisRuneCard -- 전직교관 시너지 효과
RC20055:SellThisRuneCard -- 기사단장 시너지 효과
RC20056:SellThisRuneCard -- 마스코트 시너지 효과
RC20057:SellThisRuneCard -- 수호대 시너지 효과
RC20058:SellThisRuneCard -- 선봉장 시너지 효과
RC20059:SellThisRuneCard -- 마법사 시너지 효과
RC20060:SellThisRuneCard -- 책사 시너지 효과
RC20061:SellThisRuneCard -- 사냥꾼 시너지 효과
RC20062:SellThisRuneCard -- 그림자 시너지 효과
RC20062:InGameDataLoadHandler -- 그림자 시너지 효과
RC20063:SellThisRuneCard -- 추격자 시너지 효과
RC20064:SellThisRuneCard -- 싸움꾼 시너지 효과
RC20065:SellThisRuneCard -- 저격수 시너지 효과
RC20066:SellThisRuneCard -- 방해꾼 시너지 효과
RC20067:SellThisRuneCard -- 아랫마을 시너지 효과
RC20067:SetDirectorValue -- DB에서 값을 불러왔을 떄 연출용 값들을 세팅하는 함수입니다.
RC20068:SellThisRuneCard -- 마가티아 시너지 효과
RC20069:SellThisRuneCard -- 미우미우 시너지 효과
RC20070:SellThisRuneCard -- 처형자 시너지 효과
RC20071:SellThisRuneCard -- 처형자 시너지 효과
RC20072:SellThisRuneCard -- 판타스틱테마파크 시너지 효과
RC30002:SetDirectorValue -- DB에서 값을 불러왔을 떄 연출용 값들을 세팅하는 함수입니다.
RC30002:PlayEffect -- 발동 연출
RC30003:SellThisRuneCard -- 경험치를 구매하면 2의 추가 경험치를 얻습니다.
RC30004:PlayEffect_Copy -- 발동 연출
RC30004:SellThisRuneCard -- 판매하면 이펙트 끕니다.
RC30006:SellThisRuneCard -- 더 이상 이자를 얻을 수 없습니다.
RC30010:GetReward -- 확률에 따라 보상이 지급됩니다.
RC30010:SetDirectorValue -- DB에서 값을 불러왔을 떄 연출용 값들을 세팅하는 함수입니다.
RC30011:SellThisRuneCard -- 무작위 상징 아이템 3개를 장착한 무공을 소환합니다.
RC30011:InGameDataLoadHandler -- 무공 체크
RC30017:SetDirectorValue -- DB에서 값을 불러왔을 떄 연출용 값들을 세팅하는 함수입니다.
RC30019:SetDirectorValue -- DB에서 값을 불러왔을 떄 연출용 값들을 세팅하는 함수입니다.
RC40002:RuneBuffOn -- 333 콤보를 달성하면 모든 아군이 입는 피해량이 30% 감소합니다.
RC40002:SetDirectorValue -- DB에서 값을 불러왔을 떄 연출용 값들을 세팅하는 함수입니다.
RC40003:SellThisRuneCard -- 삭제하기 전, 복제한 컴포넌트를 삭제합니다.
RC40003:CopiedComponent -- 룬카드 복제할 때, 기존 룬카드 컴포넌트 가져와서 프로퍼티 체크 필요한지 확인
RC40003:InGameDataLoadHandler -- 오른쪽 룬 카드를 복제합니다.
RC40005:SellThisRuneCard -- 미르를 소환합니다.
RC40005:InGameDataLoadHandler -- 미르 체크
BTLogic_New:GetPath -- A* 알고리즘을 사용하여 시작점에서 목적지까지의 최적 경로를 찾는 함수
BTLogic_New:getDistance -- 두 노드 사이의 거리와 가로세로 간격을 계산하는 함수
BTLogic_New:getEntities -- AttackAble
BTLogic_New:getTarget -- mainTile 위치를 기준으로, enemies 중 type에 따라 결정된 타겟을 반환합니다.
BTLogic_New:getTargets -- Num 범위의 주위 유닛들 :  Around_MinNum_MaxNum
BTLogic_New:getVector -- Line
BTLogic_New:getTile -- 범위 내 가장 많은 적이 모인 빈 타일 :  EmptyTileWithMostEnemies_All_Num
BTLogic_New:getTiles -- StraightLine_Num : 지나치는 모든 라인의 타일들(타겟 지나감) 및 범위(Num)
BTLogic_New:getTileFromTile -- 범위 내 가장 많은 적이 모인 빈 타일 :  EmptyTileWithMostEnemies_All_Num
BTLogic_New:CheckAttackAble -- 스킬 사용 혹은 공격이 가능한 지 체크하는 함수
BTLogic_New:getNextMoveTile -- A* 알고리즘을 사용하여 다음 이동 타일의 경로를 계산하여 반환하는 함수
CustomizedBattleEffectService:README -- 서비스 설명을 제공하는 가이드 함수
CustomizedBattleEffectService:PlayDamageSkin -- 대상 엔티티에 데미지 타입에 맞는 데미지 폰트를 표시
CustomizedBattleEffectService:PlayEffect -- 지정된 위치에 이팩트를 재생하는 함수
CustomizedBattleEffectService:PlayEffectAttached -- 엔티티에 부착된 이팩트를 재생하는 함수
CustomizedBattleEffectService:SetMaterialOnClient -- 엔티티의 매테리얼을 변경하는 함수
CustomizedBattleEffectService:SetEntityEnable -- 엔티티의 활성화 상태를 설정하는 함수
CustomizedBattleEffectService:SetEntityVisible -- 엔티티의 가시성을 설정하는 함수
CustomizedBattleEffectService:LineRendererEffect -- 시작점과 대상 사이에 라인 이팩트를 생성하는 함수
DynamicMapSystemLogic:CreateDynamicMap -- 지정된 유저를 위한 다이나믹 맵을 생성하는 함수
DynamicMapSystemLogic:DestoryDynamicMap -- 지정된 유저의 다이나믹 맵을 삭제하는 함수
DynamicMapSystemLogic:OnBeginPlay -- 로직 시작 시 타이머를 설정하고 디버그 로그를 초기화하는 함수
DynamicMapSystemLogic:OnEndPlay -- 로직 종료 시 설정된 타이머들을 정리하는 함수
DynamicMapSystemLogic:PendingUserId -- 다이나믹 맵 삭제에 실패한 유저 ID를 대기 목록에 추가하는 함수
DynamicMapSystemLogic:TryDestroyPendingMap -- 대기 목록에 있는 다이나믹 맵들을 삭제 시도하는 함수
IngameEnteranceLogic:InsertQueue -- 인게임 입장 대기열에 유저 ID를 추가하는 함수
IngameEnteranceLogic:OnUpdate -- 매 프레임마다 호출되어 유저 로딩 완료 상태를 주기적으로 검사하는 함수
IngameEnteranceLogic:CheckUserLoadComplete -- 대기열의 첫 번째 유저의 로딩 완료 상태를 확인하는 함수
ItemSetLogic:SetDragStartEntity -- 아이템 드래그 시작 시 호출되는 함수로 UI 상태를 설정하고 시각적 피드백을 제공
ItemSetLogic:OnUpdate -- 드래그 중인 아이템이 마우스 커서를 따라다니도록 위치를 업데이트하는 함수
ItemSetLogic:SetDragEnd -- 아이템 드래그 종료 시 UI 상태를 원래대로 복구하는 함수
ItemSetLogic:OnDragEnd -- self:SetDragEnd()
ItemSetLogic:EquipItem_Check -- targetUnit에게 teamManager.OwnItems[itemSlotIdx] 아이템을 장착시킵니다.
ItemSetLogic:EquipItem -- targetUnit에게 user.TeamManager.OwnItems[itemIdx]를 장착시킵니다.
ItemSetLogic:EquipItemThroughItemID -- targetUnit에게 user.TeamManager.OwnItems[itemIdx]를 장착시킵니다.
ItemSetLogic:OpenItemBox_Check -- senderUser의 teamManager.OwnItems[itemSlotIdx]가 아이템 상자라면,
ItemSetLogic:WithdrawAllItems -- 유닛을 판매했을 때, 또는 자석 제거기를 사용했을 때 모든 아이템을 회수하는 함수입니다.
ItemSetLogic:WithdrawItem -- equippedIdx번에 장착한 아이템을 회수합니다.
ItemSetLogic:WithdrawCopiedItem -- 전투 종료 시 호출, 임시 아이템들을 삭제하는 로직
ItemSetLogic:UseConsumableItem -- 소모품 사용 로직
ItemSetLogic:ChangeAllItems -- 유닛에게 변환 망치를 사용했을 때, 아이템을 변화시키고 회수하는 함수입니다.
ItemSetLogic:GetItemBox -- 지정된 인덱스의 아이템 상자를 유저에게 지급하는 함수
ItemSetLogic:GetConsumableItem -- 지정된 인덱스의 소모성 아이템을 유저에게 지급하는 함수
ItemSetLogic:GetMaterialItem -- 지정된 인덱스의 재료 아이템을 유저에게 지급하는 함수
ItemSetLogic:GetNormalItem -- 지정된 인덱스의 일반 아이템을 유저에게 지급하는 함수
ItemSetLogic:GetEmblemItem -- 지정된 인덱스의 상징 아이템을 유저에게 지급하는 함수
ItemSetLogic:EmblemSynergyUpdate -- 상징 아이템이 장착 해제될 때, 시너지에 반영하는 함수입니다.
ItemSetLogic:GetItemList -- 지정된 타입과 시즌에 맞는 아이템 목록을 반환하는 함수
RuneCardSetLogic:SetDraggingEntity -- 룬 카드 인벤토리에서 카드를 드래그하기 시작했을 때 호출합니다.
RuneCardSetLogic:OnUpdate -- 드래그 중인 룬 카드가 마우스 커서를 따라다니도록 위치를 업데이트하는 함수
RuneCardSetLogic:SetDragEnd -- 판매 UI를 끕니다.
RuneCardSetLogic:OnDraggingEnd -- 룬 카드 드래그가 종료되었을 때 호출합니다.
RuneCardSetLogic:SwapUIPositionOnDrag -- 룬 카드를 드래그하는 중 다른 카드 위에 마우스를 올렸을 때 실행하는 함수
RuneCardSetLogic:SetCurrentMouseHoveringSlot -- 마우스가 호버링하고 있는 슬롯의 인덱스를 설정하는 함수
RuneCardSetLogic:GetRuneCardList -- getRuneCheck : 현재 가진 룬 카드 제외할 지
S01_SkillDescLogic:OnBeginPlay -- 로직 시작 시 모든 스킬 설명 데이터를 초기화하는 함수
StatusChangeLogic:CheckDamage -- 데미지를 계산하여 일반 데미지와 고정 데미지로 분리하여 반환하는 함수
StatusChangeLogic:SetVariableStatus -- 체력이나 마나값을 변동시키는 함수입니다.
StatusChangeLogic:SetStack -- 유닛의 스택 속성을 설정하고 최대값을 제한하는 함수
StatusChangeLogic:HitDamage -- 공격자가 대상에게 데미지를 가하고 방어력과 저항력을 적용하여 최종 데미지를 계산하는 함수
StatusChangeLogic:KillUnitForce -- 시너지 효과 등에 의해 강제로 죽이는 함수입니다.
StatusChangeLogic:SetShield -- targetUnit이 보호막을 획득하는 함수입니다.
StatusChangeLogic:ShieldCheck -- 보유한 보호막 수치를 종합 계산하는 함수입니다.
StatusChangeLogic:GetBuff -- unit에게 statusType의 버프를 줍니다.
StatusChangeLogic:BuffCheck -- 유닛의 모든 버프 상태를 확인하고 지속시간을 감소시키는 함수
StatusChangeLogic:SetStatus -- unit에게 statusEffectID 키를 가진 상태이상을 setTime 초동안 부여하는 함수입니다.
StatusChangeLogic:RemoveStatusEffect -- unit이 statusEffectID 상태이상을 보유하고 있다면 해제합니다.
StatusChangeLogic:RemoveOneoffStats -- 단 번의 전투에서만 적용되는 스탯(버프, 보호막)을 제거하는 함수입니다.
StatusChangeLogic:PlayStatusEffectAnimation -- 상태이상 효과의 시각적 애니메이션을 재생하거나 중지하는 함수
UnitInfoUILogic:SetBar -- 유닛의 HP, MP, 보호막 바를 UI에 업데이트하는 함수
UnitInfoUILogic:SetBarcode -- 유닛의 HP와 MP 바 위에 눈금 가이드를 표시하는 함수
UnitInfoUILogic:SetItemList -- 유닛 체력바의 '장착 아이템 목록'을 갱신하는 함수입니다.
UnitInfoUILogic:RefreshSynergy -- 시너지 정보를 UI에 업데이트하고 페이지를 관리하는 함수
UnitInfoUILogic:SetLevelMaterial -- 유닛의 레벨과 등급에 따른 재료 정보를 UI에 표시하는 함수
UnitSetLogic_New:SettingTile -- 맵의 모든 타일에 컴포넌트를 초기화하고 설정하는 함수
UnitSetLogic_New:DragUnit -- Unit Info
UnitSetLogic_New:Drag -- 유닛 드래그 중 화면 터치 이벤트를 처리하는 함수
UnitSetLogic_New:TouchRelease -- selectUnit을 selectTile로 옮기는 함수입니다.
UnitSetLogic_New:TouchReleaseByForce -- selectUnit을 selectTile로 옮기는 함수입니다.
UnitSetLogic_New:SpawnUnit -- 새로운 유닛을 획득(구매, 이벤트 라운드 보상 등)하는 함수입니다.
UnitSetLogic_New:SpawnOnetimeUnit -- 해당 전투에만 참여하는 일회성 유닛을 소환합니다.
UnitSetLogic_New:CheckUnitMerging -- Merge 가능 여부를 체크하고, 가능하면 수행합니다.
UnitSetLogic_New:MergeUnits -- 오너가 userId인 unitTable의 유닛들을 합칩니다.
UnitSetLogic_New:SellUnit -- 유닛을 판매하는 함수입니다.
UnitSetLogic_New:BattleSetting_UnitSet -- 전투 시작/종료 시 적 유닛을 생성 또는 제거하거나 관리하는 함수
UnitSetLogic_New:BattleSetting_OnSettingPhase -- 준비 > 세팅 > 전투 단계 중 '세팅' 단계에서 수행하는 함수입니다.
UnitSetLogic_New:BattleSetting_OnBattlePhase -- 준비 > 세팅 > 전투 단계 중 '전투' 단계가 시작할 때 수행하는 함수입니다.
UnitSetLogic_New:UnitSampleSpawn -- 유닛으로 사용할 엔티티 샘플을 미리 스폰해두는 함수입니다.
UnitSetLogic_New:ProjectileSampleSpawn -- 투사체로 사용할 엔티티를 미리 소환해두는 함수입니다.
UnitSetLogic_New:UnitSampleDestroy -- 유저가 나가면 유닛 샘플 엔티티를 지우는 함수입니다.
UnitSetLogic_New:ProjectileSampleDestroy -- 유저가 나가면 투사체 샘플 엔티티를 지우는 함수입니다.
UnitSetLogic_New:PlayMergeDirection -- Merge 연출을 재생하는 함수입니다.
UnitSetLogic_New:SpawnShadow -- 그림자 캐릭터의 쉐도우 파트너를 소환/소환 해제 하는 함수입니다.
UnitSetLogic_New:SpawnDoDo -- 도도를 소환/소환 해제 하는 함수입니다.
UnitSetLogic_New:SpawnOrbisStone -- 오르비스 소환석을 소환/소환 해제 하는 함수입니다.
UnitSetLogic_New:GetEmptyPooledUnit -- 풀링한 엔티티 중 사용할 엔티티를 찾습니다.
UnitSetLogic_New:BattleSetting_EnemyUnit -- 적 유닛을 소환하는 함수
UnitSetLogic_New:BattleSetting_EnemySynergyCheck -- 적 시너지를 체크해서 활성화된 시너지에 따라 추가 작업을 하는 코드
UnitSetLogic_New:SpawnEnemyUnit -- 적 유닛을 소환하는 함수
UnitSetLogic_New:GetProjectileEntity -- 적 유닛을 소환하는 함수
Attack_Sample:Attack -- 대상 유닛에게 물리 공격을 수행하고 애니메이션과 데미지를 처리
Attack_Sample:SetDamage -- 대상 유닛에게 실제 데미지를 적용하고 히트 이펙트를 재생
Attack_Sample:HitEffect -- 대상 유닛에게 공격 히트 이펙트를 표시
C00004_Mugong_Attack:SetShadow -- 그림자가 이동합니다
C10001_Slime_Attack:SetShadow -- 그림자가 점점 작아집니다
C10002_OrangeMushRoom_Attack:SetShadow -- 그림자가 점점 작아집니다
C10015_Hodori_Attack:SetShadow -- 그림자가 점점 작아집니다
C10016_Homun_Attack:SetShadow -- 그림자가 점점 작아집니다
C20001_Hawkeye_Attack:SetShadow -- 그림자가 잠깐 사라집니다
C20002_Pepe_Attack:SetShadow -- 그림자가 이동합니다
C20007_Eckhart_Attack:SetShadow -- 그림자가 이동합니다
C20008_Lioner_Attack:SkillLineEffect -- 다수의 적이 피해를 받았을 때 대상과 가까운 적들을 공격
C30010_DarkLord_Attack:SetShadow -- 그림자가 이동합니다.
C30011_Mushmom_Attack:SetShadow -- 그림자가 점점 작아집니다
C30012_Faust_Attack:PlaySkillEffect -- 범위 표시
C40002_Grendel_Attack:PlaySkillEffect -- 범위 표시
C40008_Shadower_Attack:SetShadow -- 그림자가 이동합니다
C50001_PinkBean_Attack:AttackEffect -- 기본 공격 파티클을 띄웁니다. 자주 표시되는 파티클이라 엔터티를 삭제하지 않고 최대한 재활용합니다.
C00001_YetiAndPepe_Skill:PlaySkillEffect_Range -- 범위 표시
C00001_YetiAndPepe_Skill:PlaySkillEffect_Particle -- 예티 손과 손사이에 힘 표시 : 파티클
C00001_YetiAndPepe_Skill:RemoveEffect -- 파티클 삭제
C00002_Dodo_Skill:SpawnAggressiveIcon -- 도발 마크
C00002_Dodo_Skill:SetShadow -- 그림자가 점점 작아집니다
C00005_Mir_Skill:SetShadow -- 그림자가 점점 작아집니다
C10002_OrangeMushRoom_Skill:PlaySkillEffect -- 범위 표시
C10002_OrangeMushRoom_Skill:SetShadow -- 그림자가 점점 작아집니다
C10008_MemoryMonk_Skill:PlaySkillEffect -- 범위 표시
C10010_Newbie_Skill:SetShadow -- 그림자가 이동합니다
C10016_Homun_Skill:Reflection -- 예외 처리
C10018_Powderbutterfly_Skill:PlaySkillEffect -- 범위 표시
C10019_Goopi_Skill:SetTargetEffect -- 타겟 표시
C20002_Pepe_Skill:PlaySkillEffect -- 범위 표시
C20004_DanceswithBalrog_Skill:Reflection -- 예외 처리
C20005_QualmMonkTrainee_Skill:PlayRangeSkillEffect -- 범위 표시
C20007_Eckhart_Skill:SetShadow -- 그림자가 이동합니다
C20008_Lioner_Skill:PlaySkillEffect -- 라이오너 뿔에 파티클표시
C20008_Lioner_Skill:RemoveEffect -- 파티클 삭제
C20010_IceDrake_Skill:PlaySkillEffect -- 범위 표시
C20011_Archer_Skill:SkillLineEffect -- 자신과 적을 선으로 연결
C20013_Monkeyrog_Skill:SetShadow -- 그림자가 점점 작아집니다
C20014_Blin_Skill:SetShadow -- 그림자가 사라집니다.
C20014_Blin_Skill:PlayEffect -- 범위 표시
C20015_ThreeTailedFox_Skill:SkillLineEffect -- 다수의 적이 피해를 받았을 때 대상과 가까운 적들을 공격
C20016_DeetAndRoi_Skill:PlayRangeSkillEffect -- 범위 표시
C20017_Homunspeculler_Skill:SkillLineEffect -- 다수의 적이 피해를 받았을 때 대상과 가까운 적들을 공격
C30001_Yeti_Skill:PlaySkillEffect -- 범위 표시
C30004_Taurospear_Skill:SkillLineEffect -- 자신과 적을 선으로 연결
C30006_BlazeWizard_Skill:SkillLineEffect -- 자신과 적을 선으로 연결
C30007_Priest_Skill:PlaySkillEffect -- 범위 표시
C30009_NightWalker_Skill:PlaySkillEffect -- 범위 표시
C30011_Mushmom_Skill:PlaySkillEffect -- 범위 표시
C30011_Mushmom_Skill:SetShadow -- 그림자가 점점 작아집니다
C30013_Kyrin_Skill:SkillLineEffect -- 자신과 적을 선으로 연결
C30016_WindGuardian_Skill:PlayRangeSkillEffect -- 범위 표시
C30018_SnowWitch_Skill:SkillLineEffect -- 자신과 적을 선으로 연결
C30020_Jellybus_Skill:PlaySkillEffect -- 범위 표시
C40004_Timer_Skill:SkillLineEffect -- 자신과 적을 선으로 연결
C40005_NeinHeart_Skill:PlaySkillEffect -- 범위 표시
C40006_JuniorBarlog_Skill:PlaySkillEffect -- 범위 표시
C40007_WindArcher_Skill:SetTargetEffect -- 타겟 표시
C40014_NineTailedFox_Skill:SkillLineEffect -- 다수의 적이 피해를 받았을 때 대상과 가까운 적들을 공격
C40015_Rurumo_Skill:PlayEffect -- 범위 표시
C40016_SkyGuardian_Skill:SkillLineEffect -- 자신과 적을 선으로 연결
C50001_PinkBean_Skill:PlaySkillEffect -- 범위 표시
C50005_Lucid_Skill:SetBattle -- self.skillCount = 0
C50006_CrimsonBalrog_Skill:PlaySkillEffect -- 빈 테이블이라면 먼저 자식 엔터티에 파티클 엔터티가 있는지 확인합니다.
C50008_Papulatus_Skill:PlaySkillEffect -- 범위 표시
C50010_Frankenroid_Skill:PlaySkillEffect -- 범위 표시
C50010_Frankenroid_Skill:SetShadow -- 그림자가 점점 작아집니다
C50013_Scarlion_Skill:GetTreasure -- 보물찾기 (고유)
SkillComponent:Skill -- 대상 유닛에게 기본 액티브 스킬을 사용하고 애니메이션과 사운드를 재생
Skill_Sample:Skill -- 대상 유닛에게 스킬을 사용하고 MP를 소모하여 데미지를 가함
Skill_Sample:SetSkillDamage -- 대상 유닛에게 스킬 데미지를 적용하고 히트 이펙트를 재생
Skill_Sample:HitEffect -- 대상 유닛에게 스킬 히트 이펙트를 표시
AProjectileInfo:SetProjectile -- 발사체를 설정하고 대상을 향해 이동시키며 충돌 시 데미지를 적용
AProjectileInfo:Destroy -- 발사체를 파괴하고 초기 상태로 되돌림
AProjectileInfo:SetPosition -- 발사체의 위치와 회전을 설정
AProjectileInfo:SetFlipX -- 발사체의 스프라이트를 X축으로 뒤집기 설정
AProjectileInfo:SetOwnerID -- 발사체의 소유자 ID를 서버와 클라이언트에 설정
AProjectileInfo:SetOwnerIDInClient -- 클라이언트에서 발사체의 소유자 ID를 설정
SkillProjectile2Info:SetProjectile -- 스킬 발사체를 설정하고 두 번째 대상을 향해 이동시켜 스킬 데미지를 적용
SkillProjectile2Info:Destroy -- 스킬 발사체를 파괴하고 컴포넌트를 제거
SkillProjectile2Info:SetPosition -- 스킬 발사체의 위치와 회전을 설정
SkillProjectile2Info:SetFlipX -- 스킬 발사체의 스프라이트를 X축으로 뒤집기 설정
SkillProjectileInfo:SetProjectile -- 스킬 발사체를 설정하고 대상을 향해 이동시켜 스킬 데미지를 적용
SkillProjectileInfo:Destroy -- 스킬 발사체를 파괴하고 컴포넌트를 제거
SkillProjectileInfo:SetPosition -- 스킬 발사체의 위치와 회전을 설정
SkillProjectileInfo:SetFlipX -- 스킬 발사체의 스프라이트를 X축으로 뒤집기 설정
SkillShotCheckComponent:SetOwnerID -- 스킬 발사체의 소유자 ID를 서버와 클라이언트에 설정
SkillShotCheckComponent:SetOwnerIDInClient -- 클라이언트에서 스킬 발사체의 소유자 ID를 설정
MotionComponent:MotionChangeToIdle -- 유닛의 모션을 Idle 상태로 변경하고 애니메이션을 재생
MotionComponent:Check -- 유닛의 상태를 확인하고 필요시 모션을 변경
MotionComponent:HandleSpriteAnimPlayerEndFrameEvent -- 스프라이트 애니메이션 프레임 종료 이벤트 처리
UnitAIWanderComponent:OnBeginPlay -- AI 행동 트리 노드들을 초기화하고 루트 노드를 설정
UnitAIWanderComponent:BattleEnd -- 전투 종료 시 모든 BT 관련 프로퍼티를 초기화
UnitAIWanderComponent:Move -- 유닛을 현재 타일에서 다음 타일로 이동시키는 함수
UnitAIWanderComponent:YetiAndPePe -- 예티와 페페 특수 이동 (포물선 궤도로 날아가는 이동)
UnitAnimationComponent:OnBeginPlay -- 클라이언트에서 캐릭터 정보 테이블을 로드
UnitAnimationComponent:SetAnimRUID -- 캐릭터 ID에 따라 애니메이션 RUID를 설정
UnitAnimationComponent:PlayAnimation -- 지정된 애니메이션을 재생하고 방향을 설정
UnitAnimationComponent:PlayHitDirection -- 피격 시 스프라이트를 빨간색으로 변경 후 원래 색으로 복원
UnitAnimationComponent:SetDefaultColor -- 스프라이트의 기본 색상을 설정
UnitAnimationComponent:SetStatusEffectLayerOrder -- 상태 이상 이펙트들의 레이어 순서를 설정
UnitAnimationComponent:SetLayerOrder -- 스프라이트의 레이어 순서를 설정
UnitAnimationComponent:SetFlip -- 스프라이트의 X, Y축 반전 설정
UnitBattleStatistics:RoundPropertyInitialize -- 라운드마다, 각 프로퍼티 값 초기화
UnitBattleStatistics:SetProperty -- 전투 통계 프로퍼티 값을 설정하고 누적
UnitBattleStatistics:SetPropertyToClient -- 클라이언트에서 전투 통계 프로퍼티 값을 설정
UnitBattleStatistics:RoundPropertyInitializeToClient -- 라운드마다, 각 프로퍼티 값 초기화
UnitBattleStatistics:PropertyClear -- 모든 전투 통계 프로퍼티들을 초기화
UnitBattleStatistics:PropertyClearToClient -- 클라이언트에서 모든 전투 통계 프로퍼티들을 초기화
UnitBattleStatistics:SetPropertyWithKey -- 특정 키로 전투 통계 프로퍼티 값을 설정
UnitBattleStatistics:SetPropertyInClientWithKey -- 클라이언트에서 특정 키로 전투 통계 프로퍼티 값을 설정
UnitInfo:OnBeginPlay -- 유닛 초기화 시 스프라이트 렌더러와 모션 컴포넌트를 설정
UnitInfo:SetCharInfo -- 캐릭터 정보를 설정하고 관련 컴포넌트들을 초기화
UnitInfo:ChangeCharInfo -- 기존 캐릭터 정보를 새로운 캐릭터로 변경
UnitInfo:CleanCharInfo -- 캐릭터 정보를 초기화하고 모든 상태를 리셋
UnitInfo:SetTransformScale -- 유닛의 크기와 콜라이더, UI 위치를 설정
UnitInfo:SetResourceInfo -- 리소스 정보를 설정하여 RectSize와 CenterPivot을 업데이트
UnitInfo:SetOutlineMaterial -- 유닛의 외곽선 머테리얼을 설정하거나 레벨에 따른 색상 적용
UnitInfo:SetPosition -- 유닛의 월드 좌표를 설정
UnitInfo:CleanPosition -- 유닛을 화면 밖으로 이동시켜 숨김 처리
UnitInfo:SetPropertyToServer -- 서버에서 프로퍼티를 설정하고 클라이언트에 동기화
UnitInfo:SyncPropertyToClient -- 클라이언트에서 서버로부터 받은 프로퍼티 값을 적용
UnitInfo:IsOnFieldUnit -- 유닛이 전장에 있는지 대기석에 있는지 확인
UnitInfo:DoesHaveSynergy -- 유닛이 특정 시너지를 보유하고 있는지 확인
UnitInfo:GetOwnSynergies -- 유닛이 보유한 모든 시너지를 반환 (기본 + 상징 아이템)
UnitInfo:SetCenterPivot -- 스프라이트 RUID를 기반으로 중심점을 설정
UnitInfo:SetUnitStatusUIEnable -- 유닛 상태 UI(체력바 등)의 표시 여부를 설정
UnitInfo:SetDefaultInfo -- 유닛의 기본 정보를 설정 (주석 처리된 코드)
UnitInfo:HandleTouchEvent -- 유닛 클릭 이벤트 처리 (드래그 시작)
UnitInfo:HandleTouchReleaseEvent -- 유닛 터치 릴리즈 이벤트 처리 (드래그 종료)
UnitItem:OnBeginPlay -- 아이템 컴포넌트 초기화 및 스택 초기화
UnitItem:RefreshItemStatus -- 아이템을 장착할 때, 아이템으로 얻는 스탯 효과를 갱신하는 함수입니다.
UnitItem:OnSettingPhase -- 준비 > 세팅 > 전투 중 '세팅' 단계가 시작되면 실행합니다.
UnitItem:OnBattleStart -- 전투 시작 시 효과
UnitItem:OnEquippedChangedDuringBattlePhase -- 전투 중 idx번 슬롯에 아이템을 장착한 경우, 해당 아이템의 전투 시작 효과를 발동시키기 위한 함수입니다.
UnitItem:OnAttacked -- 피격 시 발동되는 효과
UnitItem:OnAttacked_Damage -- 공격자가 특정 아이템을 가지고 있을 경우 발동되는 효과
UnitItem:OnUseSkill -- 스킬 사용 시 효과
UnitItem:OnKillUnit -- 스킬 사용 시 효과
UnitItem:OnDefaultAttack -- 공격 시 효과
UnitItem:OnDefaultAttackHit -- 기본 공격 적중 시 효과
UnitItem:OnSkillHit -- 스킬 적중 시 효과
UnitItem:OnVamp -- 흡혈 시 발동되는 효과
UnitItem:ClearAllStacks -- 모든 아이템의 사용 효과, 누적 스택 등의 값을 초기화하는 함수
UnitItem:UseItemAbility_NI10001 -- 화염의 카타나 : 전투 시작 후 5초마다 공격력 +15% (중첩 가능)
UnitItem:UseItemAbility_NI10002 -- NI10002 스틸 미셀: 전투 시작 후 15초간 기절 등 상태이상으로부터 면역 상태가 됩니다.
UnitItem:UseItemAbility_ShieldByHP -- 전투 당 1번, 남은 체력이 30%가 되면 최대 체력의 20%만큼 보호막 획득.
UnitItem:UseItemAbility_NI10004 -- NI10004 도깨비 방망이: 체력이 60%가 되면 2초간 은신 및 무적 상태가 됩니다.
UnitItem:UseItemAbility_NI10006 -- NI10006 소드 이어링: 기본 공격 및 스킬로 피해를 입힌 대상을 6초동안 화상 및 회복력 감소 상태로 만듭니다.
UnitItem:UseItemAbility_NI10007 -- (NI10007) 물리 공격 적중 시 20% 확률로 대상을 마나 과부하 상태로 만듭니다.
UnitItem:UseItemAbility_NI10008 -- NI10008 붉은 채찍: 세 번째 기본 공격 적중 시 주변 1칸 내 적에게 70%의 추가 물리 피해
UnitItem:UseItemAbility_NI10009 -- NI10009 신속의 날개: 기본 공격 시 공격속도가 3% 증가합니다. 이 효과는 중첩됩니다.
UnitItem:UseItemAbility_NI10010 -- NI10010 냄비 뚜껑: 3번째 기본 공격 적중 대상에게 30의 물리 피해를 입히고 4초간 물리 방어 약화 상태로 만듦
UnitItem:UseItemAbility_NI10011 -- NI10011 화이트 네쉐르: 기본 공격 적중 대상에게 30의 마법 피해를 입히고 4초간 마법 방어 약화 상태로 만듦
UnitItem:UseItemAbility_NI10012 -- NI10012 드래곤 샤인 보우: 스킬 사용 후 다음 기본 공격시 마력의 200%에 해당하는 추가 마법 피해를 줍니다.
UnitItem:UseItemAbility_NI10015 -- NI10015 파란색 권투 글러브: 공격하거나 피해를 받으면 입는 피해량 -0.4%, 가해량 +0.8% (최대 25스택)
UnitItem:UseItemAbility_NI10017 -- NI10017 에스터 실드:--전투 시작: 본인을 제외한 주변 1칸 내 아군에게 물리 방어력 +20, 마법방어력 +20 제공
UnitItem:UseItemAbility_NI10019 -- NI10019 타임리스 귀고리: 2초마다 파동을 일으켜 주변 2칸 내 무작위 적 하나에게 75의 물리 피해를 입히고, 6초간 물리 방어 약화 적용
UnitItem:UseItemAbility_NI10020 -- NI10020, NI10025 : 스킬 사용 시 4초동안 최대 마나의 100%만큼 보호막 획득
UnitItem:UseItemAbility_NI10021 -- NI10021 파란색 가운: 2초마다 최대 체력의 5% 회복
UnitItem:UseItemAbility_NI10023 -- 가한 피해량의 20%만큼 체력 비율이 가장 낮은 아군 치유
UnitItem:UseItemAbility_NI10024 -- NI10024 사파이어  귀고리: 2초마다 마법 폭발을 일으켜 주변 2칸 내 무작위 적 하나에게 75의 마법 피해를 입히고, 6초간 마법 방어 약화 적용
UnitItem:UseItemAbility_NI10027 -- 전투 시작 후 5초마다 마력 +15% (중첩 가능)
UnitItem:UseItemAbility_NI10028 -- NI10028 레드 해골 귀고리: 기본 공격 및 스킬로 피해를 입힌 대상을 6초동안 화상 및 회복력 감소 상태로 만듭니다.
UnitItem:UseItemAbility_NI10030 -- NI10030 별빛 팔찌: 전투 시작 후 15초간 기절 등 상태이상으로부터 면역 상태가 됩니다.
UnitItem:UseItemAbility_NI10032 -- NI10032 골드 드롭 귀고리: 스킬 사용 시 MP MAX의 30%만큼 크리티컬 확률 증가 (중첩 가능)
UnitItem:UseItemAbility_NI10033 -- NI10033 산타 장갑:
UnitItem:UseItemAbility_NI10034 -- NI10034 : 스킬 사용 시, 가장 가까운 아군 1명 및 자신에게 MP 10 제공
UnitItem:UseItemAbility_NI10035 -- 스킬 사용 시 자기 자신을 제외한 체력 비율이 가장 낮은 아군에게 4초간 소모한 마나의 200%만큼 보호막 부여
UnitItem:UseItemAbility_SI10002 -- 분노의 옥석
UnitItem:UseItemAbility_SI10003 -- 질투의 옥석
UnitItem:UseItemAbility_SI10004 -- 식탐의 옥석
UnitItem:UseItemAbility_SI10005 -- 후회의 옥석
UnitItem:UseItemAbility_SI10006 -- 나태의 옥석
UnitItem:UseItemAbility_SI10007 -- 탐욕의 옥석
UnitItem:UseItemAbility_SI10008 -- 시기의 옥석
UnitItem:IsEquipingItem -- 이 유닛이 itemID에 해당하는 아이템을 장착하고 있는지 여부를 검사, 장착하고 있으면 true를 반환합니다.
UnitStatus:SetUnitStatus -- 유닛의 각종 스탯을 계산하는 함수입니다.
UnitStatus:Dead -- 유닛이 죽으면 호출되는 함수입니다.
UnitStatus:SetUniInfoPopup -- 우클릭으로 보는 유닛 정보 팝업을 갱신하도록 하는 함수입니다.
UnitStatus:SetProperty -- 이 컴포넌트의 Property들은 특정 유저의 클라이언트에만 sync 되어야 하고, sync 상태를 유지해야 합니다.
UnitStatus:ApplyStatusEffect_SE0017 -- 화상 상태이상을 최초로 활성화 또는 비활성화할 때 호출하는 함수입니다.
UnitStatus:SetUnitStatusByStat -- 유닛의 각종 스탯을 계산하는 함수입니다.
UnitSynergy:ClearAllStackProperties -- 전투 중 획득/소모한 스택 값들을 되돌립니다.
UnitSynergy:OnActivatedSynergyCountChanged -- 전장에 활성화된 시너지 숫자가 변경될 때마다 호출합니다.
UnitSynergy:OnBattleStart -- 전투가 시작될 때 호출합니다.
UnitSynergy:OnShieldBreak -- 보호막이 파괴되었을 때 호출합니다.
UnitSynergy:OnHit -- 피격할 때 호출합니다.
UnitSynergy:OnDefaultAttackHit -- 내 기본 공격이 적중했을 때 호출
UnitSynergy:OnSkillHit -- 내 스킬이 적중할 때 호출합니다.
UnitSynergy:OnChangeHP -- 상대 체력을 깎을 때 호출합니다.
UnitSynergy:OnDead -- 이 유닛이 죽었을 때 실행하는 함수
UnitSynergy:S10002_MakeStun -- 수호대 : 수호대의 보호막을 파괴한 적 기절
UnitSynergy:S10002_TrueDamage -- 수호대 10시너지 : 기본 공격 시, 보유한 보호막의 5% 만큼 고정 피해를 입힙니다.
UnitSynergy:S10003_Taunt -- 선봉장 : 전투 시작 시, 그리고 체력이 50% 이하가 되면 주변 2칸 내 모든 적을 도발합니다.
UnitSynergy:S10003_DamageDecrease -- 선봉장 : 입는 피해량 감소
UnitSynergy:S10006_Vamp -- 사냥꾼 : 체력이 70% 이하일 때 흡혈률 획득
UnitSynergy:S10006_GetPhysicalAttack -- 사냥꾼 11 시너지 : 체력이 70% 이하일 때 추가 공격력 50% 획득
UnitSynergy:S10009_Recover -- 싸움꾼 : 체력이 30% 이하일 때 6초동안 회복 및 저지불가
UnitSynergy:S10010_Sniping -- 저격수 : 일정 시간마다 체력 수치가 가장 낮은 캐릭터를 추가로 공격
UnitSynergy:S10010_HPDown -- 저격수(7) : 체력이 30% 이하일 때 3초동안 은신
UnitSynergy:S10013_OnUseSkill -- 전설의 궁수 (헬레나 고유 시너지) : 스킬을 사용할 때마다 적들로부터 가장 먼 칸으로 이동합니다.
UnitSynergy:S10019_OnDead -- 루디브리엄 캐릭터가 처치되면 가지고 있던 아이템을 복사해 아이템이 없는 무작위 아군에게 장착시킵니다.
UnitSynergy:S10033_Stat -- 미우미우 :
UnitSynergy:S10033_maxMPDown -- 미우미우 :
UnitSynergy:S10034_Execution -- 6 시너지 이상부터 데미지를 받아 일정 체력 비율 이하로 낮아진 적은 처형됩니다.
UnitSynergy:S10035_Stat -- 결투가는 공격할 때마다 공격 속도가 최대 12회(룬카드 사용 시, 30회)까지 증가합니다.
UnitSynergy:S10035_RuneAddStat -- 룬 효과로 결투가는 공격 속도 5회 더 중첩된 상태로 전투를 시작합니다.
AttackCheck:OnBehave -- 공격 가능 여부를 확인하고 공격을 실행하는 BT 노드
MoveCheck:OnBehave -- 타겟까지의 경로를 탐색하고 이동을 실행하는 BT 노드
MoveCheck:GetTile -- 타일 노드 좌표로부터 실제 타일 엔티티를 가져오는 함수
SkillCheck:OnBehave -- 스킬 사용 가능 여부를 확인하고 스킬을 실행하는 BT 노드
TargetCheck:OnBehave -- 공격 대상을 탐색하고 설정하는 BT 노드
UI_LevelReward:Update_RewardEntity -- 레벨 보상 엔티티의 UI 요소들을 업데이트
UI_LevelReward:OnBeginPlay -- 레벨 보상 설명 텍스트를 초기화
UI_LevelReward:HandleUITouchEnterEvent -- 마우스 호버 시 툴팁 위치를 조정
UI_LevelUP_Popup:SetPopup -- 아마 이미지폰트로 교체하게 될 것 같지만 일단 텍스트로... [여기부터 레벨 표시]
UI_LevelUP_Popup:OpenPopup -- 레벨업 팝업을 열고 사운드를 재생
UI_LevelUP_Popup:TooltipOpen -- TouchReceive에 할당하는 함수
UI_PlayerLevel:OnBeginPlayCustomButtonFunc_toDotIndicator -- 닷 인디케이터 버튼들에 이벤트를 연결
UI_PlayerLevel:CreatePopup_LevelRewardList -- 레벨 보상 리스트 팝업을 생성하고 페이지를 설정
UI_PlayerLevel:RefreshLobbyProfile -- 로비에서 플레이어 레벨과 경험치 정보를 업데이트
UI_PlayerLevel:InitializeLobbyProfile -- 로비 프로필을 초기값으로 설정
UI_PlayerLevel:GetRewardIconInfo -- 보상 ID에 따른 아이콘 정보를 반환
UI_PlayerLevel:HandleButtonClickEvent -- 레벨 보상 리스트 팝업 열기 버튼 클릭 이벤트
UI_PlayerLevel:HandleButtonClickEvent2 -- 이전 페이지 버튼 클릭 이벤트
UI_PlayerLevel:HandleButtonClickEvent3 -- 다음 페이지 버튼 클릭 이벤트
AchievementManager:HandleInGameStart -- 게임 시작 시 stack처럼 사용한 일부 업적의 데이터를 초기화합니다.
AchievementService:UpdateAchievement -- log("@h",achievementID,value)
AchievementService:SaveAchieveDB -- -- 업적: 로그인 횟수 증가 / 강종했을때의 시간이 9시를 넘었을 수 있으므로
UI_AchievementList:OnBeginPlay -- 업적 카테고리 Cell UI 생성하기
UI_AchievementList:HandleButtonClickEvent -- 업적 UI의 닫기 버튼 클릭
UI_AchievementService:OnBeginPlay -- 툴팁 UI 끄기
UI_AchievementService:EnableRewardPopup -- 모두받기 버튼 비활성화----
UI_AchievementService:EnableAllRewardButton -- ---
UI_AchievementStep:HandleButtonClickEvent2 -- 업적 단계 UI의 닫기 버튼 클릭
CoachMoveComponent:CoachSleepTimer -- 100초동안 코치와 아무 상호작용이 없다면 SleepRUID를 보여줍니다.
CoachService:OnBeginPlay -- 마스터 코치 애니메이션 이펙트 ruid
UI_GachaDirection:OnBeginPlay -- 가챠 연출 UI 초기 상태 설정
UI_GachaDirection:SetGoodsID -- 가챠 상품 ID를 설정하는 함수
UI_GachaDirection:HandleButtonClickEvent -- 가챠 연출 문 클릭 이벤트 핸들러
UI_GachaDirection:HandleButtonClickEvent3 -- 가챠 연출 스킵 버튼 클릭 이벤트 핸들러
UI_GachaResult:OnClick_ResultCloseBtn -- 가챠 결과 화면 UI 닫기
UI_GachaResult:SetGachaResult_10Times -- 10연차 뽑기. 데이터 받아와서 순차출력함
CoachShopDataLogic:OnBeginPlay -- 게임 시작 시 상점 관련 데이터셋들을 로드하는 초기화 함수
CoachShopDataLogic:Get_Gacha -- 가챠 상품 ID로 가챠 상품 정보를 조회하는 함수
CoachShopDataLogic:Get_CoachPrice -- 코치 코스트로 가격 정보를 조회하는 함수
CoachShopDataLogic:Get_CoachPriceById -- 상품 타입과 ID로 가격 정보를 배열 형태로 반환하는 함수
CoachShopDataLogic:DataSync -- 서버에서 클라이언트로 상점 데이터를 동기화하는 함수
CoachShopDataLogic:HandleUserEnterEvent -- 유저 입장 시 상점 데이터를 동기화하고 UI를 초기화하는 핸들러
CoachShopManager:OnBeginPlay -- 월드코인 구매 결과 함수 연결
UI_CoachShopList:OnBeginPlay -- 코스트 필터의 목록 UI , 버튼 이벤트 연결하기
UI_CoachShopList:Sort -- func: 코치 목록 id가 담긴 테이블을 코스트 오름차순/내림차순으로 정렬하는 함수
UI_CoachShopList:OnClick_OwnCoachVisible -- func: 코치 상점의 필터 버튼 클릭시 보유한 코치도 함께 보이도록 요청하는 함수
UI_CoachShopList:OnClick_OwnMasterCoachVisible -- func: 마스터 코치 상점의 필터 버튼 클릭시 구매 가능한 마스터 코치만 보이도록 요청 하는 함수
UI_CoachShopList:HandleButtonClickEvent -- 상점 닫기 버튼 클릭
UI_CoachShopList:HandleButtonClickEvent2 -- 코치 영입 상점 카테고리 버튼 클릭
UI_CoachShopList:HandleButtonClickEvent3 -- 코치 상점 카테고리 버튼 클릭
UI_CoachShopList:HandleButtonClickEvent4 -- 마스터 코치 상점 카테고리 버튼 클릭
UI_CoachShopList:HandleButtonClickEvent5 -- 코치 상점의 필터 버튼 클릭
UI_CoachShopList:HandleButtonClickEvent8 -- 마스터 상점의 필터 버튼 클릭
UI_CoachShopList:HandleButtonClickEvent6 -- 코스트 필터 버튼 클릭
UI_CoachShopList:HandleButtonClickEvent7 -- 정렬 버튼 클릭
UI_CoachShopPopUp:UIClose_Popup -- 상점 팝업 UI 닫기
UI_CoachShopPopUp:Popup_CompletePurchaseInitailize -- 구매 완료 팝업
UI_CoachShopPopUp:HandleButtonClickEvent -- 상점 팝업 UI 닫기
UI_CoachShopPopUp:HandleButtonClickEvent3 -- 상점 팝업 UI 닫기
UI_CoachShopPopUp:HandleButtonClickEvent2 -- 월드코인 구매 버튼 클릭
UI_CoachShopPopUp:HandleButtonClickEvent4 -- 로얄 시럽 구매 버튼 클릭
UI_CoachShopPopUp:HandleButtonClickEvent5 -- 상품 정보 툴팁 버튼 클릭
UI_CoachShopService:CheckHaveRoyalSyrup -- 시럽 보유 여부 판단
UI_GachaShopService:RefreshGachaShopUI -- 가챠 상점을 엽니다
UI_GachaShopService:OnOffShopUI -- 가챠 상점 오픈
UI_GachaShopService:RefreshPriceUI -- 가격 표시, 현재 유저가 갖고 있는 재화량에 따라 가격 폰트색 변경
UI_GachaShopService:SetProbabilityData -- 확률 정보 표시 : 서버에서 테이블 받아서 UI로 데이터 보냄
UI_GachaShopService:SendToUIChanceTable -- 서버에서 받은 확률 데이터를 UI에 표시하는 함수
UI_GachaShopService:HandleButtonClickEvent2 -- 가챠 상점 열기 버튼 클릭 이벤트 핸들러
UI_GachaShopService:HandleButtonClickEvent -- 가챠 상점 닫기 버튼 클릭 이벤트 핸들러
UI_GachaShopService:HandleButtonClickEvent3 -- 1회 가챠 구매 버튼 클릭 이벤트 핸들러
UI_GachaShopService:HandleButtonClickEvent4 -- 10회 연속 가챠 구매 버튼 클릭 이벤트 핸들러
UI_GachaShopService:HandleButtonClickEvent5 -- 가챠 확률 테이블 열기 버튼 클릭 이벤트 핸들러
UI_GachaShopService:HandleButtonClickEvent6 -- 가챠 확률 테이블 닫기 버튼 클릭 이벤트 핸들러
UI_GachaShopService:HandleButtonClickEvent7 -- 1회 가챠 월드코인 구매 버튼 클릭 이벤트 핸들러 (미구현)
UI_GachaShopService:HandleButtonClickEvent8 -- 10회 연속 가챠 월드코인 구매 버튼 클릭 이벤트 핸들러 (미구현)
UI_Goods:ShowTooltip -- 마우스 호버 시 코치 정보 툴팁을 표시하거나 숨기는 함수
UI_Goods:HandleButtonClickEvent -- 상품 클릭 시 구매 조건을 확인하고 구매 프로세스를 시작하는 핸들러
UI_Goods:HandleButtonStateChangeEvent -- 버튼 상태 변화 시 툴팁 표시를 제어하는 핸들러
DailyMissionComponent:OnLoadData -- DB에서 일일 미션 관련 데이터를 불러왔을 때 실행합니다.
DailyMissionComponent:InitDailyMission -- 매일 UTC 0시 기준으로 실행되는 함수입니다.
DailyMissionComponent:RefreshMission_Check -- 클라이언트에서 새로고침을 요청할 때 호출합니다.
DailyMissionComponent:RefreshMission -- missionIndex 슬롯의 미션을 변경합니다. 변경할 때, 진행도도 초기화됩니다.
DailyMissionComponent:AddDailyMissionProgress -- 특정 상황마다 호출하여, 일일 미션의 진행도를 변경합니다.
DailyMissionComponent:ReceiveReward -- 검증
DailyMissionComponent:ReceiveBonusReward -- 보너스 포인트에 따라 단계별 보상을 지급하는 함수
DailyMissionComponent:OnSyncProperty -- 서버에서 동기화된 데이터에 따라 UI를 업데이트하는 함수
DailyMissionComponent:SetRedDot -- 레드닷 조건을 검사하여, 활성화합니다.
DailyMissionLogic:OnBeginPlay -- 게임 시작 시 일일 미션 데이터셋을 로드하는 초기화 함수
DailyMissionLogic:LoadDataSet -- 데이터셋에서 일일 미션 정보를 로드하여 내부 테이블에 저장하는 함수
DailyMissionLogic:UI_RefreshMissionList -- 일일 미션 목록 UI를 새로고침하는 함수
DailyMissionLogic:UI_RefreshPointArea -- 보너스 포인트 영역 UI를 새로고침하는 함수
DailyMissionLogic:ShowUI_RefreshCheckPopup -- 미션 새로고침 확인 팝업을 표시하는 함수
DailyMissionLogic:HandleButtonClickEvent3 -- 보너스 보상 수령 버튼 클릭 이벤트 핸들러
DailyMissionLogic:HandleButtonClickEvent4 -- 미션 새로고침 확인 버튼 클릭 이벤트 핸들러
DailyMissionLogic:HandleButtonClickEvent5 -- '다시 묻지 않기' 체크박스 토글 버튼 클릭 이벤트 핸들러
UI_DailyMisison_RefreshButton:HandleButtonClickEvent -- 일일 미션 새로고침 버튼 클릭 이벤트 핸들러
UI_DailyMission_Reward:HandleUITouchEnterEvent -- 보상 아이콘에 마우스 진입 시 툴팁 표시 이벤트 핸들러
UI_DailyMission_Reward:HandleUITouchExitEvent -- 보상 아이콘에서 마우스 나갈 시 툴팁 숨김 이벤트 핸들러
UI_DailyMission_RewardReceiveButton:HandleButtonClickEvent -- 일일 미션 보상 수령 버튼 클릭 이벤트 핸들러
UI_DailyMission_Slot:Initialization -- UI 엔티티들을 초기화하는 함수
UI_DailyMission_Slot:RefreshUI -- 일일 미션 슬롯 UI를 새로고침하는 함수
DictionaryFavoriteListManager:Initialize -- 모든 즐겨찾기 UI를 초기화
DictionaryFavoriteListManager:Update_FavoriteUI -- 즐겨찾기 패널을 업데이트합니다.
DictionaryFavoriteListManager:Update_EnableSynergy -- 캐릭터 즐겨찾기가 업데이트 될 때 호출
DictionaryFavoriteListManager:RefreshUI_SynergyList -- UI에 반영
DictionaryFavoriteListManager:GetSynergyList -- 계산된 시너지 목록 반환
DictionaryFavoriteListManager:IsSettedFave_Char -- 해당 캐릭터가 즐겨찾기에 등록되어 있는지 확인
DictionaryFavoriteListManager:IsSettedFave_Item -- 해당 아이템이 즐겨찾기에 등록되어 있는지 확인
DictionaryFavoriteListManager:IsSettedFave_Rune -- 해당 룬카드가 즐겨찾기에 등록되어 있는지 확인
DictionaryFavoriteListManager:Initialize_CharList -- 캐릭터 즐겨찾기 목록 초기화 및 UI 리셋
DictionaryFavoriteListManager:Initialize_ItemList -- 아이템 즐겨찾기 목록 초기화 및 UI 리셋
DictionaryFavoriteListManager:Initialize_RuneList -- 룬카드 즐겨찾기 목록 초기화 및 UI 리셋
DictionaryFavoriteListManager:Initialize_SynergyList -- 시너지 목록 초기화 (미구현)
DictionaryFavoriteListManager:HandleButtonClickEvent -- 즐겨찾기 초기화 버튼 클릭 처리
DictionaryFavoriteListManager:HandleDictionaryFavoriteEvent -- 즐겨찾기 토글 이벤트 처리 및 목록 갱신
DictionaryFavoriteListManager:HandleButtonClickEvent2 -- 버튼을 누르면 지금 현재 플레이어가 가지고 있는 유닛과 룬 카드를 즐겨찾기에 자동 등록한다.
DictionaryFavoriteListManager:HandleButtonClickEvent3 -- 시너지 목록 페이지 넘기기 버튼 클릭 처리
DictionaryManager:OnBeginPlay -- 사전 시스템 초기화 및 시즌 목록 설정
DictionaryManager:OnOpenDictionary -- UI를 눌러 사전을 열 때 실행합니다.
DictionaryManager:Initialize -- 사전 카테고리 페이지 인덱스 초기화 및 즐겨찾기 UI 갱신
DictionaryManager:OnSelectCategory_1st -- 1차 카테고리를 선택하고, 그에 따라 하위 내용을 변경하는 함수입니다.
DictionaryManager:OnSelectCategory_2nd -- 2차 카테고리를 선택하고, 그에 따라 하위 내용을 변경하는 함수입니다.
DictionaryManager:RefreshCategory_3rd -- 선택한 1, 2차 카테고리 및 시즌에 따라 3차 카테고리 목록을 새로고침하는 함수입니다.
DictionaryManager:OnSelectCategory_3rd -- 3차 카테고리를 선택하고, 그에 따라 하위 내용을 변경하는 함수입니다.
DictionaryManager:UpdateUI_CharList -- 사전 > 캐릭터 목록을 새로고침합니다.
DictionaryManager:Character_Favorite -- 캐릭터 즐겨찾기 토글 이벤트 전송
DictionaryManager:Item_Favorite -- 아이템 즐겨찾기 토글 이벤트 전송
DictionaryManager:RuneCard_Favorite -- 룬카드 즐겨찾기 토글 이벤트 전송
DictionaryManager:UpdateUI_ItemList -- 사전 > 아이템 목록을 새로고침합니다.
DictionaryManager:UpdateUI_RuneCardList -- 사전 > 룬 카드 목록을 새로고침합니다.
DictionaryManager:UpdateUI_GameRulesList -- 게임 규칙 카테고리에 따른 규칙 텍스트 및 이미지 UI 업데이트
DictionaryManager:SetUI_SeasonDropDownList -- 시즌 드롭다운 목록 UI 생성 및 설정
DictionaryManager:HandleTabChangedEvent -- 1차 카테고리 탭 변경 시 처리
DictionaryManager:HandleTabChangedEvent2 -- 2차 카테고리 탭 변경 시 처리
DictionaryManager:HandleTabChangedEvent4 -- 3차 카테고리 탭 변경 시 처리
DictionaryManager:HandleButtonClickEvent4 -- 사전 닫기 버튼 클릭 시 즐겨찾기 데이터 저장 후 UI 비활성화
DictionaryManager:HandleButtonClickEvent -- 시즌 변경 드롭다운을 (비)활성화 합니다.
DictionaryManager:HandleTabChangedEvent3 -- 시즌 선택 변경 시 사전 내용 갱신 및 UI 업데이트
UI_CharDictionaryInfo:UpdateInfo -- 캐릭터 상세 정보 UI 전체 업데이트 (스탯, 시너지, 스킬 등)
UI_dictionary_CharacterBT:Initialize -- 공란으로..
UI_dictionary_CharacterBT:UpdateIcon -- 캐릭터 아이콘 및 배경색 업데이트, 즐겨찾기 상태 반영
UI_dictionary_CharacterBT:HandleDictionaryFavoriteEvent -- 즐겨찾기 변경 이벤트 수신 시 마크 표시 상태 갱신
UI_dictionary_CharacterBT:HandleUITouchDownEvent -- 마우스 클릭 시 즐겨찾기 토글 처리
UI_dictionary_CharacterBT:HandleUITouchEnterEvent -- 마우스 호버 시 캐릭터 정보 패널 표시 및 아웃라인 활성화
UI_dictionary_CharacterBT:HandleUITouchExitEvent -- 마우스 호버 해제 시 정보 패널 숨김 및 아웃라인 비활성화
UI_Dictionary_ItemBT:Initialize -- 아이템 버튼 UI 컴포넌트 초기화
UI_Dictionary_ItemBT:UpdateIcon -- 아이템 아이콘 및 배경 업데이트, 즐겨찾기 상태 반영
UI_Dictionary_ItemBT:HandleDictionaryFavoriteEvent -- 아이템 즐겨찾기 변경 이벤트 수신 시 마크 상태 갱신
UI_Dictionary_ItemBT:HandleUITouchDownEvent -- 마우스 클릭 시 아이템 즐겨찾기 토글 처리
UI_Dictionary_ItemBT:HandleUITouchEnterEvent -- 마우스 호버 시 아이템 정보 패널 표시 및 아웃라인 활성화
UI_Dictionary_ItemBT:HandleUITouchExitEvent -- 마우스 호버 해제 시 정보 패널 숨김 및 아웃라인 비활성화
UI_dictionary_OpenBT:HandleButtonClickEvent -- 사전 열기 버튼 클릭 처리
UI_dictionary_RuneCard:Initialize -- 룬카드 버튼 UI 컴포넌트 초기화
UI_dictionary_RuneCard:UpdateCard -- 룬카드 이미지 및 배경색 업데이트, 즐겨찾기 상태 반영
UI_dictionary_RuneCard:HandleDictionaryFavoriteEvent -- 룬카드 즐겨찾기 변경 이벤트 수신 시 마크 상태 갱신
UI_dictionary_RuneCard:HandleUITouchDownEvent -- 마우스 클릭 시 룬카드 즐겨찾기 토글 처리
UI_dictionary_RuneCard:HandleUITouchEnterEvent -- 마우스 호버 시 룬카드 정보 패널 표시 및 아웃라인 활성화
UI_dictionary_RuneCard:HandleUITouchExitEvent -- 마우스 호버 해제 시 정보 패널 숨김 및 아웃라인 비활성화
UI_dictionary_SynergyBT:SynergyButtonInitialize -- 시너지 버튼 초기화 및 아이콘, 캐릭터 목록 설정
UI_dictionary_SynergyBT:FavoriteSynergy -- 즐겨찾기 시너지 아이콘만 간단히 업데이트 (임시 구현)
UI_dictionary_SynergyBT:HandleButtonClickEvent -- 시너지 버튼 클릭 시 상세 정보 패널 표시
UI_FavoriteSynergy:Initialize -- 즐겨찾기 시너지 UI 컴포넌트 초기화
UI_FavoriteSynergy:UpdateFaveSynergy -- 즐겨찾기 시너지 UI 업데이트 (아이콘, 활성화 단계, 인원수)
UI_FavoriteSynergy:GetSynergyCountText -- 전직교관부터 판단
UI_FavoriteSynergy:HandleUITouchEnterEvent -- 마우스 호버 시 시너지 이름 툴팁 표시
UI_FavoriteSynergy:HandleUITouchExitEvent -- 마우스 호버 해제 시 툴팁 숨김
UI_ItemDictionaryInfo:OnInitialize -- 아이템 정보 패널 초기화
UI_ItemDictionaryInfo:UpdateUI -- 아이템 정보 UI 전체 업데이트 및 타입별 확장 정보 표시
UI_ItemDictionaryInfo:GetItemStatusText -- 아이템 스탯 정보를 텍스트로 포맷팅하여 반환
UI_ItemDictionaryInfo:UpdateUI_Extra_Recipes -- 재료 아이템 화면에서 / 이 재료 아이템으로 만들 수 있는 모든 레시피를 보여줍니다.
UI_ItemDictionaryInfo:UpdateUI_Extra_Recipe -- 완성 아이템 화면에서 / 이 아이템의 조합식을 보여줍니다.
UI_ItemDictionaryInfo:ItemList_Update -- 박스 아이템의 획득 가능한 아이템 목록 UI 업데이트
UI_ItemDictionaryInfo:SetItemList_intheBox -- 해당 아이템이 '아이템 박스'인가?
UI_LinkedSynergy_BT:UpdateButton -- 연관 시너지 버튼 아이콘 및 이름 업데이트
UI_LinkedSynergy_BT:Init -- 연관 시너지 버튼 UI 컴포넌트 초기화
UI_RuneCardDictionaryInfo:UpdateInfo -- 룬카드 상세 정보 UI 업데이트 (이름, 등급, 설명 등)
UI_SynergyDictionaryInfo:UpdateInfo -- 시너지 상세 정보 UI 업데이트 (아이콘, 설명, 연관 시너지 등)
UI_SynergyDictionaryInfo:LinkedCharacterList -- 연관 시너지와 현재 시너지를 공유하는 캐릭터 목록 반환
UI_SynergyDictionaryList:CreateSynergyList -- 시너지 목록 GridView 생성 및 초기 정보 표시
DictionaryDataManager:DataSetInitialize -- 모든 딕셔너리 데이터를 초기화하고 로드 완료 상태로 설정
DictionaryDataManager:SetCharacterData -- 캐릭터 데이터를 세팅하는 함수
DictionaryDataManager:SortCharacterKeyIDs -- 캐릭터 ID를 코스트 기준으로 정렬하여 반환
DictionaryDataManager:SetSynergyData -- 시너지 데이터를 세팅합니다.
DictionaryDataManager:SetItemData -- 아이템 상태, 효과, 시즌별 정보를 로드하여 아이템 딕셔너리 구성
DictionaryDataManager:SetStatusEffectData -- 상태 효과 데이터를 로드하여 상태 효과 딕셔너리 구성
DictionaryDataManager:SetRuneCardData -- 룬 카드 정보와 시즌별 데이터를 로드하여 룬 카드 딕셔너리 구성
DictionaryDataManager:GetSortedCharacterIDList -- 시즌과 시너지 아이디를 입력하면, 해당하는 캐릭터 아이디 목록을 정렬된 상태로 반환합니다.
DictionaryDataManager:GetItemIDList -- 시즌과 시너지 아이디를 입력하면, 해당하는 아이템 아이디 목록을 정렬된 상태로 반환합니다.
DictionaryDataManager:GetRuneIDList -- 시즌과 시너지 아이디를 입력하면, 해당하는 룬 카드 아이디 목록을 정렬된 상태로 반환합니다.
DictionaryDataManager:SetAllGameRulesData -- 게임 규칙 텍스트 데이터를 불러오는 함수입니다.
UIToggle:OnClick -- 토글 버튼 클릭 시 상태를 반전시키는 핸들러
UIToggle:SetToggleGroup -- 토글이 속할 그룹을 설정하고 그룹에 등록
UIToggle:SetIsOn -- 토글 상태를 설정하고 콜백을 호출
UIToggle:Set -- 토글 상태를 내부적으로 설정하고 그룹 및 콜백 처리
UIToggle:SetIsOnWithoutNotify -- 콜백 없이 토글 상태만 설정
UIToggle:OnInitialize -- 토글 컬포넌트 초기화 및 버튼 이벤트 연결
UIToggle:OnBeginPlay -- 게임 시작 시 토글의 시각적 효과를 초기화
UIToggle:PlayEffect -- 토글 상태에 따른 시각적 효과를 적용
UIToggleGroup:RegisterToggle -- 토글을 그룹에 등록
UIToggleGroup:UnRegisterToggle -- 토글을 그룹에서 제거
UIToggleGroup:NotifyToggleOn -- 특정 토글이 활성화될 때 다른 토글들을 비활성화
UIToggleGroup:AnyToggleOn -- 그룹 내에 활성화된 토글이 있는지 확인
UIToggleGroup:Contains -- 토글이 그룹에 속해있는지 확인하고 인덱스 반환
UIToggleGroup:OnBeginPlay -- 게임 시작 시 토글 그룹의 유효한 상태를 보장
UIToggleGroup:EnsureValidState -- 토글 그룹의 상태를 검증하고 필요시 수정
UIToggleGroup:ActiveToggles -- 활성화된 모든 토글들의 목록을 반환
UI_GameResult:SetUI_GameResultPanel -- 게임 결과 패널의 모든 UI 요소를 설정하고 표시
UI_GameResult:SetUI_LevelInfo_inGameResultPanel -- 게임 결과 패널에서 레벨과 경험치 정보를 설정
UI_GameResult:PlayAnim_EXP -- 경험치 획득 애니메이션을 재생합니다.
ExtendAvatarStateAnimationComponent:ReceiveStateChangeEvent -- 아바타 렌더러가 활성화된 경우에만 상태 변경 이벤트를 처리
ExtendPlayerControllerComponent:ActionAttack -- 변신 상태에서 공격 가능 여부를 확인하고 공격 실행
ExtendPlayerControllerComponent:ActionCrouch -- 변신 중이 아니면 웅크리기 동작 실행
ExtendPlayerControllerComponent:ActionJump -- 변신 상태에서 점프 가능 여부를 확인하고 점프 실행
ExtendPlayerControllerComponent:OnMapEnter -- 로비 진입 시 플레이어 위치를 랜덤하게 설정
NewPlayerAvatarComponent:StateChange -- 변신 아바타의 상태를 변경하고 해당 애니메이션을 적용
NewPlayerAvatarComponent:HandleSpriteAnimPlayerEndFrameEvent -- 애니메이션 종료 시 공격 상태에서 현재 상태로 전환
NewPlayerAvatarComponent:HandleSpriteAnimPlayerStartEvent -- 애니메이션 시작 시 공격 상태에서만 플레이어 컨트롤러를 비활성화
PlayerAvatarChangeCompoenent:ClientInitialize -- 클라이언트에서 변신 아바타와 이펙트 엔티티를 초기화
PlayerAvatarChangeCompoenent:AvatarChange -- 변신 상태 스위칭
PlayerAvatarChangeCompoenent:False_change -- 변신 스위칭이 아닌 완전 해제만 다룰 때 사용하는 함수입니다.
PlayerAvatarChangeCompoenent:SetPossibleAction -- 변신 상태에서 플레이어의 행동 가능 여부와 이동속도를 설정
PlayerAvatarChangeCompoenent:ManualAttackEnd -- 수동으로 공격 상태를 종료하고 대기 상태로 전환
PlayerAvatarChangeCompoenent:AvatarFlip_forServer -- 변신 아바타의 좌우 반전을 플레이어의 방향에 맞춰 설정
PlayerAvatarChangeCompoenent:SoundPlay_ForMap -- 변신 시 사운드를 재생하고 이펙트를 활성화
PlayerAvatarChangeCompoenent:EffectPlay_ForServer -- 서버에서 변신 이펙트를 활성화
PlayerAvatarChangeCompoenent:HandleKeyHoldEvent -- 키 홀드 시 변신 아바타의 방향을 플레이어 이동 방향에 맞춰 조정
PlayerAvatarChangeCompoenent:HandleStateChangeEvent -- 플레이어 상태 변화를 감지하여 변신 아바타의 상태를 동기화
PlayerAvatarChangeCompoenent:HandleKeyDownEvent -- 키 다운 시 변신 아바타의 방향을 플레이어 이동 방향에 맞춰 조정
PlayerAvatarChangeCompoenent:HandleEntityMapChangedEvent -- 맵 변경 시 로비로 이동한 경우 다른 유저들의 변신 상태를 초기화
temp_Effect_Bomb:EnableFalse_forServer -- 서버에서 스프라이트 렌더러를 비활성화
temp_Effect_Bomb:HandleSpriteAnimPlayerEndFrameEvent -- 애니메이션 종료 시 이팩트를 비활성화하는 핸들러
PlayerCollectionDataComponent:InitializeCollection -- 컴렉션 데이터 컴포넌트 초기화
PlayerCollectionDataComponent:InitializeCharacterCollectionData -- (각 시즌에서) 최초 실행 시 생성하는 함수
PlayerCollectionDataComponent:InitializeSynergyCollectionData -- (각 시즌에서) 최초 실행 시 생성하는 함수?
PlayerCollectionDataComponent:UpdateCharacterCollectionData -- 게임 중 updateData를 받은 만큼만 업데이트. 데이터를 받고 해당 변수를 수정한 뒤에 데이터 저장을 합니다.
PlayerCollectionDataComponent:GetGameOverUnitSet -- 게임 오버 되었을 때 유닛 데이터 받아와서 걸러내는 용 (캐릭터유닛)
PlayerCollectionDataComponent:UpdateSynergyCollectionData -- 시너지 컴렉션 데이터를 업데이트하고 데이터베이스에 저장 후 UI 이벤트 발송
PlayerCollectionDataComponent:GetGameOverSynergySet -- 게임 오버 되었을 때 유닛 데이터 받아와서 걸러내는 용 (시너지)
PlayerCollectionDataComponent:Get_CharMaxCount -- 딕셔너리 데이터 구조체 부르기
PlayerCollectionDataComponent:Get_SynergyMaxCount -- 딕셔너리 데이터 구조체 부르기
PlayerCollectionDataComponent:Get_nowCharCount -- 딕셔너리 데이터 구조체 부르기
PlayerCollectionDataComponent:Get_nowSynergyCount -- 딕셔너리 데이터 구조체 부르기
PlayerCollectionDataComponent:UpdateUI -- 컴렉션 UI를 업데이트하고 새로운 수집 알림 레드닷 표시
PlayerCollectionDataComponent:Check_AvaliableChange -- 캐릭터가 4레벨 이상인지 확인하고 아바타 변경 가능 여부 반환
UI_CollectionCharacterCard:Initialize -- 엔티티 셋
UI_CollectionCharacterCard:Set_CollectLevel -- 도감의 수집 레벨은 올라가기만 하고 내려갈 일은 없으므로
UI_CollectionCharacterCard:Set_Star -- 수집 레벨에 따라 별 표시 개수와 위치 설정
UI_CollectionCharacterCard:Set_NameTag -- 수집 여부에 따라 캐릭터 이름 또는 ??? 표시
UI_CollectionCharacterCard:Set_CardImage -- 수집 레벨에 따라 카드 이미지 색상과 배경 매테리얼 설정
UI_CollectionCharacterCard:Set_PlatinumCard -- 카드 배경, 아웃라인 효과
UI_CollectionCharacterCard:HandleButtonClickEvent -- 캐릭터 카드 클릭 시 캐릭터 상세 정보 UI 표시
UI_CollectionCharacterCard:HandleCollectionUpdateEvent -- 컴렉션 데이터 업데이트 시 카드 재초기화
UI_CollectionCharacterInfo:SetInfo -- 캐릭터의 수집 레벨과 ID를 바탕으로 캐릭터 정보 UI를 설정
UI_CollectionCharacterInfo:SetInfo_OnlyCharID -- 캐릭터 ID만으로 컴렉션 데이터를 찾아 정보 UI 설정
UI_CollectionCharacterInfo:HandleButtonClickEvent -- 아바타 변경 버튼 클릭 시 캐릭터 변신 및 쿨타임 처리
UI_CollectionManager:OnBeginPlay -- 컬렉션 배경 매테리얼 초기화 및 첫 오픈 상태 설정
UI_CollectionManager:CreateCharColList_NewGrid -- 지정된 시즌의 캐릭터 컬렉션 목록을 GridView로 생성
UI_CollectionManager:CreateSynergyColList -- 지정된 시즌의 시너지 컬렉션 목록을 생성하고 UI에 표시
UI_CollectionManager:OnEnable -- 카메라 줌인아웃
UI_CollectionManager:Set_RateUI -- 선택된 컬렉션 타입에 따라 수집률 UI를 설정하고 애니메이션 표시
UI_CollectionManager:CloseUI -- 컴렉션 UI를 닫고 카메라 줄 리셋
UI_CollectionManager:CharList_OnFilter -- 4단계 이상 캐릭터만 필터링하여 표시
UI_CollectionManager:ChangeSeason -- 선택된 시즌으로 컴렉션 목록을 변경하고 UI 갱신
UI_CollectionManager:InitSeasonDropdown -- 시즌 드롭다운 Initialization
UI_CollectionManager:OpenNewSeasonTab -- 해금된 시즌들을 확인하여 드롭다운에 시즌 버튼 생성
UI_CollectionManager:HandleButtonClickEvent -- 캐릭터 컴렉션 탭 버튼 클릭 처리
UI_CollectionManager:HandleButtonClickEvent2 -- 시너지 컴렉션 탭 버튼 클릭 처리
UI_CollectionManager:HandleButtonClickEvent3 -- 닫기 버튼을 눌렀을 때 드롭다운을 (비)활성화합니다.
UI_CollectionManager:HandleButtonClickEvent4 -- 컴렉션 새로고침 버튼 클릭 처리
UI_CollectionManager:HandleButtonClickEvent5 -- 4단계 이상 캐릭터 필터 체크박스 토글 처리
UI_CollectionManager:HandleButtonClickEvent6 -- 시즌 버튼을 눌렀을 때 드롭다운을 (비)활성화합니다.
UI_CollectionManager:HandleTabChangedEvent -- 시즌 드롭다운에서 시즌 변경 시 해당 시즌으로 컴렉션 바꿀 처리
UI_CollectionSynergyBC:Initialize -- 시너지 컬렉션 카드를 초기화하고 모든 단계 배지 설정
UI_CollectionSynergyBC:HandleCollectionUpdateEvent -- 시너지 컬렉션 데이터 업데이트 시 해당 시너지의 등급 갱신
PlayerTouch:HandleTouchEvent -- 플레이어 터치 이벤트 핸들러 (현재 비활성화)
UI_Profile:RequestData -- 지정된 사용자의 프로필 데이터를 요청하고 UI에 표시할 정보를 설정
UI_Profile:OnOpenUI -- 프로필 UI를 열고 로딩 상태를 초기화하며 데이터 로딩 완료를 감시
UI_Profile:SetData_DefaultProfile -- 사용자의 기본 프로필 정보(칭호, 레벨, 닉네임, 아바타)를 UI에 설정
UI_Profile:SetData_IsPublic -- 프로필 기록과 전적의 공개/비공개 설정을 UI에 반영
UI_Profile:SetData_Record -- 플레이어의 기록 탭 데이터(최고 티어, 랭킹, 플레이 통계, 수집률)를 설정
UI_Profile:SetData_History -- 플레이어의 게임 전적 데이터(승패, 모드, 라운드, 유닛 정보 등)를 설정
UI_Profile:SetUI_Record -- 기록 탭의 UI 요소들을 데이터에 맞춰 갱신하고 표시
UI_Profile:SetUI_History -- 전적 탭의 게임 기록 목록을 UI에 갱신하고 표시
UI_Profile:SetUI_History_GameDetail -- 선택한 게임의 상세 정보(라운드, 하트, 유닛, 시너지 등)를 UI에 표시
UI_Profile:GetSortedUsedSynergyList -- 사용한 시너지를 우선순위(단계, 개수)에 따라 정렬하여 반환
UI_Profile:RequestChangePublicInfo -- 클라이언트에서 요청한 프로필 공개/비공개 설정을 서버에 저장
UI_Profile:HandlePlayerTouchEvent -- 플레이어를 터치했을 때 프로필 보기 버튼을 표시
UI_Profile:HandleButtonClickEvent -- 프로필 보기 버튼 클릭 시 프로필 UI를 열고 데이터 요청
UI_Profile:HandleTabChangedEvent -- 프로필 탭(기록/전적) 변경 시 해당 UI를 갱신하고 탭 스타일 업데이트
UI_Profile:HandleTabChangedEvent2 -- 게임 기록 목록에서 특정 게임 선택 시 상세 정보 표시 및 선택 스타일 업데이트
UI_Profile:HandleButtonClickEvent2 -- 기록 공개/비공개 토글 버튼 클릭 처리
UI_Profile:HandleButtonClickEvent3 -- 전적 공개/비공개 토글 버튼 클릭 처리
UI_Profile:HandleButtonClickEvent4 -- 내 프로필 보기 버튼 클릭 시 자신의 프로필 UI 열기
UI_Profile:HandleButtonClickEvent5 -- 칭호 설정 버튼 클릭 시 칭호 설정 UI 열기
Ranking_UILogic:OnBeginPlay -- 게임 시작 시 시즌 시간 UI 설정 및 랭킹 데이터 초기화
Ranking_UILogic:OnUpdate -- 매 프레임마다 시간을 업데이트하고 주기적으로 랭킹 데이터 갱신
Ranking_UILogic:SetUI_NextOrdinalTime -- Lobby HUD의 '시즌 종료까지 남은 시간'을 갱신합니다.
Ranking_UILogic:SetRankingInfo -- 랭킹 정보를 설정하는 메서드 (현재 미구현)
Ranking_UILogic:HandleButtonStateChangeEvent -- 시즌 정보 툴팁 버튼 호버 상태 변경 시 툴팁 표시/숨김 처리
UI_RewardPopup:HandleButtonClickEvent -- 보상 팝업 닫기 버튼 클릭 시 팝업 숨김 및 보상 아이템들 비활성화
UI_Reward_inPopup:UpdateReward -- 보상 아이템의 ID와 수량을 설정하고 UI 업데이트
UI_Reward_inPopup:HandleUITouchExitEvent -- 툴팁 엔티티 켜기
TitleLogic:getOtherUserTitle -- 다른 사용자의 칭호 데이터를 데이터베이스에서 가져와 클라이언트에 설정
TitleLogic:setTitle -- 칭호 ID를 바탕으로 칭호 텍스트를 생성하고 표시
TitleManager:TitleSet -- 칭호 요소를 변경하고, 칭호를 업데이트합니다.
TitleManager:MakeTitleEntity -- 칭호 엔티티가 없을 때, 칭호 엔티티를 만듭니다.
TitleManager:TitleSet_Client -- 클라이언트에서 칭호 엔티티를 설정하고 UI에 반영
TitleManager:Random_Title -- 보유중인 칭호 요소 중에서 무작위로 선정하여 칭호를 설정합니다.
TitleManager:TitleDataInitialize -- 첫 접속 시 칭호 데이터 테이블을 초기화하는 함수입니다.
TitleManager:TitleDataUpdate -- 현재 칭호데이터를 업데이트하는 함수입니다.
TitleManager:GetTitle -- 칭호 요소를 획득하는 함수입니다.
TitleManager:DataSyncToClient -- 서버에서 전송된 칭호 데이터를 클라이언트에 동기화
TitleManager:GetAllTitle -- 모든 칭호 요소를 획득하는 함수입니다. (치트용 코드)
TitleManager:AddtoRedDotTable -- 새로 획득한 칭호 요소를 레드닷 표시 목록에 추가
TitleManager:InitializeTitle -- 칭호 시스템을 초기화하고 엔티티 생성
TitleManager:OnMapEnter -- 맵 진입 시 호출되는 이벤트 핸들러 (현재 비활성화)
TitleManager:CheckTitleAvaliable -- -칭호 요소를 실제로 서버에서 갖고있는지 체크하고, 갖고있다면 타이틀을 변경해줍니다.
CooldownType:OnBeginPlay -- 게임 시작 시 쿨다운 데이터 테이블을 초기화
KinematicLayerOrderController:HandleChangedMovementInputEvent -- -- Parameters
PlayerCooldownComponent:CheckAndSetCooldown -- 쿨다운 상태를 확인하고 쿨다운이 없으면 새로 설정
PlayerCooldownComponent:SetCooldown -- 지정된 타입에 대해 쿨다운 시간을 설정
PlayerCooldownComponent:CheckCooldown -- 지정된 타입의 쿨다운 상태만 확인 (설정하지 않음)
PlayerCooldownComponent:OnDestroy -- 엔터티 파괴 시 동적 맵 시스템에서 해당 플레이어의 맵을 제거
PlayerLevelLogic:GetRewardEXPAmount -- 게임 모드와 난이도에 따라 획득하는 경험치 량을 return 하는 함수 (클리어 기준)
PlayerLevelLogic:IsLevelUpCondition -- 현재 레벨과 경험치 보유량을 입력하면, 레벨 업 가능한 지 여부를 return합니다.
PlayerLevelLogic:GetRequiredEXP -- targetLevel로 레벨업 하기 위해 필요한 경험치량을 return 합니다. 잘못된 값을 입력받은 경우 -1을 return 합니다.
PlayerLevelLogic:SetUI_LevelUpPopup -- 레벨업 팝업의 내용을 변경합니다. ui를 enable시키진 않습니다. (별도 처리 필요)
PlayerLevelLogic:EnableUI_LevelUpPopup -- 레벨 업 팝업을 활성화시킵니다. 활성화할 때, 1초에 걸쳐 서서히 등장하게 만듭니다.
PlayerLevelLogic:OnBeginPlay -- 게임 시작 시 레벨업 보상 리스트를 로드
PlayerLevelLogic:LoadRewardList -- 데이터 테이블에서 레벨업 보상 리스트를 로드하고 저장
GuideToRulesManager:OnBeginPlay -- 게임 시작 시 가이드 팝업과 게임 규칙 데이터셋을 초기화
GuideToRulesManager:InitGuideList -- 모든 가이드 팝업을 미시청 상태로 초기화
GuideToRulesManager:PopupWatched -- 특정 가이드 팝업을 시청했음을 기록
GuideToRulesManager:ActivatePopupMessage -- 가이드 팝업을 활성화합니다.
GuideToRulesManager:OffGuideList -- 가이드 팝업을 모두 본 상태로 변경하는 함수입니다.
GuideToRulesManager:HandleButtonClickEvent -- 게임 규칙 버튼 클릭 시 사전을 열고 해당 카테고리로 이동
GuideToRulesManager:HandleButtonClickEvent2 -- 팝업 닫기 버튼 클릭 시 시청 완료로 표시
GuideToRulesManager:HandleNotEnoughCoin -- 코인 부족 시 코인 관련 가이드 팝업을 표시
GuideToRulesManager:HandleRoundStart -- 라운드 시작 시 스테이지별 가이드 팝업을 표시
GuideToRulesManager:HandleBattleEnd -- 전투 종료 시 팀 파워 부족 상황에서 가이드 팝업을 표시
GuideToRulesManager:HandleBuyUnit -- 유닛 구매 시 배치 가이드나 비용 관련 가이드를 표시
GuideToRulesManager:HandleMergeUnit -- 유닛 합성 시 업그레이드 가이드를 표시
GuideToRulesManager:HandleBuyItem -- 아이템 구매 시 아이템 관련 가이드를 표시
GuideToRulesManager:HandleRerollCharacterShop -- 상점 리롤 시 리롤 관련 가이드를 표시
GuideToRulesManager:HandleBuyEXP -- 경험치 구매 시 팀 레벨 관련 가이드를 표시
GuideToRulesManager:HandleLevelUpTeam -- 팀 레벨업 시 팀 레벨 관련 가이드를 표시
GuideToRulesManager:HandlePlaceUnit -- 유닛 배치 시 시너지 관련 가이드를 표시
GuideToRulesManager:HandleBuyRuneCard -- 룬 카드 구매 시 룬 카드 관련 가이드를 표시
TutorialManager_New:TutorialInitialize -- 튜토리얼 시작 시 모든 제한 상태와 플래그들을 기본값으로 초기화
TutorialManager_New:CallAdviceMessage -- 지정된 ID의 튜토리얼 안내 메시지를 화면에 표시
TutorialManager_New:ReRollTest -- 튜토리얼에서 캐릭터 상점을 지정된 캐릭터들로 새로고침
TutorialManager_New:SetAllowFeature -- 튜토리얼 진행에 따라 특정 기능의 허용/제한 상태를 설정
TutorialManager_New:CheckIsRewardReceived -- 튜토리얼 완료 보상 수령 여부를 확인하고 미수령 시 보상을 지급
TutorialManager_New:SetRewardReceived -- 튜토리얼 완료 보상으로 시럽을 지급하고 수령 상태를 기록
TutorialManager_New:SetBattleStart -- 튜토리얼에서 전투 단계로 진행시키는 함수
TutorialManager_New:EnableRewardPopup -- 보상 팝업 UI를 활성화하고 받을 보상 목록을 표시
TutorialManager_New:SetDraggableCharID -- 현재 드래그 가능한 캐릭터 ID를 설정
TutorialManager_New:SetItemTargetCharID -- 아이템을 장착할 대상 캐릭터 ID를 설정
TutorialManager_New:SetCurrentTargetTile -- 튜토리얼에서 강조 표시할 타겟 타일을 지정하고 UI에 표시
TutorialManager_New:SyncSelectedTile -- 선택된 타겟 타일 정보를 서버에서 동기화
TutorialManager_New:SetTutorialRejected -- 플레이어가 튜토리얼을 스킵했음을 데이터에 기록
TutorialManager_New:ActivateTutoSelectForServer -- 튜토리얼을 거부하지 않은 플레이어에게 튜토리얼 선택 UI를 표시
TutorialManager_New:CallShowTile -- 지정된 캐릭터에 해당하는 대기 라인 타일을 강조 표시
TutorialManager_New:HandleRoundStart -- 라운드 시작 시 튜토리얼 스테이지별 상점 설정과 안내 메시지 표시
TutorialManager_New:HandlePlaceUnit -- 유닛 배치 시 튜토리얼 단계에 따른 안내 메시지와 타일 표시 처리
TutorialManager_New:HandleBuyUnit -- 캐릭터 구매 시 튜토리얼 진행 상황에 따른 안내 메시지 표시
TutorialManager_New:HandleBattleEnd -- 전투 종료 시 결과에 따른 안내 메시지 표시 및 플래그 초기화
TutorialManager_New:HandleMergeUnit -- 유닛 합성 시 레벨2 이상 유닛 개수를 확인하여 안내 메시지 표시
TutorialManager_New:HandleBuyItem -- 아이템 구매 시 튜토리얼 단계에 따른 안내 메시지 표시
TutorialManager_New:HandleEquipedItem -- 아이템 장착 시 특정 캐릭터와 아이템 조합에 따른 안내 메시지 표시
TutorialManager_New:HandleCombinationItem -- 아이템 조합 시 소모성 아이템을 추가하고 안내 메시지 표시
TutorialManager_New:HandleBuyRuneCard -- 룬 카드 구매 시 보유 개수에 따른 안내 메시지와 새로고침 기능 활성화
TutorialManager_New:HandleBattleOverTime -- 전투 시간 초과 시 처음 발생했을 때만 안내 메시지 표시
TutorialManager_New:HandleLevelUpTeam -- 팀 레벨업 시 특정 레벨에 도달했을 때 안내 메시지 표시
TutorialManager_New:HandleSellUnit -- 유닛 판매 시 특정 캐릭터 판매에 따른 기능 활성화와 안내 메시지 표시
TutorialManager_New:HandleUseConsumableItem -- 소모성 아이템 사용 시 특정 아이템에 따른 안내 메시지 표시
TutorialManager_New:HandleButtonClickEvent -- 튜토리얼 UI의 모든 요소를 비활성화하는 버튼 클릭 처리
TutorialManager_New:HandleButtonClickEvent2 -- 새로고침 기능을 비활성화하는 버튼 클릭 처리
TutorialManager_New:HandleKeyDownEvent -- 튜토리얼 중 키보드와 마우스 입력에 따른 상호작용 처리
TutorialManager_New:HandleButtonStateChangeEvent -- 버튼 호버 상태 변경 시 특정 조건에서 안내 메시지 표시
TutorialManager_New:HandleKeyDownEvent2 -- ESC 키 입력 시 특정 튜토리얼 상황에서 다음 단계로 진행
CursorPosManager:CheckHoverEntity -- 마우스 커서 위치의 엔터티를 확인하고 하이라이트 효과를 적용
CursorPosManager:HandleMouseMoveEvent -- 마우스 이동 시 커서 위치의 엔터티를 확인하고 하이라이트 처리
CursorPosManager:HandleKeyDownEvent -- 키 입력 시 마우스 클릭에 따른 유닛 정보 표시 및 플레이어 터치 이벤트 처리
UI_AlphaDesolve:DesolveToDisable -- UI를 서서히 투명화하여 비활성화
UI_AlphaDesolve:DesolveToEnable -- UI를 서서히 나타나게 하여 활성화
UI_AlphaDesolve:HandleButtonStateChangeEvent -- 버튼 상태 변화 시 피드백 메시지 표시 처리
UI_CameraZoomLogic:Zoom -- 로비에서 카메라 줌인/줌아웃을 토글하여 캐릭터를 확대/축소 표시
UI_DragMoverComponent:HandleUITouchDragEvent -- UI 터치 드래그 시 타겟 UI를 지정된 경계 내에서 이동
UI_FlyingUIEntity:OnUpdate -- UI 엔터티를 시작점에서 목적지까지 비행 애니메이션으로 이동
UI_GameResultTooltipEnabler:OnUpdate -- 마우스 호버 중일 때 툴팁 위치를 커서 위치에 맞춰 업데이트
UI_GameResultTooltipEnabler:HandleUITouchEnterEvent -- 마우스 진입 시 툴팁 메시지를 활성화
UI_GameResultTooltipEnabler:HandleUITouchExitEvent -- 마우스 벗어날 시 툴팁을 비활성화
UI_HideButtonComponent:InitHideState -- 숨김 상태를 초기화
UI_HideButtonComponent:HideTargetUI -- 자신을 제외한 모든 엔티티를 끕니다.
UI_HideButtonComponent:HandleButtonClickEvent -- 버튼 클릭 시 UI 숨김/표시 상태를 토글
UI_HUD_HoverSynergy:SetSynergyHoverOutline -- 시너지에 마우스를 올렸을 때, 해당 시너지를 가진 유닛에 타일을 표시합니다.
UI_HUD_HoverSynergy:HandleUITouchEnterEvent -- 시너지 UI에 마우스 진입 시 툴팁 표시 및 유닛 강조
UI_HUD_HoverSynergy:HandleUITouchExitEvent -- 시너지 UI에서 마우스 벗어날 시 툴팁 숨김 및 유닛 강조 해제
UI_LevelUpPopup_RewardButton:OnUpdate -- 호버 중일 때 툴팁 크기를 내용에 맞게 동적으로 조정
UI_LevelUpPopup_RewardButton:HandleUITouchEnterEvent -- 마우스 진입 시 보상 툴팁을 표시
UI_LevelUpPopup_RewardButton:HandleUITouchExitEvent -- 마우스 벗어날 시 툴팁을 숨김
UI_Mask:SetMask -- 타겟 UI를 기준으로 마스크를 설정하고 주변 배경을 어둡게 처리
UI_Mask:SetMaskWithPos -- 마스크의 위치와 크기를 받아 설정합니다.
UI_Mask:OnBeginPlay -- 하이라이트 모드일 때 펄스 애니메이션을 적용
UI_Mask:SetMaskWithRUID -- 리소스 ID를 사용하여 마스크 이미지와 크기를 설정
UI_Mask:SetMaskSizeMatch -- 현재 마스크 크기에 맞춰 배경 영역의 크기를 조정
UI_ShortCutKeyChangeButton:HandleButtonClickEvent -- 버튼 클릭 시 단축키 변경 모드를 활성화
UI_SynergyList_EachSlotBackground:OnBeginPlay -- 게임 시작 시 시너지 이름과 레벨 UI 요소를 찾아 저장
UI_SynergyList_EachSlotBackground:OnUpdate -- 시너지 이름과 레벨 텍스트 크기에 맞춰 배경 크기를 동적으로 조정
UI_Tooltip:OnBeginPlay -- 게임 시작 시 툴팁 시스템을 초기화하고 UI 목록을 설정
UI_Tooltip:ClearAllTooltipUI -- 모든 툴팁 UI를 비활성화하여 화면을 정리
UI_Tooltip:SetMouseHoveredUI -- 현재 마우스가 호버 중인 UI 엔티티를 설정
UI_Tooltip:OnUpdate -- 매 프레임마다 활성화된 툴팁 UI의 크기와 위치를 실시간 갱신
UI_Tooltip:SetSkillInfo -- 캐릭터의 스킬 정보를 표시하는 툴팁을 활성화/비활성화
UI_Tooltip:Update_SkillInfo -- 스킬 정보 툴팁의 내용 길이에 따라 크기와 위치를 동적으로 조정
UI_Tooltip:Update_RecommendItemInfo -- 유닛 정보창 위치에 따라 추천 아이템 툴팁의 위치를 동적으로 조정
UI_Tooltip:SetSynergyInfo -- 시너지 정보 툴팁을 설정하고 활성화 상태에 따라 내용을 갱신
UI_Tooltip:Update_SynergyInfo -- 시너지 정보 툴팁이 화면 밖으로 벗어나지 않도록 위치를 조정
UI_Tooltip:SetStatInfo -- 유닛의 스탯 정보 툴팁을 설정하고 상세 정보를 표시
UI_Tooltip:Update_StatInfo -- 스탯 툴팁의 내용 길이에 따라 크기를 조정하고 유닛 정보창에 맞춰 위치 설정
UI_Tooltip:SetItemInfo -- 아이템 정보 툴팁을 설정하고 아이템의 상세 정보를 표시
UI_Tooltip:SetItemEquipInfo -- 특정 캐릭터에게 아이템을 장착할 때 표시되는 툴팁 정보를 설정
UI_Tooltip:Update_ItemInfo -- 아이템 툴팁의 내용에 따라 크기를 조정하고 표시 타입에 따라 위치를 설정
UI_Tooltip:SetGoldsRewardInfoUI -- 골드 획득 방법과 보상량에 대한 정보를 계산하여 툴팁에 표시
UI_Tooltip:SetEXPInfoUI -- 경험치 획득 방법과 수량 정보를 계산하여 툴팁에 표시
UI_Tooltip:SetRuneInfoUI -- 룬 카드의 정보와 상태를 표시하는 툴팁을 설정
UI_Tooltip:Update_RuneInfo -- 룬 카드 툴팁의 내용과 태그에 따라 크기를 조정하고 표시 타입별 위치 설정
UI_Tooltip:SetGameModeInfo -- 게임 모드별 정보와 시즌 정보를 표시하는 툴팁의 내용을 설정
UI_Tooltip:Update_GameModeInfo -- 게임 모드 툴팁의 패널티 정보 유무에 따라 크기를 동적으로 조정
UI_Tooltip:SetCharShopInfo -- 캐릭터 상점에서 캐릭터 정보와 스킬을 표시하는 툴팁을 설정
UI_Tooltip:Update_CharShopInfo -- 캐릭터 상점 툴팁의 내용 길이에 따라 UI 요소들의 위치와 전체 크기를 조정
UI_Tooltip:SetRuneInfoUI_OnBattlePhase -- 전투 페이즈에서 룬 카드의 간단한 정보를 표시하는 툴팁을 설정
UI_Tooltip:SetBattleStatValue -- 전투 통계에서 특정 수치의 이름과 값을 표시하는 툴팁을 설정
UI_Tooltip_SynergyInfo:OnUpdate -- 구성 엔티티들의 위치 조절
UI_TutoButtonAnimation:AdjustTutoSelectButtonSize -- 튜토리얼을 진행할지 선택하는 버튼의 사이즈 조절 연출입니다.
UI_TutoButtonAnimation:HandleButtonClickEvent -- 튜토리얼 플레이 버튼 클릭 시 상태 변경 및 애니메이션 처리
UI_TutoButtonAnimation:HandleButtonClickEvent2 -- 튜토리얼 스킵 버튼 클릭 시 상태 변경 및 애니메이션 처리
UI_TutoButtonAnimation:HandleButtonClickEvent3 -- 세 번째 버튼 클릭 이벤트 처리 (플레이 상태 토글)
UI_TutorialLogic:OnBeginPlay -- 튜토리얼 시스템 초기화 및 필요한 데이터셋 로드
UI_TutorialLogic:ActivateTutoSelect -- 튜토리얼 진행 또는 스킵 선택 UI를 활성화
UI_TutorialLogic:ActivateAdviceMessage -- 안내 캐릭터의 안내 메시지를 활성화합니다.
UI_TutorialLogic:DeactivateAdviceMessage -- 핑크빈의 메시지를 비활성화합니다.
UI_TutorialLogic:BattleButtonOnOff -- 튜토리얼 진행 시, 전투 시작 버튼을 보이게/안 보이게 조절하는 함수입니다.
UI_TutorialLogic:SetDragGuide -- -엔티티 간 상호작용 가이드를 활성화합니다.
UI_TutorialLogic:SetSkipButton -- 튜토리얼 스킵 버튼의 활성화 상태를 설정
UI_TutorialLogic:DeactivateMaskAndHighlight -- 튜토리얼 마스크와 강조 효과를 모두 비활성화
UI_TutorialLogic:ActivateInteractionArrow -- 지정된 상호작용 화살표 가이드를 활성화하거나 비활성화
UI_TutorialLogic:DeactivateAllTutorialUI -- 튜토리얼에 관련된 모든 UI를 비활성화합니다.
UI_TutorialLogic:ClickAdviceMessage -- 안내 메시지 클릭 시 다음 페이지로 이동하거나 종료
UI_TutorialLogic:ShowSynergyTile -- 지정한 시너지에 해당하는 캐릭터를 강조합니다.
UI_TutorialLogic:ShowFieldTile -- 전장 타일을 보여줍니다.
UI_TutorialLogic:ShowTargetTile -- 현재 목표로 하는 타일을 화면에 표시합니다.
UI_TutorialLogic:checkAvailableTile -- 배치 전, 비어있는 타일을 탐색합니다.
UI_TutorialLogic:checkTargetWaitLine -- 지정한 캐릭터가 있는 대기석 타일을 탐색합니다.
UI_TutorialLogic:showTargetWaitLine -- 타겟 대기석을 보여줍니다.
UI_TutorialLogic:setUnitArrow -- 지정된 번호의 유닛 화살표를 활성화하거나 비활성화
UI_TutorialLogic:DragEntityWithPos -- -벡터 간 상호작용 가이드를 활성화합니다.
UI_TutorialLogic:SetTutoTileRUID -- 튜토리얼 타일의 스프라이트를 목적지 또는 일반 타일로 설정
UI_TutorialLogic:CheckFieldcharTile -- 지정한 캐릭터가 있는 전장 타일을 탐색합니다.
UI_TutorialLogic:SetUnitGuideLine -- 유닛의 배치를 유도하는 선의 위치를 결정합니다.
UI_TutorialLogic:GetArenaTile -- 전장 타일 중에서 LineNum번째 가로줄의 TileNum번째 타일을 가져옵니다.
UI_TutorialLogic:SetUnitGuideLine_Entity -- 유닛의 배치를 유도하는 선의 위치를 결정합니다.
UI_TutorialLogic:SetMaskStretchAll -- maskType에 따라 크기와 위치를 변경함.
UI_TutorialLogic:GetMaskOffsetFromArena -- 마스킹용 오프셋 좌표를 받아옵니다.
UI_TutorialLogic:OnUpdate -- 마스크가 켜져있는 경우, 현재 화면 크기를 받아와서 실시간으로 업데이트합니다.
UI_TutorialLogic:ScreenPostoUIPos -- screenpos를 UIpos로 변경
UI_TutorialLogic:SetDragItemGuide -- -벡터 간 상호작용 가이드를 활성화합니다.
UI_TutorialLogic:SetHPGaugePos -- -게이지 안내 마스크의 현재 위치를 조정합니다.
UI_TutorialLogic:SetArenaMapPath -- 현재 플레이어의 아레나 맵 경로를 생성하여 반환
UI_TutorialLogic:HandleKeyDownEvent -- 키보드 입력을 처리하여 튜토리얼 진행 및 UI 제어
UI_TutorialLogic:HandleButtonClickEvent6 -- 버튼 클릭 이벤트 처리 (현재 비활성화된 상태)
UI_TutorialLogic:HandleButtonClickEvent8 -- 튜토리얼 거부/스킵 버튼 클릭 시 로비로 이동 처리
UI_WorldExitTooltipEnabler:HandleMouseMoveEvent -- 마우스 이동 시 화면 우상단 영역에서 월드 종료 툴팁을 활성화
UnitSkillDescLogic:GetDefaultDesc -- 유닛의 스킬 설명을 기본 형식으로 생성하여 반환
UnitSkillDescLogic:GetDetailDesc -- 유닛의 상세 스킬 설명을 레벨별로 생성하여 반환
UnitSkillDescLogic:GetStatusEffectList -- 유닛이 가진 상태 효과 목록을 반환
UnitSkillDescLogic:GetColorTextFromNumberValue -- value를 지정한 colorType에 따라 리치텍스트를 추가한 텍스트로 바꾸어 반환합니다.
UnitSkillDescLogic:GetColorTextFromStringValue -- value를 지정한 colorType에 따라 리치텍스트를 추가한 텍스트로 바꾸어 반환합니다.
LoadingManager:SetEnableUI -- 로딩 UI의 활성화 상태를 설정하고 배경음악 페이드 처리
LoadingManager:SetProgressUI -- 로딩 진행률을 UI에 반영
LoadingManager:OnSyncProperty -- 동기화된 프로퍼티 변경 시 로딩 진행률 계산 및 업데이트
LoadingManager:ClearLoadedCount -- 로딩 카운트를 초기화하고 필요한 로딩 항목들을 설정
LoadingManager:GameStart -- 로딩 완료 후 게임을 시작하고 다음 페이즈로 이동
UI_Loading:SetEnableUI -- 로딩 UI 요소들의 활성화 상태를 설정하고 페이드 애니메이션 적용
UI_Loading:SetProgressUI -- 진행도를 변경하고, 그에 따라 UI를 갱신하는 함수입니다. 변경할 때 애니메이션 연출을 적용합니다.
UI_Loading:PlayLoadingAnim -- 큐 맨 앞의 연출을 재생합니다.
UI_Loading:OnUpdate -- 로딩 팁 업데이트 타이머 관리
UI_Loading:UpdateUI_Tip -- 로딩 화면에 표시할 팁 텍스트를 랜덤하게 업데이트
UI_Loading:HandleButtonClickEvent -- 게임 시작 버튼 클릭 시 로딩 완료 확인 후 게임 시작 요청
UI_Loading_Spinner:OnBeginPlay -- 스피너 애니메이션을 위한 자식 엔티티들을 초기화
UI_Loading_Spinner:OnUpdate -- 매 프레임마다 스피너 애니메이션을 업데이트
UI_Loading_TextBlinker:OnUpdate -- 텍스트 색상을 주기적으로 변경하여 깜빡임 효과 구현
UI_Color:OnBeginPlay -- 게임에서 사용할 다양한 색상 정보를 데이터 테이블에서 로드하여 초기화
UI_ActivateTooltipOnMouseHover:OnUpdate -- 툴팁 위치를 실시간으로 업데이트
UI_ActivateTooltipOnMouseHover:HandleUITouchEnterEvent -- 마우스가 UI 영역에 진입했을 때 툴팁 활성화 (PC 플랫폼만)
UI_ActivateTooltipOnMouseHover:HandleUITouchExitEvent -- 마우스가 UI 영역에서 벗어났을 때 툴팁 비활성화 (PC 플랫폼만)
UI_AutoScroll:OnBeginPlay -- 자동 스크롤 컴포넌트 초기화 및 스크롤 타입 설정
UI_AutoScroll:OnUpdate -- 매 프레임마다 자동 스크롤 위치를 업데이트
UI_AutoScroll:InitScroll -- 스크롤 위치를 초기화
UI_ButtonClickSoundComponent:HandleButtonClickEvent -- 버튼 클릭 시 지정된 사운드 재생
UI_ButtonClickSoundComponent:HandleUITouchDownEvent -- UI 터치 다운 시 지정된 사운드 재생
UI_ExitButton:HandleButtonClickEvent -- 버튼 클릭 시 지정된 대상 UI를 비활성화
UI_OpenButton:HandleButtonClickEvent -- 버튼 클릭 시 지정된 대상 UI를 활성화
CustomScrollLayoutComponent:OnBeginPlay -- 커스텀 스크롤 레이아웃 초기화 및 드래그 이벤트 연결
CustomScrollLayoutComponent:SortingChildrenEntities -- 자식 엔티티들을 지정된 정렬 방식에 따라 배치
CustomScrollLayoutComponent:SetCurrentScroll -- 현재 스크롤 위치를 설정하고 이벤트 발송
CustomScrollLayoutComponent:SetChildrenCount -- 자식 엔티티 개수를 설정하고 최대 스크롤 수 계산
CustomScrollLayoutComponent:MoveScroll -- 스크롤 휠 입력에 따라 스크롤 위치 이동
CustomScrollLayoutComponent:SetScrollBar -- 스크롤바의 크기와 위치를 현재 스크롤 상태에 맞춰 설정
CustomScrollLayoutComponent:OnDragScrollBar -- 스크롤바 드래그 시 스크롤 위치 업데이트
CustomScrollLayoutComponent:HandleMouseScrollEvent -- 마우스 스크롤 휠 이벤트 처리
CustomScrollLayoutComponent:HandleUITouchEnterEvent -- 마우스가 스크롤 영역에 진입했을 때 플래그 설정
CustomScrollLayoutComponent:HandleUITouchExitEvent -- 마우스가 스크롤 영역에서 벗어났을 때 플래그 해제
CustomScrollLayoutComponent:HandleEntityCreateEditorEvent -- 에디터에서 자식 엔티티 생성 시 자동 정렬 수행
DropDownBtnComponent:OnBeginPlay -- 드롭다운 버튼의 부모 엔티티 참조 설정
DropDownBtnComponent:ChangeStateOfTheList -- 드롭다운 목록 표시/숨기기 및 선택된 텍스트 변경
DropDownBtnComponent:HandleButtonClickEvent -- 드롭다운 버튼 클릭 시 목록 상태 변경
DropDownComponent:OnBeginPlay -- 드롭다운 버튼 리스트 엔티티 참조 설정
DropDownComponent:ChangeStateOfTheList -- 드롭다운 목록 표시/숨기기 상태 전환
DropDownComponent:HandleButtonClickEvent -- 드롭다운 메인 버튼 클릭 시 목록 상태 변경
ImageFontComponent:SetText -- 이미지 폰트 텍스트 설정 및 UI 갱신
ImageFontComponent:SetColor -- 이미지 폰트 색상 설정 및 UI 갱신
ImageFontComponent:SetShadow -- 이미지 폰트 그림자 효과 설정 및 UI 갱신
ImageFontComponent:HandleScreenTouchEditorEvent -- 에디터에서 화면 터치 시 이미지 폰트 갱신 처리
ImageFontComponent:HandleTextInputSubmitEditorEvent -- 에디터에서 텍스트 입력 제출 시 처리
ImageFontComponent:HandleTextInputEndEditEditorEvent -- 에디터에서 텍스트 입력 종료 시 처리
UI_ImageFontService:OnBeginPlay -- 이미지 폰트 데이터를 데이터셋에서 로드하여 캐시에 저장
UI_ImageFontService:IsValidCharacter -- 지정된 문자가 이미지 폰트에서 지원되는 유효한 문자인지 확인
UI_ImageFontService:Refresh -- 이미지 폰트 엔티티의 텍스트를 개별 문자 이미지로 분해하여 표시
TabComponent:OnBeginPlay -- 탭 컴포넌트 초기화 및 첫 번째 탭 활성화
TabComponent:ChangeTab -- 지정된 인덱스의 탭으로 전환하고 이벤트 발송
TabComponent:EnableChildrenEntities -- 모든 탭 버튼의 활성화 상태 제어
TabComponent:OnTabButtonClicked -- 탭 버튼 클릭 시 해당 탭으로 전환 및 이벤트 발송
TabComponent:SetChildren -- 자식 엔티티에서 탭 버튼들을 찾아 리스트에 등록 및 이벤트 연결
UITweenAlpha:OnBeginPlay -- UI 알파 트윈 컴포넌트 초기화 및 자동 재생 설정
UITweenAlpha:OnUpdate -- 매 프레임마다 알파 트윈 애니메이션 업데이트
UITweenAlpha:Play -- 알파 트윈 애니메이션 재생 시작
UITweenAlpha:PoingPonng -- 핑폁 모드로 시간 값 계산 (앞뒤로 왕복)
UITweenAlpha:Repeat -- 루프 모드로 시간 값 반복 계산
UITweenAlpha:Stop -- 알파 트윈 애니메이션 정지
UITweenAlpha_GroupCanvas:OnBeginPlay -- UI 그룹 캔버스 알파 트윈 컴포넌트 초기화
UITweenAlpha_GroupCanvas:OnUpdate -- 매 프레임마다 그룹 알파 트윈 애니메이션 업데이트
UITweenAlpha_GroupCanvas:Play -- 그룹 알파 트윈 애니메이션 재생 시작
UITweenAlpha_GroupCanvas:Stop -- 그룹 알파 트윈 애니메이션 정지
UITweenPosition:OnBeginPlay -- UI 위치 트윈 컴포넌트 초기화
UITweenPosition:OnUpdate -- 매 프레임마다 위치 트윈 애니메이션 업데이트
UITweenPosition:Play -- 위치 트윈 애니메이션 재생 시작
UITweenPosition:Stop -- 위치 트윈 애니메이션 정지
UITweenPosition_Stretch:OnBeginPlay -- UI 스트레치 위치 트윈 컴포넌트 초기화
UITweenPosition_Stretch:OnUpdate -- 매 프레임마다 스트레치 위치 트윈 업데이트
UITweenPosition_Stretch:Play -- 스트레치 위치 트윈 재생 시작
UITweenPosition_Stretch:Stop -- 스트레치 위치 트윈 정지
UITweenRotate:OnBeginPlay -- UI 회전 트윈 컴포넌트 초기화
UITweenRotate:OnUpdate -- 매 프레임마다 회전 트윈 업데이트
UITweenRotate:Play -- 회전 트윈 재생 시작
UITweenRotate:Stop -- 회전 트윈 정지
UITweenScale:OnBeginPlay -- UI 스케일 트윈 컴포넌트 초기화
UITweenScale:OnUpdate -- 매 프레임마다 스케일 트윈 업데이트
UITweenScale:Play -- 스케일 트윈 재생 시작
UITweenScale:Stop -- 스케일 트윈 정지
ArenaUI_BattleStartButton:OnUpdate -- 전투 시작 버튼 누르고 있을 때 시간 카운트 및 UI 갱신 처리
ArenaUI_BattleStartButton:PressButton -- 전투 시작 버튼 누르기/취소 로직 및 게임 단계 전환 처리
ArenaUI_BattleStartButton:HandleButtonClickEvent -- 전투 시작 버튼 클릭 시 버튼 누르기 실행
ArenaUI_BattleStartButton:HandleButtonClickEvent2 -- 취소 버튼 클릭 시 전투 준비 취소 처리
ArenaUI_BattleStartButton:HandleKeyDownEvent -- ESC 키 입력 시 전투 준비 취소 처리
UIManager_ArenaReadyPhase:UI_ChangeUIDisplay_Default -- 기본 UI 디스플레이 상태로 변경 (비어있음)
UIManager_ArenaReadyPhase:HandleButtonClickEvent2 -- 인벤토리 패널 확장/축소 버튼 클릭 시 UI 토글 처리
UI_BattleTeamInfo_RuneButton:SetProperty -- 룬 버튼의 이름, 설명, 등급, 비용 정보 설정
UI_BattleTeamInfo_RuneButton:HandleButtonStateChangeEvent -- 룬 버튼 마우스 오버/아웃 시 툴팁 표시 및 특수 효과 처리
UI_CharShopProduct:InitProperty -- 캐릭터 상점 상품 UI 요소들의 참조 초기화
UI_CharShopProduct:CheckTutorial -- 튜토리얼 진행 상태에서 해당 슬롯의 캐릭터 구매 가능 여부 확인
UI_CharShopProduct:HandleButtonClickEvent -- 캐릭터 상품 좌클릭 시 구매 처리 및 유효성 검사
UI_CharShopProduct:HandleUITouchEnterEvent -- 캐릭터 상품에 마우스 오버 시 툴팁 정보 표시
UI_CharShopProduct:HandleUITouchDownEvent -- 캐릭터 상품 우클릭 시 상세 정보 팝업 표시
UI_CharShopProduct:HandleUITouchExitEvent -- touch를 벗어나는 경우, 툴팁을 모두 끕니다.
UI_HPShrinkBar:OnUpdate -- HP 바 축소 애니메이션 업데이트
UI_HPShrinkBar:Lerp -- 두 값 사이의 선형 보간 계산
UI_HPShrinkBar:OnBeginPlay -- HP 바 엔티티 초기화 및 타겟 HP 바 참조 설정
UI_Inventory:OnBeginPlay -- 인벤토리 시스템 초기화 및 UI 갱신
UI_Inventory:ResistCache -- 아이템 정보를 데이터셋에서 불러와 캐시에 저장
UI_Inventory:RefreshUI_ItemInventory -- 플레이어가 보유한 아이템 목록으로 인벤토리 UI 갱신
UI_Inventory:RefreshUI_ByOnSyncProperty -- 동기화 프로퍼티 변경 시 인벤토리 UI를 첫 페이지로 초기화하여 갱신
UI_Inventory:ShowItemSelectPopup -- 아이템 상자 열기/닫기 시 선택 팝업 UI 표시 여부 제어 및 트윈 애니메이션 처리
UI_Inventory:RefreshPageMoveButton -- 인벤토리 페이지 이동 버튼 활성화/비활성화 상태 및 페이지 정보 갱신
UI_Inventory:RefreshUI_RuneInventory -- 플레이어가 보유한 룬 카드 정보를 UI에 표시하고 시각적 효과 적용
UI_Inventory:SetReddot -- 인벤토리 다음 페이지 버튼에 레드닷 표시 여부 제어
UI_Inventory:RefreshUI_BattleRuneList -- 전투 단계에서 플레이어의 룬 카드 설명 정보를 갱신
UI_Inventory:HandleButtonClickEvent -- 인벤토리 이전 페이지 버튼 클릭 시 페이지 이동 및 UI 갱신
UI_Inventory:HandleButtonClickEvent2 -- 인벤토리 다음 페이지 버튼 클릭 시 페이지 이동 및 UI 갱신
UI_InventoryItemSlot:HandleUITouchEnterEvent -- 인벤토리 아이템 슬롯 마우스 오버 시 아웃라인 및 툴팁 표시
UI_InventoryItemSlot:HandleUITouchExitEvent -- 인벤토리 아이템 슬롯 마우스 아웃 시 아웃라인 및 툴팅 비활성화
UI_InventoryItemSlot:HandleUITouchBeginDragEvent -- 인벤토리 아이템 드래그 시작 시 아웃라인 활성화 및 드래그 상태 설정
UI_InventoryItemSlot:HandleUITouchEndDragEvent -- 인벤토리 아이템 드래그 종료 시 아웃라인 비활성화 및 드래그 상태 해제
UI_InventoryItemSlot:HandleUITouchDownEvent -- 인벤토리 아이템 우클릭 시 아이템 조합 테이블 툴팁 표시
UI_ItemSelect_ItemSlot:HandleUITouchEnterEvent -- 아이템 선택 슬롯 마우스 오버 시 아웃라인 및 툴팁 표시
UI_ItemSelect_ItemSlot:HandleUITouchExitEvent -- 아이템 선택 슬롯 마우스 아웃 시 아웃라인 및 툴팅 비활성화
UI_ItemSelect_ItemSlot:HandleUITouchDownEvent -- 아이템 선택 슬롯 클릭 시 아이템 선택 및 우클릭 시 조합 테이블 표시
UI_ItemShopSlot:HandleUITouchDownEvent -- 아이템 슬롯 우클릭 시 조합 테이블 툴팁 표시
UI_ItemShopSlot:HandleUITouchEnterEvent -- 아이템 슬롯에 마우스 진입 시 아이템 정보 툴팁 표시
UI_ItemShopSlot:HandleUITouchExitEvent -- 아이템 슬롯에서 마우스 빠져나갈 시 툴팁 숨김
UI_RuneInventroyItemButton:OnBeginPlay -- 룬 인벤토리 아이템 버튼 초기화
UI_RuneInventroyItemButton:SetProperty -- 룬 카드의 속성 정보를 설정합니다.
UI_RuneInventroyItemButton:HandleButtonStateChangeEvent -- 룬 인벤토리 버튼 호버 상태 변경 시 툴팁 표시
UI_RuneInventroyItemButton:HandleUITouchBeginDragEvent -- 룬 카드 드래그 시작 시 처리
UI_RuneInventroyItemButton:HandleUITouchEndDragEvent -- 룬 카드 드래그 종료 시 처리
UI_RuneInventroyItemButton:HandleUITouchEnterEvent -- 룬 카드 슬롯에 마우스 진입 시 현재 호버링 슬롯 설정
UI_RuneRerollButton:HandleButtonClickEvent -- 룬 카드 리롤 버튼 클릭 시 리롤 수행
UI_RuneShopProductButton:SetProperty -- 룬 상점 상품의 속성 정보를 설정합니다.
UI_RuneShopProductButton:HandleButtonStateChangeEvent -- 룬 상점 상품 버튼 호버 상태 변경 시 툴팁 표시
UI_SynergyList:SetEnableSynergyHoverUI -- 시너지 호버 UI를 활성화/비활성화하고 정보를 표시합니다.
UI_SynergyList:RefreshSynergyList -- UI에 반영하기 위해, 현재 보유한 시너지 목록을 정렬합니다.
UI_SynergyList:RefreshUI -- 시너지 목록을 새로고침하는 함수입니다.
UI_SynergyList:OnBeginPlay -- 시너지 리스트 초기화
UI_SynergyList:GetSortedSynergyList -- 유닛 및 아이템, 룬 카드, 코치를 통해 획득하는 시너지 목록을 정렬하여 반환합니다.
UI_SynergyList:GetSortedSynergyListByCharID -- 캐릭터 ID를 기반으로 시너지 목록을 정렬하여 반환합니다.
UI_SynergyListComponent:SetEnableSynergyHoverUI -- 시너지 호버 UI를 활성화/비활성화하고 정보를 표시합니다.
UI_SynergyListComponent:RefreshSynergyList -- UI에 반영하기 위해, 현재 보유한 시너지 목록을 정렬합니다.
UI_SynergyListComponent:RefreshUI -- 시너지 목록을 새로고침하는 함수입니다.
UI_SynergyListComponent:OnBeginPlay -- 시너지 리스트 컴포넌트 초기화
UI_SynergyListNextPageButton:HandleButtonClickEvent -- 시너지 리스트 다음 페이지 버튼 클릭 시 페이지 전환
UI_UnitInfoPopup:OnBeginPlay -- 유닛 정보 팝업 초기화 및 데이터셋 로드
UI_UnitInfoPopup:ConnectToSelectedUnit -- 우클릭한 엔티티를 연결된 엔티티로 합니다.
UI_UnitInfoPopup:UI_Close -- 팝업을 닫을 때, 유닛과의 연결을 끊습니다.
UI_UnitInfoPopup:UI_Init -- 연결된 유닛의 기본 정보를 기반으로 UI를 초기화합니다.
UI_UnitInfoPopup:UI_Update -- 유닛 스탯 정보를 받아 정보 창을 업데이트하는 함수입니다.
UI_UnitInfoPopup:UI_Update_WhenMerged -- 캐릭터 병합 시, 병합된 캐릭터가 우클릭으로 보고 있던 캐릭터였다면 정보를 갱신해주는 함수
UI_UnitInfoPopup:UI_Update_StarInfo -- 현재 보고 있는 유닛의 별 등급과 관련된 정보를 업데이트합니다.
UI_UnitInfoPopup:UI_MoveOnPhaseChanged -- 페이즈가 바뀜 때 UI 위치를 옮깁니다.
UI_UnitInfoPopup:UI_ShowCoachInfoTooltip -- 코치 정보 툴팁을 표시합니다.
UI_UnitInfoPopup:UI_ShowFromCharacterShop -- 캐릭터 상점에서 각 상품에 우클릭하면, 해당 캐릭터의 상세 정보를 띠웁니다.
UI_UnitInfoPopup:HandleKeyDownEvent -- 키보드/마우스 입력 처리
UI_UnitInfoPopup:HandleButtonStateChangeEvent -- 스킬 정보 버튼 호버 상태 변경 처리
UI_UnitInfoPopup:HandleButtonStateChangeEvent2 -- 추천 아이템 버튼 호버 상태 변경 처리
UI_UnitInfo_HoverSkill:HandleButtonStateChangeEvent -- 유닛 정보에서 스킬 정보 버튼 호버 상태 변경 시 스킬 툴팁 표시
UI_UnitInfo_HoverStat:HandleUITouchEnterEvent -- 유닛 스탯에 마우스 진입 시 스탯 정보 툴팁 표시
UI_UnitInfo_HoverStat:HandleUITouchExitEvent -- 유닛 스탯에서 마우스 빠져나갈 시 스탯 정보 툴팁 숨김
UI_UnitInfo_HoverSynergy:HandleUITouchEnterEvent -- 유닛 시너지에 마우스 진입 시 시너지 정보 툴팁 표시
UI_UnitInfo_HoverSynergy:HandleUITouchExitEvent -- 유닛 시너지에서 마우스 빠져나갈 시 시너지 정보 툴팁 숨김
UI_UnitInfo_ItemSlot:HandleUITouchEnterEvent -- 유닛 아이템 슬롯에 마우스 진입 시 아이템 정보 툴팁 표시
UI_UnitInfo_ItemSlot:HandleUITouchExitEvent -- 유닛 아이템 슬롯에서 마우스 빠져나갈 시 아이템 정보 툴팁 숨김
UI_UnitInfo_ItemSlot:HandleUITouchDownEvent -- 유닛 아이템 슬롯 우클릭 시 조합 테이블 툴팁 표시
UI_UnitSkillInfo:SetEnableSkillHoverUI -- 유닛 스킬 정보 호버 UI를 활성화/비활성화하고 정보를 표시합니다.
UI_ChanceExpandButton:SetButtonShape -- 화살표 UI 변경
UI_ChanceExpandButton:HandleButtonClickEvent -- 확률 테이블 확장/축소 버튼 클릭 처리
UI_ChanceTable:ShowTooltip -- 중복 보상 툴팁 표시/숨김
UI_ChanceTable:Init -- 코치 확률 테이블 초기화
UI_ChanceTable:RequestShopProbability -- 상점 확률 데이터 요청
UI_ChanceTable:OnBeginPlay -- 확률 테이블 초기화
UI_ChanceTable:ShowSmallSlots -- 세부 확률 슬롯들 표시/숨김
UI_ChanceTable:HandleButtonStateChangeEvent -- 중복 보상 버튼에 마우스오버하면 툴팁등장
UI_CoachInventory_CoachSlot:HandleButtonStateChangeEvent -- 코치 슬롯 버튼 호버 상태 변경 시 코치 정보 툴팁 표시
UI_CoachInventory_CoachSlot:HandleButtonClickEvent -- 코치 슬롯 버튼 클릭 시 코치 동행 설정
UI_CombineTable_ItemTooltipActivator:HandleButtonStateChangeEvent -- 조합 테이블에서 아이템 호버 시 아이템 정보 툴팁 표시
UI_LobbyCoachInventory:OnBeginPlay -- 코치 보관함 UI 초기화 및 이벤트 연결
UI_LobbyCoachInventory:RefreshFollowingCoach -- 동행 코치 패널 내용을 갱신합니다.
UI_LobbyCoachInventory:RefreshCoachList -- 코치 보관함의 코치 리스트를 갱신합니다.
UI_LobbyCoachInventory:RefreshCurrencyList -- 화폐 정보 UI를 갱신합니다.
UI_LobbyCoachInventory:ChangeFollowingCoach_Check -- 선택한 동행 코치를 서버에 보내고, 검증합니다.
UI_LobbyCoachInventory:ChangeFollowingCoach_Client -- 코치 변경 완료 후 클라이언트 처리
UI_LobbyCoachInventory:ChangeCoachList_OnClient -- 코치 변경 완료 후 토스트 메시지 표시
UI_LobbyCoachInventory:SetCoachUnfollow -- 동행중인 코치를 동행 해제시키는 함수입니다.
UI_LobbyCoachInventory:SetCoachFollow -- 코치 보관함에서 특정 코치를 선택했을 때 실행
UI_LobbyCoachInventory:OnClick_MasterCoachEffect -- 마스터 코치의 이펙트를 On/Off할 수 있는 함수입니다.
UI_LobbyCoachInventory:EnableMasterCoachEffect -- 마스터 코치 이팩트 버튼 활성화/비활성화
UI_LobbyCoachInventory:HandleButtonClickEvent -- 코치 보관함 열기 버튼 클릭 시 리스트 갱신
UI_LobbyCoachInventory:HandleTabChangedEvent -- 코치 보관함 UI에서 등급 필터를 바꿨을 때 실행합니다.
UI_LobbyCoachInventory:HandleButtonClickEvent2 -- 코치 변경 완료 버튼 클릭 시 서버로 변경사항 전송
UI_LobbyCoachInventory:HandleButtonClickEvent4 -- 보유 코치 정렬 버튼 클릭 시 정렬 옵션 토글
UI_LobbyCoachInventory:HandleButtonClickEvent3 -- 코치 보관함 열기 시 코치 리스트 새로고침
UI_LobbyHUD:RefreshUI_LobbyHUD_GameStart -- 세이브된 데이터가 있는 경우 로비 HUD UI를 갱신하는 함수입니다.
UI_LobbyHUD:HandleButtonClickEvent -- 빈 이벤트 핸들러
UI_LobbyHUD:HandleButtonClickEvent2 -- 빈 이벤트 핸들러
UI_LobbyHUD:HandleButtonClickEvent3 -- 설정 버튼 클릭 시 ESC 메뉴 열기
UI_LobbyLevelSelect:OnBeginPlay -- 레벨 선택 UI 초기화 및 이벤트 연결
UI_LobbyLevelSelect:RefreshUI_SeasonLevelInfo -- 시즌 및 난이도 관련 정보 UI를 갱신합니다.
UI_LobbyLevelSelect:SetCoachChangeMode -- 코치 변경 모드를 활성화/비활성화합니다.
UI_LobbyLevelSelect:RefreshCurrentSelectedCoaches -- 현재 선택된 코치 목록 UI를 새로고침합니다.
UI_LobbyLevelSelect:RefreshCoachList -- '코치 선택 팝업' 내 코치 리스트를 갱신합니다.
UI_LobbyLevelSelect:SelectCoach -- 코치 선택 팝업에서 특정 코치를 선택했을 때 실행
UI_LobbyLevelSelect:UnselectCoach -- 코치 선택 팝업이 떠 있는 상태에서 특정 코치를 선택 해제했을 때 실행
UI_LobbyLevelSelect:ChangeCoachList_Check -- 선택한 코치 리스트를 서버에서 검증하고 저장합니다.
UI_LobbyLevelSelect:ChangeCoachList_OnClient -- 코치 변경 완료 후 클라이언트 UI 처리
UI_LobbyLevelSelect:SetEnteranceMode -- (기본 모드 <-> 입장 대기 모드) 전환합니다.
UI_LobbyLevelSelect:Cancle_CoachSelectMode -- 코치 변경 팝업에서 '닫기'를 눌렀을 때 실행합니다.
UI_LobbyLevelSelect:RefreshUI_LevelSelectPanel -- 레벨 선택 패널(레벨 목록)을 새로고침합니다.
UI_LobbyLevelSelect:RefreshUI_ModeSelectPanel -- 모드 선택 패널의 입장 조건을 검사하고 UI를 갱신합니다.
UI_LobbyLevelSelect:OnButtonClick_ModeSelect -- 모드 선택 화면에서 각 모드 버튼을 눌렀을 때 실행하는 함수입니다.
UI_LobbyLevelSelect:OnEndPlay -- 스크립트 종료 시 타이머 정리
UI_LobbyLevelSelect:HandleButtonClickEvent8 -- HUD에서 "이어하기"를 눌렀을 때
UI_LobbyLevelSelect:HandleButtonClickEvent3 -- 메인 패널에서 "코치 바꾸기(팝업 열기)" 버튼을 눌렀을 때 실행
UI_LobbyLevelSelect:HandleButtonClickEvent4 -- 코치 선택 팝업 닫기 버튼 처리
UI_LobbyLevelSelect:HandleButtonClickEvent5 -- 코치 변경 팝업에서 '교체 완료'를 눌렀을 때 실행합니다.
UI_LobbyLevelSelect:HandleTabChangedEvent2 -- 코치 선택 UI에서 등급 필터를 바꿨을 때 실행합니다.
UI_LobbyLevelSelect:HandleCustomScrollChangedEvent -- 코치 리스트 스크롤 변경 시 실행
UI_LobbyLevelSelect:HandleButtonClickEvent6 -- 게임 입장 버튼 클릭 시 입장 모드 전환
UI_LobbyLevelSelect:HandleButtonClickEvent7 -- 이전에 저장된 게임이 있을 때 등장하는 '이어하기' 팝업에서, 'yes' 버튼을 눌렀을 때 실행
UI_LobbyLevelSelect:HandleButtonClickEvent9 -- 이어하기 팝업에서 새로운 게임 시작 버튼 처리
UI_LobbyLevelSelect:HandleButtonClickEvent10 -- 메인 패널에서 '닫기'를 눌렀을 때 실행합니다.
UI_LobbyLevelSelect:HandleTabChangedEvent3 -- 코치 프리셋 버튼 변경 시 실행
UI_LobbyLevelSelect:HandleButtonClickEvent12 -- 레벨 선택 버튼 클릭 시 레벨 선택 패널 열기
UI_LobbyLevelSelect:HandleTabChangedEvent4 -- 레벨 선택 패널에서 시즌 탭 변경 시 실행
UI_LobbyLevelSelect:HandleButtonClickEvent13 -- HUD에서 '게임 시작'버튼을 눌렀을 때 실행, 게임 모드 선택 화면을 엽니다.
UI_LobbyLevelSelect_LevelSlot:HandleButtonClickEvent -- 레벨 슬롯 클릭 시 해당 레벨을 선택하고 레벨 선택 패널 닫기
UI_LobbyLevelSelect_ModeButton:HandleButtonStateChangeEvent -- 모드 버튼 호버 상태 변경 시 설명 텍스트 애니메이션 처리
UI_LobbyLevelSelect_ModeButton:HandleButtonClickEvent -- 모드 버튼 클릭 시 해당 모드로 전환
UI_PlayerTitleButton:callTitleElementList -- 현재 버튼에 맞는 칭호 요소를 리스트에 불러옵니다.
UI_PlayerTitleButton:TitleElementChange -- 칭호 요소를 변경하고, 서버에 올려줍니다.
UI_PlayerTitleButton:elementSelected -- 현재 장착 중인 칭호 요소를 UI에 갱신합니다.
UI_PlayerTitleButton:SetNameTagFontColor -- 네임태그의 Rank 값에 따라 폰트 색깔을 설정하는 함수입니다.
UI_PlayerTitleButton:TitleSettingInit -- 칭호 설정 UI 초기화 시 현재 장착된 칭호 정보를 표시
UI_PlayerTitleButton:ButtonChangeColor -- 버튼 선택 상태에 따라 색상을 변경
UI_PlayerTitleButton:ActivateButton -- 칭호 요소 버튼 활성화 시 목록 초기화 및 UI 설정
UI_PlayerTitleButton:HandleButtonClickEvent -- 칭호 관련 버튼 클릭 시 해당 기능 실행
UI_PlayerTitleButton:HandleButtonClickEvent2 -- 프로필 창 열기 버튼 클릭 시 프로필 UI 활성화 및 카메라 줌
UI_PlayerTitleSetting:InitOwnedTable -- 현재 보유중인 칭호 요소의 테이블을 만듭니다.
UI_PlayerTitleSetting:CheckOwnedOnly -- 보유 칭호만 보기 옵션 토글 및 목록 갱신
UI_PlayerTitleSetting:GetNextTitleList -- 리스트에 다음 칭호 요소 8개를 갱신합니다.
UI_PlayerTitleSetting:GetPreviousTitleList -- 리스트에 이전 칭호 요소 8개를 갱신합니다.
UI_PlayerTitleSetting:AddToOwnedTable -- 새로 획득한 칭호 요소를 보유 목록에 추가
UI_PlayerTitleSetting:HandleButtonClickEvent -- 보유 칭호만 보기 버튼 클릭 시 필터 토글
UI_PlayerTitleSetting:HandleButtonClickEvent2 -- 다음 페이지 화살표 버튼 클릭 시 목록 갱신
UI_PlayerTitleSetting:HandleButtonClickEvent3 -- 이전 페이지 화살표 버튼 클릭 시 목록 갱신
UI_PlayerTitleSetting:HandleButtonClickEvent4 -- 랜덤 칭호 조합 버튼 클릭 시 랜덤 칭호 생성
UI_PlayerTitleSetting:HandleMouseScrollEvent -- 마우스 스크롤로 칭호 목록 페이지 이동
UI_SimpleTooltipActivator:HandleUITouchEnterEvent -- 마우스 호버 시 툴팁 표시
UI_SimpleTooltipActivator:HandleUITouchExitEvent -- 마우스 호버 해제 시 툴팁 숨김