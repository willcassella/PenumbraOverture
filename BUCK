load("//defs.bzl", "global_compiler_flags")
load("//defs.bzl", "global_linker_flags")

cxx_binary(
    name = "PenumbraOverture",
    headers = [
        "AttackHandler.h",
        "ButtonHandler.h",
        "CharacterMove.h",
        "Credits.h",
        "DeathMenu.h",
        "DemoEndText.h",
        "EffectHandler.h",
        "FadeHandler.h",
        "GameArea.h",
        "GameDamageArea.h",
        "GameEnemy.h",
        "GameEnemy_Dog.h",
        "GameEnemy_Spider.h",
        "GameEnemy_Worm.h",
        "GameEntity.h",
        "GameForceArea.h",
        "GameItem.h",
        "GameItemType.h",
        "GameLadder.h",
        "GameLamp.h",
        "GameLink.h",
        "GameLiquidArea.h",
        "GameMessageHandler.h",
        "GameMusicHandler.h",
        "GameObject.h",
        "GameSaveArea.h",
        "GameScripts.h",
        "GameStickArea.h",
        "GameSwingDoor.h",
        "GameTypes.h",
        "GlobalInit.h",
        "GraphicsHelper.h",
        "HapticGameCamera.h",
        "HudModel_Throw.h",
        "HudModel_Weapon.h",
        "Init.h",
        "IntroStory.h",
        "Inventory.h",
        "MainMenu.h",
        "MapHandler.h",
        "MapLoadText.h",
        "Notebook.h",
        "NumericalPanel.h",
        "Player.h",
        "PlayerHands.h",
        "PlayerHelper.h",
        "PlayerMoveStates.h",
        "PlayerState.h",
        "PlayerState_Interact.h",
        "PlayerState_InteractHaptX.h",
        "PlayerState_Misc.h",
        "PlayerState_MiscHaptX.h",
        "PlayerState_Weapon.h",
        "PlayerState_WeaponHaptX.h",
        "PreMenu.h",
        "RadioHandler.h",
        "SDLMain.h",
        "SaveHandler.h",
        "SaveTypes.h",
        "StdAfx.h",
        "TriggerHandler.h",
        "Triggers.h",
        "Version.h",
        "resource.h",
    ],
    srcs = [
        "AttackHandler.cpp",
        "ButtonHandler.cpp",
        "CharacterMove.cpp",
        "Credits.cpp",
        "DeathMenu.cpp",
        "DemoEndText.cpp",
        "EffectHandler.cpp",
        "FadeHandler.cpp",
        "GameArea.cpp",
        "GameDamageArea.cpp",
        "GameEnemy.cpp",
        "GameEnemy_Dog.cpp",
        "GameEnemy_Spider.cpp",
        "GameEnemy_Worm.cpp",
        "GameEntity.cpp",
        "GameForceArea.cpp",
        "GameItem.cpp",
        "GameItemType.cpp",
        "GameLadder.cpp",
        "GameLamp.cpp",
        "GameLink.cpp",
        "GameLiquidArea.cpp",
        "GameMessageHandler.cpp",
        "GameMusicHandler.cpp",
        "GameObject.cpp",
        "GameSaveArea.cpp",
        "GameScripts.cpp",
        "GameStickArea.cpp",
        "GameSwingDoor.cpp",
        "GameTypes.cpp",
        "GraphicsHelper.cpp",
        "HapticGameCamera.cpp",
        "HudModel_Throw.cpp",
        "HudModel_Weapon.cpp",
        "Init.cpp",
        "IntroStory.cpp",
        "Inventory.cpp",
        "Main.cpp",
        "MainMenu.cpp",
        "MapHandler.cpp",
        "MapLoadText.cpp",
        "Notebook.cpp",
        "NumericalPanel.cpp",
        "Player.cpp",
        "PlayerHands.cpp",
        "PlayerHelper.cpp",
        "PlayerState_Interact.cpp",
        "PlayerState_InteractHaptX.cpp",
        "PlayerState_Misc.cpp",
        "PlayerState_MiscHaptX.cpp",
        "PlayerState_Weapon.cpp",
        "PlayerState_WeaponHaptX.cpp",
        "PreMenu.cpp",
        "RadioHandler.cpp",
        "SaveHandler.cpp",
        "SaveTypes.cpp",
        "StdAfx.cpp",
        "TriggerHandler.cpp",
        "Triggers.cpp",
        # "SDLMain.m",
    ],
    deps = [
        "//HPL1Engine:HPL1Engine",
    ],
    compiler_flags = global_compiler_flags + [
        "-isystem",
        "/opt/homebrew/include",
    ],
    linker_flags = global_linker_flags,
    link_style = "static",
)
