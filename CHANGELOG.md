# Assets Changelog

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
