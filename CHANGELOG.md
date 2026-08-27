# Changelog

## v1.5.1

- Added a dedicated UI-free compatibility payload for Epic Games 1.7.8.
- Preserved the accepted Steam V16 payload byte-for-byte.
- Preserved all Arabic localization rows, fonts, and the name-order table in
  the Epic payload while excluding the three Steam-derived TWUI overrides.
- Made install, elevation, state detection, upgrades, and restore platform-aware.
- Disabled optional unverified components on the Epic tab.
- Added reproducible payload and manager builds plus platform-specific install
  and restore self-tests.

## v1.5.0

- Embedded the accepted V16 Arabic payload.
- Repaired verified multiline tooltip, Cao Cao, Meng Huo, main-menu credit, and
  campaign pre-battle text routes.

## v1.4.0 R6

- Updated the embedded Arabic localization to the user-tested R6 payload.
- Corrected requested faction, retinue, melee, armour, campaign movement,
  assignment, rank, prestige, reform, mounted-unit, and food-reserve terms.
- Corrected the displayed components for Sun Jian and Xiahou Dun, while
  retaining the verified Meng Huo components.
- Replaced ambiguous army-leadership scope text with `عند قيادة الجيش` and
  `على مستوى الفصيل عند قيادة الجيش` where appropriate.
- Added the native-BiDi display treatment for the three verified assignment
  descriptions so their Arabic word order is not reversed twice.
- Updated the optional embedded Dynasty character pack verification hash.
- Preserved game tokens, protected formatting, and the dedicated loading-text
  boundary. This release does not claim the separate full-corpus review is
  complete.

## v1.3.1

- Added separate Steam and Epic Games installation sections.
- Added automatic Epic Games manifest detection and manual folder selection.
- Added launching through Epic Games Launcher when its manifest is available.
- Kept the translation and optional mod packages unchanged from v1.3.0.

## v1.3.0

- Reviewed and corrected Arabic terminology across the localization.
- Corrected long right-to-left text layout for supported loading and advice
  panels.
- Included the complete optional Dynasty character portrait component.
- Included optional Dynasty faction colors.
- Included optional balanced campaign movement for human and computer
  factions.
- Added embedded-package verification and safe replacement of older managed
  versions.
