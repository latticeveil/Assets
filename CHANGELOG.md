# Assets Changelog

## v14.0.0 - "Veilborne Vitals Assets" - 2026-04-08

### ❤️ Survival HUD Additions
- **Health HUD Sheet**: Added the new `health.png` runtime GUI asset used for the first visible health band.
- **Hunger HUD Sheet**: Added the new `hunger.png` runtime GUI asset so hunger now visually ships with the survival pass.
- **Runtime Alignment**: Both HUD sheets are aligned to the current in-game survival layout rather than older placeholder art.

### 🜂 Attunement Placeholder Art
- **Sigil/Attunement Sheet**: Added `sigil_balance_mockup.png` as the current placeholder Attunement HUD asset.
- **Atonement vs Curse Split**: The art supports the current split-circle left/right meter presentation used by Veilwalker.
- **Work-In-Progress Notice**: This asset intentionally represents a placeholder system while the default gameplay loop is still being finished.

### 📦 Release Sync
- **Version Synchronization**: Aligned with the `v14.0.0` game release.
- **Current Live Baseline**: This release advances the public asset line from `v13.0.0`.
- **Optional UI Note**: Players who do not want the placeholder Attunement UI can disable it in-game with `/rule sigil off`.

---

## v13.0.0 - "Frontier Polish Assets" - 2026-04-04

### 🧭 Release Sync
- **Version Synchronization**: Aligned with the V13.0.0 game release
- **Latest-Release Contract**: Assets continue shipping as `Assets.zip` from the latest GitHub release
- **Historical Integrity**: V12.0.0 remains untouched while V13.0.0 becomes the new latest public asset line

### 📦 Packaging Cleanup
- **Source of Truth**: Rebuilt from `LatticeVeilMonoGame/Defaults/Assets`
- **Runtime-Only Payload**: Public package contains only the live runtime asset folders required by the game
- **No Local Update Tracker**: Removed reliance on any packaged local "latest version" file for remote asset update discovery

### 🎨 Content Alignment
- **GUI Refresh Alignment**: Synced current menu/button art used by the latest interface pass
- **Screenshot Button Update**: Includes the refreshed screenshot button art from the current runtime defaults
- **Worldgen Support Assets**: Kept the active terrain-facing texture/model set aligned with the current game build

---

## v12.0.0 - "Chrono Weaver Assets" - 2026-04-02

### 🏷️ Branding Alignment
- **Chrono Weaver Theme**: Updated asset package to match temporal manipulation branding
- **Version Synchronization**: Aligned with V12.0.0 game release
- **Metadata Consistency**: Updated README and changelog with new naming

### 📦 Asset Distribution
- **Installer Compatibility**: Assets remain compatible with installer-first distribution
- **Runtime Structure**: Maintained existing asset organization for launcher compatibility
- **Version Tracking**: Updated to V12.0.0 for proper version resolution

---

## v10.0.0 - "Worldshaper Reforged Assets" - 2026-03-03

### Texture and Visual Pass
- Updated block texture set from current runtime defaults.
- Added refreshed cubenet atlas output for the latest block/material mappings.
- Applied new transparency-focused texture updates for:
  - `glass.png`
  - `veilglass.png`
  - `leaves.png`

### Runtime Asset Structure
- Added current runtime metadata files:
  - `assets_manifest.lvc`
  - `textures/.asset_manifest.lvc`
  - `settings.json`
  - UI layout files
- Added `air.png` to the active block texture set for runtime completeness.

### Public Package Hygiene
- Removed lore data JSON tables from the distributed public asset payload.
- Kept `Assets.zip` aligned with launcher install expectations.

---

## v9.0.0 - "Gatekeeper's Assets" - 2026-02-21

### 🎨 New Multiplayer Background Images
- **InviteFriends_bg.png**: New background for friend invitation screen
- **JoinByCode_bg.png**: New background for code joining screen  
- **Kicked_background.png**: New background for kick/disconnect screen
- **MultiplayerHost_bg.png**: New background for multiplayer hosting screen
- **ShareJoinCode_bg.png**: New background for code sharing screen

### 🖼️ Texture Updates
- **air.png**: Added new transparent texture for improved block rendering

### 📁 Asset Structure
- **Enhanced Organization**: Improved folder structure for better asset management
- **Compatibility**: Ensured proper loading paths for V9.0.0 game integration
- **Performance**: Optimized asset loading for faster startup times

---

## Previous Versions
### v8.0.0 - "Worldforge Assets" - 2026-02-09
- Initial asset repository setup
- Core textures and models included
- Basic asset structure established
