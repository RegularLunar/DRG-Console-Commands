# Deep Rock Galactic - FSDCheatManager Functions

## Properties
- RoomJumpCount: IntProperty
- PreviousMaxDistanceBeforeCleanup: FloatProperty
- ToggleHoopGameMovement: MulticastInlineDelegateProperty
- SpawnPosMarker: ObjectProperty
- EscortShowSmartRockDebug: BoolProperty
- IsUsingSavedCheats: BoolProperty

## Functions

### AddResourceToTeamDeposit
- Resource: ObjectProperty
- amount: FloatProperty

### C_AddAllResourcesToInventory
- amount: FloatProperty

### C_AddForgingXP
- Number: IntProperty

### C_AddUncappedXP
- amount: IntProperty

### C_AddXP
- Number: IntProperty

### C_BiomeEffectsEnabled
- Enabled: BoolProperty

### C_BreakAllEnemyArmor

### C_Campaign_Advance

### C_Campaign_CompleteAll

### C_Campaign_CompleteCurrent

### C_Campaign_CompleteMain

### C_Campaign_ResetCompleted

### C_Campaign_ResetProgress

### C_ClearAllDecalsAll

### C_ClearAllDecalsLocal

### C_ClearAllMilestones

### C_ClearAllMissionStats

### C_CompleteMission

### C_CompleteObjectives

### C_DebugTargetEnemySync
- FindIt: BoolProperty

### C_DeepDives_List

### C_DeepDives_Refresh

### C_DeepDives_Reset

### C_DeepDives_SetSeed
- Seed: IntProperty

### C_DeepDives_UnlockAll

### C_DestroyAllDancingCharacters

### C_DisableBackendEvents

### C_DLC_ClearAnnounced

### C_Escort_AddOilShale
- Number: IntProperty

### C_Escort_JumpToNextPhase
- WorldContextObject: ObjectProperty

### C_Escort_SetMuleSpeed
- WorldContextObject: ObjectProperty
- Speed: FloatProperty

### C_Escort_ShowSmartRockDebug
- shouldShow: BoolProperty

### C_Facility_DisableShields

### C_Facility_SpawnDataCore

### C_FadeFromBlack
- WorldContextObject: ObjectProperty

### C_FailMission

### C_FixedMissionSeed
- Seed: IntProperty

### C_FixedPLSSeed
- Seed: IntProperty

### C_FlareInfiniteDuration
- Enabled: BoolProperty

### C_ForceCrash

### C_FSDEvent_ClearSeenRewards

### C_FSDEvent_ListEvents

### C_FSDEvent_SetDebugEvent
- EventName: StrProperty

### C_GameDLC_ResetAnnouncements

### C_GiveAllGenericHeroItems

### C_GodMode
- forceEnable: IntProperty

### C_IncreasePlagueInfection
- Increment: FloatProperty

### C_IncrementAllMissionStats
- amount: IntProperty

### C_Intoxication_Set
- Percent: IntProperty

### C_Intoxication_SetAll
- Percent: IntProperty

### C_JetBoots_Enable

### C_JetBoots_Enable_MK2

### C_JumpToNextRoom

### C_KillAll

### C_KillAllFriendly

### C_KillAllNeutral

### C_KillPlayer

### C_KillTeam

### C_LevelUpCharacter
- amount: IntProperty

### C_MachineEvents_FinishCurrent

### C_MachineEvents_Track
- Track: BoolProperty

### C_MinersManual_EnableWorkInProgress
- WorldContextObject: ObjectProperty

### C_MissionMap_AutoRotate
- Enabled: BoolProperty

### C_MissionMap_DoubleWarning
- indexA: IntProperty
- indexB: IntProperty

### C_MissionMap_ForceAnomaly
- Index: IntProperty

### C_MissionMap_ForceWarning
- Index: IntProperty

### C_MissionMap_Rotate

### C_MissionMap_SetSeed
- Seed: IntProperty

