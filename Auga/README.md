# Project Auga
##### by RandyKnapp / n4 / Vapok

Project Auga is a completely re-imagined, modder-friendly UI-overhaul for Valheim. Every last piece of UI was considered and reworked from the ground-up to create a more helpful and immersive player experience, all while remaining familiar to Valheim veterans.

Join the Discord: [Project Auga Discord](https://discord.gg/randyknappmods)
Visit the Website: [ProjectAuga.com](https://projectauga.com/)

## What's Changed?

Basically everything:
  * New Player HUD
  * Redesigned Player & Container inventories
  * New Consolidated Player Panels
  * Improved Crafting Panels
    

SEE SCREENSHOTS HERE: https://github.com/RandyKnapp/Auga/tree/main/Auga/Screenshots

## How to Install

### GitHub/Nexus Mods
  1. Install [BepInEx for Valheim﻿](https://valheim.thunderstore.io/package/denikson/BepInExPack_Valheim/)
  1. Download the zip file from the Nexus or the GitHub Release
  1. Extract the contents of the zip file to <Your Valheim Installation Directory>\BepInEx\plugins\Auga

### Thunderstore
  1. Install [BepInEx for Valheim﻿](https://valheim.thunderstore.io/package/denikson/BepInExPack_Valheim/)
  1. Download the zip file from here on Thunderstore
  1. Install with your mod manager
  1. OR - Extract the contents of the `files` folder inside the zip file to <Your Valheim Installation Directory>\BepInEx\plugins\Auga

## Mod Compatibility

Does it work with...

  * Controller: **LIMITED** (using a controller is not supported in all menus yet)
  * EpicLoot: **YES**
  * Equipment & Quick Slots: **YES**
  * Valheim+: **YES (LIMITED)** (Not all features work, please set the following config options or the HUD will break:)
	* displayStaminaValue = false
	* displayBowAmmoCounts = 0
	* Changing inventory size works, but it is slightly too small and always scrolls
	* GameClock: enabled = false
  * [JotunnBackpacks](https://www.nexusmods.com/valheim/mods/1416): **YES**
  * Better Wards: **YES**
  * Creature Level & Loot Control: **YES**
  * BetterTrader: **YES**
  * BuildExpansion: **NO (but kinda YES)** (But it now supports extra build pieces, BuildExpansion is no longer required when using Auga)
  * _Message me if your mod is compatible, I'll add it to this list! - RandyKnapp_

Project Auga drastically changes many parts of the Valheim UI. It will most likely not be compatible with other mods that modify the UI.

Please report bugs and mod conflicts on the [GitHub Issues Page](https://github.com/RandyKnapp/Auga/issues)﻿!

## For Modders

Project Auga comes with an API that allows other mods to easily access its features and create UI elements in the Auga style. It's also open-source on GitHub.

Auga API: https://github.com/RandyKnapp/Auga/wiki/Auga-API
Source: https://github.com/RandyKnapp/Auga
