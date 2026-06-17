# Changelog

All notable changes to this mod are documented in this file.

## [3.0] - 2026-06-17
### Added
- UI preset files for 16:9, 21:9, and 4K:
  - UI-Presets/xui_16x9.xml
  - UI-Presets/xui_21x9.xml
  - UI-Presets/xui_4k.xml

### Changed
- Rebalanced Pack Mule progression for 7DTD 3.0 flow:
  - perkPackMule CarryCapacity base_add values: 5,10,17,24,31
- Tuned Night Stalker carry bonus for 78-slot scaling:
  - perkNightStalkerThiefAdrenaline CarryCapacity base_add: 47
- Updated mod metadata:
  - Version: 3.0
  - DisplayName: Chaos Relics - Backpack Slot(78) - v3.0 (3.0 Compatible)
  - Description now includes 3.0 build note and changelog summary.

## [2.3] - 2026-06-17
### Changed
- Updated mod to 7DTD 3.0 XML schema compatibility.
- Migrated UI patch location from Config/XUi to Config/XUi_InGame.
- Updated backpack window xpaths for 3.0 UI structure (panel -> rect).
- Updated xui scale xpaths to root attributes (/xui/@scale and /xui/@stackpanel_scale).
- Tightened progression, buffs, and entity xpath targets for 3.0 data layout.

## [2.2] - Previous Release
### Changed
- UI layout optimizations for 13x6 backpack grid.
- Backpack width/height and header icon/currency positioning updates.
- Carry capacity adjusted to 34.