### C_MissionMap_TestDistribution

### C_PlayNewMusic
- songIndex: IntProperty

### C_PreventMeteors

### C_PrintLoadout

### C_ProjectileDebugPrintToggle

### C_ProjectileDrawPaths

### C_Promotion_ClearRewardsSeen

### C_Promotion_SetCampaignComplete

### C_Promotion_SetLevel
- Number: IntProperty
- 1-18
### C_Promotion_SetLevelSpecific
- onCharacter: ObjectProperty
- Number: IntProperty

### C_PropHunt_Start
- InServerIndex: IntProperty

### C_PropHunt_Stop

### C_RecordMode

### C_Refinery_BreakPipes

### C_Refresh_Daily_Special
- Index: IntProperty

### C_RefreshDailyDeal
- Seed: IntProperty

### C_Remove_VictoryPose

### C_Remove_WeaponSkinsFromCrate_Framwork

### C_RemoveAllWidgets

### C_RemovePlayerRanks
- Number: IntProperty

### C_Reset_Drinks

### C_Reset_EnemyKillCount

### C_Reset_MinersManual

### C_Reset_Perks

### C_Reset_PickaxeParts

### C_Reset_Poses

### C_Reset_WeaponSkins

### C_Reset_WeaponSkins_Framworks

### C_Reset_WeaponSkins_Paintjobs

### C_Reset_WeaponSkinsAndUpgrades

### C_Reset_YearTwoGifts

### C_ResetAchievements

### C_ResetAll_Vanity

### C_ResetCheatedResources
- newAmount: IntProperty

### C_ResetForgingXP

### C_ResetLatestAdvertisedId
- WorldContextObject: ObjectProperty
- AdvertisedId: StrProperty

### C_ResetSteamAchievementStats

### C_Resupply

### C_Revive

### C_Salvage_FixMiniMules

### C_Schematic_GiveRandom

### C_Schematics_ClearHasSeenFirstMessage

### C_Schematics_ForgeAll

### C_Schematics_ForgeAll_Owned

### C_Schematics_ResetAll

### C_Schematics_UnlockAll

### C_Season_SetActiveSeason
- WorldContextObject: ObjectProperty
- Index: IntProperty

### C_Seasons_AddBonusScripFragment
- Number: IntProperty

### C_Seasons_AddChallenge

### C_Seasons_AddHeartsCollecdted
- Number: IntProperty

### C_Seasons_AddXP
- WorldContextObject: ObjectProperty
- Number: IntProperty

### C_Seasons_ClearAllProgress

### C_Seasons_ClearChallenges

### C_Seasons_ClearSeasonCompletedAnnounced

### C_Seasons_CompleteScripChallenge
- Number: IntProperty

### C_Seasons_CompleteSeason

### C_Seasons_CompleteSeasonAlmost

### C_Seasons_IncrementChallenge
- Index: IntProperty

### C_Seasons_PrintScripProgress

### C_Seasons_ResetBonusScripFragmentsCollected

### C_Seasons_ResetPlagueHeartsCollected

### C_Seasons_ResetReroll

### C_Seasons_ResetToken

### C_Seasons_ResetTreeOfVanity

### C_Seasons_ResetXP
- WorldContextObject: ObjectProperty

### C_SetActorTrackingVisible
- Visible: BoolProperty

### C_SetAmmoCostEnabled
- Enabled: BoolProperty

### C_SetDancing
- shouldDance: BoolProperty
- danceMove: IntProperty

### C_SetEnglish
- Val: IntProperty

### C_SetFastFlares

### C_SetFlyMode
- flyEnabled: BoolProperty

### C_SetHealth
- Health: FloatProperty

### C_SetInstantUsables
- Value: BoolProperty

### C_SetInWorldSubtitlesActive
- Active: BoolProperty

### C_SetPlayers
- Number: IntProperty

### C_SetSavedCheats

### C_SetStandingDown
- standingDown: BoolProperty

