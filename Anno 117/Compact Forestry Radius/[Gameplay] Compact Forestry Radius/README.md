# Compact Forestry Radius

**Author:** Aleanni  
**Version:** 1.1.0  
**Game:** Anno 117: Pax Romana  
**Mod ID:** `aleanni-compact-forestry-radius`

Compact Forestry Radius provides configurable forestry requirements for beauty-focused settlements. It lets woodcutters operate within a smaller planting area and independently reduces how many trees are needed by woodcutters, Roman charcoal kilns, and Celtic charcoal kilns.

## Features

- Configurable influence radius for Roman and Celtic woodcutters.
- One shared tree-requirement setting for Roman and Celtic woodcutters.
- Independent tree-requirement settings for Roman and Celtic charcoal kilns.
- Defaults to half of the corresponding vanilla radius or tree requirement.
- Supports existing saves and the campaign.
- Does not require any other mod.

## Configuration

| Option | Range | Default | Vanilla value |
| --- | ---: | ---: | ---: |
| Woodcutter Forest Radius | 1–8 | 4 | 8 |
| Needed Woodcutter Trees | 1–80 | 40 | 80 |
| Needed Roman Charcoal Trees | 1–80 | 40 | 80 |
| Needed Celtic Charcoal Trees | 1–80 | 40 | 80 |

The Roman and Celtic charcoal-kiln influence radii remain at their vanilla value of 9. Only their required tree counts are configurable.

Lower settings leave more room around forestry buildings for roads, farms, ornaments, and deliberately landscaped woodland. Extremely low settings make forestry substantially easier than vanilla.

## Installation

1. Extract the ZIP archive.
2. Place `[Gameplay] Compact Forestry Radius` in the game's `mods` directory.
3. Confirm that `modinfo.json` is directly inside that folder rather than inside an additional nested folder.
4. Enable the mod and adjust its options through the mod browser if desired.

## Existing Saves and Removal

A new game is not required. The mod is marked safe to remove; after removal, the affected buildings return to the values supplied by vanilla or by another active mod.

## Compatibility

This mod directly changes the `FreeAreaProductivity` settings of the following vanilla assets:

- Roman woodcutter (`2878`)
- Celtic woodcutter (`5976`)
- Roman charcoal kiln (`2880`)
- Celtic charcoal kiln (`5977`)

Another mod that changes the same values may override this mod or be overridden by it, depending on load order. Mods that alter unrelated forestry properties should remain compatible.

Multiplayer is not supported by the mod metadata.

## AI Assistance and Verification

AI tools were used to help search the extracted Anno 117 game data for the correct asset identifiers and vanilla values, and to help create the banner artwork. All shipped XML, metadata, referenced values, and packaged files were subsequently reviewed and verified. Verification included XML and JSON syntax checks, comparison with extracted game data, and archive-content and integrity checks. This does not guarantee compatibility with future game or mod-loader updates.
