# Ornament Anarchy

**Author:** Aleanni  
**Version:** 1.0.0  
**Game:** Anno 117: Pax Romana  
**Mod ID:** `aleanni-ornament-anarchy`

Ornament Anarchy removes construction blocking from ornaments for unrestricted beauty building. Ornaments can be drawn or placed into buildings, walls, colonnades, roads, other decorations, and one another, allowing tightly composed scenes that the normal placement rules prevent.

## Features

- Makes every ornament available when this mod loads non-blocking.
- Permits overlapping ornaments and nearby construction.
- Prevents ornaments from hiding or deleting surrounding decorative props.
- Applies to compatible mod-added ornaments loaded before it.
- Supports existing saves and the campaign.
- Does not require any other mod.

## Scope and Limitations

The mod targets assets that contain the game's `Ornament` property. A functional building without that property retains its normal construction restrictions.

Ornament Anarchy changes placement rules, not the physical appearance of an asset. Visual clipping, flickering surfaces, inaccessible roads, or awkward animation can occur when incompatible objects occupy the same space. The player is responsible for deciding which overlaps look and function correctly.

## Installation

1. Extract the ZIP archive.
2. Place `[Cosmetic] Ornament Anarchy` in the game's `mods` directory.
3. Confirm that `modinfo.json` is directly inside that folder rather than inside an additional nested folder.
4. Enable the mod.

## Load Order and Modded Ornaments

The mod uses `LoadAfter: ["*"]`, placing it in the mod loader's late phase so that it can also affect ordinary-phase modded ornaments.

If another mod that creates or changes ornaments also loads in the late phase, keep Ornament Anarchy at the bottom of the relevant load order or add an explicit ordering rule. An ornament introduced after Ornament Anarchy has already run may retain its original blocking behaviour.

## Existing Saves and Removal

A new game is not required. However, the mod is not marked safe to remove. Overlapping construction that was valid while the mod was active may become invalid or behave unexpectedly after removal. Back up an important save before disabling or uninstalling the mod.

Multiplayer is not supported by the mod metadata.

## AI Assistance and Verification

AI tools were used to help inspect Anno 117's ornament configuration and identify the correct blocking values, and to help create the banner artwork. All shipped XML, metadata, selectors, and packaged files were subsequently reviewed and verified. Verification included XML and JSON syntax checks, inspection of the ornament selector and load-order metadata, and archive-content and integrity checks. This does not guarantee compatibility with future game or mod-loader updates or with ornaments introduced later in the same loading phase.