### C_SetSuperRapidFireEnabled
- Enabled: BoolProperty

### C_SetTestingCharacter
- characterID: ObjectProperty

### C_SetTestMission
- missionIndex: IntProperty

### C_SetUseSavedCheatsByDefault
- useSavedCheats: BoolProperty

### C_SpawnAllParticles

### C_SpawnBarrelOnPlayer
- amount: IntProperty

### C_SpawnDancingCharacterOnSelf
- InDanceIndex: IntProperty

### C_SpawnDropPodOnSelf
- Delay: FloatProperty

### C_SpawnEvenRewarder

### C_SpawnNormalWave

### C_SpawnScriptedWave

### C_SpawnScriptedWaveIndex
- Index: IntProperty

### C_StartCountDown

### C_StopMovement
- shouldMove: BoolProperty

### C_TeleportAllPlayersToMe

### C_TeleportPlayerToMe
- InPlayerIndex: IntProperty

### C_TeleportToPlayer
- InPlayerIndex: IntProperty

### C_TestSpecialEventChance

### C_ToggleCanShowBlood

### C_ToggleFadingDebug

### C_ToggleFadingEnabled

### C_ToggleHoopGameMovement

### C_Treasures_Reward
- Count: IntProperty

### C_Treasures_Track
- Mode: IntProperty

### C_TryRespawnBoneCollector

### C_Unlock_Facility

### C_UnlockAll

### C_UnlockAll_ArmorMats

### C_UnlockAll_Beers

### C_UnlockAll_Drinks

### C_UnlockAll_Perks

### C_UnlockAll_PickaxeParts

### C_UnlockAll_Poses

### C_UnlockAll_Poses_ForAll

### C_UnlockAll_StoreVanity

### C_UnlockAll_Weapons

### C_UnlockAll_WeaponSkins

### C_UnlockAll_WeaponSkins_Frameworks

### C_UnlockAll_WeaponSkins_Paintjobs

### C_UnlockAll_WeaponUpgrades

### C_UnlockOverclocking

### C_VanityMasteryAddXP
- Number: IntProperty

### C_VanityMasteryResetXP

### C_WeaponMaintenance_AddXP
- XP: IntProperty

### C_WeaponMaintenance_Reset

### C_Windows_CloseAll

### C_Windows_PrintStack

### Cheat_AddCredits
- WorldContextObject: ObjectProperty
- amount: IntProperty

### Cheat_AddPerkPoints
- WorldContextObject: ObjectProperty
- amount: IntProperty

### Cheat_AddXP
- WorldContextObject: ObjectProperty
- amount: IntProperty

### Cheat_Campaign_Advance
- WorldContextObject: ObjectProperty

### Cheat_Campaign_Complete
- WorldContextObject: ObjectProperty

### Cheat_DeepDives_Refresh
- WorldContextObject: ObjectProperty

### Cheat_ForceLostPack
- WorldContextObject: ObjectProperty

### Cheat_ForceTreasure
- WorldContextObject: ObjectProperty

### Cheat_GenerateNewMissionSeed
- WorldContextObject: ObjectProperty
- Enabled: BoolProperty

### Cheat_MinersManual_ShowAll
- WorldContextObject: ObjectProperty

### Cheat_PickAxeVanity_ResetAll
- WorldContextObject: ObjectProperty

### Cheat_PickAxeVanity_UnlockAll
- WorldContextObject: ObjectProperty

### Cheat_RemoveResources
- WorldContextObject: ObjectProperty
- amount: IntProperty

### Cheat_ResetEquippedUpgrades
- WorldContextObject: ObjectProperty

### Cheat_Resources
- WorldContextObject: ObjectProperty
- amount: FloatProperty

### Cheat_Schematic_ForgeAll
- WorldContextObject: ObjectProperty

### Cheat_Schematic_ForgeAll_Owned
- WorldContextObject: ObjectProperty

