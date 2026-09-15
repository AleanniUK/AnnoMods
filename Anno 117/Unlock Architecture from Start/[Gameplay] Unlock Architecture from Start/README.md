# Unlock Architecture from Start

**Author:** Aleanni  
**Version:** 1.6.0  
**Game:** Anno 117: Pax Romana  
**Mod ID:** `aleanni-roads-unlocked-from-start`

Unlock Architecture from Start makes selected vanilla construction tools available from the beginning of a game. Roads, continuous quays, and regional walls and gates can be enabled independently, allowing a settlement's permanent layout and visual identity to be established immediately.

## Features

- Unlocks vanilla Roman and Celtic roads from the start.
- Unlocks vanilla Roman and Celtic walls, gates, and their automatic crossings.
- Unlocks vanilla Roman and Celtic continuous quay tools.
- Provides an independent toggle for each category.
- Enables all three categories by default.
- Supports existing saves and the campaign.
- Does not require any other mod.

## Configuration

| Option | Default |
| --- | --- |
| Unlock Roads From Start | Enabled |
| Unlock Walls and Gates From Start | Enabled |
| Unlock Continuous Quays From Start | Enabled |

Options may be changed through the mod browser. If an earlier version has already unlocked an asset in an existing save, disabling its option cannot safely relock that asset.

## What This Mod Does Not Change

The mod changes availability only. It does not make construction free and does not change construction materials, maintenance, movement speed, productivity, or building statistics.

It deliberately does not unlock:

- Aqueducts or canals
- Trading piers
- Repair cranes
- Shipyards
- Military towers or other military buildings
- Decorative wall ornaments supplied by other categories or mods

## Installation

1. Extract the ZIP archive.
2. Place `[Gameplay] Unlock Architecture from Start` in the game's `mods` directory.
3. Confirm that `modinfo.json` is directly inside that folder rather than inside an additional nested folder.
4. Enable the mod and select the desired unlock categories through the mod browser.

## Existing Saves and Removal

A new game is not required. Runtime unlock actions allow the selected tools to become available in existing saves.

The mod is marked safe to remove, but removing it or disabling an option does not guarantee that assets already recorded as unlocked in a save will become locked again. Make a backup before changing the mod list of an important save.

## Compatibility

The mod targets an explicit list of vanilla assets rather than every asset of a given type. It therefore does not automatically unlock roads, walls, gates, or quays added by other mods.

Another mod that changes the locked state of the same assets may produce load-order-dependent results. Multiplayer is not supported by the mod metadata.

## AI Assistance and Verification

AI tools were used to help search the extracted Anno 117 game data for the correct asset identifiers and unlock values, and to help create the banner artwork. All shipped XML, metadata, referenced assets, and packaged files were subsequently reviewed and verified. Verification included XML and JSON syntax checks, comparison with extracted game data, validation of custom trigger identifiers, and archive-content and integrity checks. This does not guarantee compatibility with future game or mod-loader updates.