### Cheat_Schematic_GiveRandom
- WorldContextObject: ObjectProperty

### Cheat_Schematic_ResetAll
- WorldContextObject: ObjectProperty

### Cheat_Schematic_UnlockAll
- WorldContextObject: ObjectProperty

### Cheat_SetHealth
- newHealthValue: FloatProperty
- Player: ObjectProperty

### Cheat_SetSpawnPosMarker
- Actor: ObjectProperty

### Cheat_UnlockAll_Beers
- WorldContextObject: ObjectProperty

### Cheat_UnlockAll_Poses
- WorldContextObject: ObjectProperty

### Cheat_UnlockAllUpgrades
- WorldContextObject: ObjectProperty

### Cheat_UnlockAllWeapons
- WorldContextObject: ObjectProperty

### Cheat_UnlockWeapon
- WorldContextObjectm: ObjectProperty
- ItemID: ObjectProperty

### D_EnableMovieMode
- Value: BoolProperty

### D_EnableMovieModeInSpacerig
- Value: BoolProperty

### D_MovieModeStartAtOrigin
- Value: BoolProperty

### D_MovieModeStartWithCameraShake
- Value: BoolProperty

### D_Rejoin_RestoreState

### DestroyAllInstances
- destroy: ClassProperty

### GetListOfRoomNames
- roomNames: ArrayProperty (StrProperty elements)

### GetSavedCheatValue
- CheatName: NameProperty
- ValueToGet: IntProperty
- ReturnValue: BoolProperty

### InstantDropResuppyPod
- pod: ObjectProperty

### IsFastMovementActive
- ReturnValue: BoolProperty

### IsFlareGunProjectilesInfinite
- ReturnValue: BoolProperty

### IsFlyModeActive
- ReturnValue: BoolProperty

### IsInGodMode
- ReturnValue: BoolProperty

### R_Add_Aquarq
- amount: IntProperty

### R_Add_BitterGem
- amount: IntProperty

### R_Add_Phazyonite
- amount: IntProperty

### R_AddCraftingResource
- amount: IntProperty
- Type: IntProperty

### R_AddCredits
- Number: IntProperty

### R_AddDystrum
- amount: FloatProperty

### R_AddGold
- amount: FloatProperty

### R_AddHollomite
- amount: FloatProperty

### R_AddMatrixCores
- Number: IntProperty

### R_AddMorkite
- amount: FloatProperty

### R_AddNitra
- amount: FloatProperty

### R_AddPerkPoints
- amount: IntProperty

### R_AddResources
- Number: FloatProperty

### R_AddResources_Player
- Number: FloatProperty

### R_AddSeasonToken
- WorldContextObject: ObjectProperty
- Number: IntProperty

### R_RemoveCraftingResource
- amount: IntProperty
- Type: IntProperty

### R_RemoveCredits
- Number: IntProperty

### R_RemoveResources
- Number: IntProperty

### ResetSpacerigIntroMessage

### ResetTutorials

### Server_Refresh_Daily_Special
- Index: IntProperty

### SetFastMovement
- fast: BoolProperty

### SetGodMode
- God: BoolProperty

### SetHUDVisible
- ShowHUD: BoolProperty

### SetQuadPickAxe
- quad: BoolProperty

### SetSavedCheatValue
- CheatName: NameProperty
- ValueToSet: IntProperty
- ReturnValue: BoolProperty

### SetSpawnEnemies
- SpawnEnemies: BoolProperty

### SetStandingDown
- standingDown: BoolProperty

### ShowTutorialDebug

### SpawnBosco
- droneClass: SoftClassProperty
- aControllerClass: ClassProperty

### SpawnCritters
- descriptor: ObjectProperty
- Count: IntProperty

### SpawnEnemies
- descriptor: ObjectProperty
- Count: IntProperty

### SwitchCharacter
- characterID: ObjectProperty

### ToggleDebugEvent
- InEvent: ObjectProperty
