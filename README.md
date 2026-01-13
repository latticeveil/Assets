# RedactedCraft Assets

This repo mirrors `RedactedCraftMonoGame/Defaults/Assets` from the game repo.

## Latest Update: The Continuist Papers

- Added lore-aligned block textures: runestone, veinstone, veilglass, resonance core, waybound frame, transit regulator.
- Compatible with the v1.1d lore pack content drop.

## Required structure

`Assets.zip` must contain only:
- `data/lore/**`
- `fonts/default.fnt`
- `textures/blocks/*.png`
- `textures/menu/**`

Anything outside those folders is ignored and should not be shipped.

## Block texture format (cube-net)

Each block texture is a 3x2 cube-net. The face size is `N` and the final image
must be `3N x 2N`. All blocks must use the same `N` (16, 32, 64, etc).

Tile layout (column, row):
- (0, 0) = Up (+Y)
- (1, 0) = East (+X)
- (2, 0) = Down (-Y)
- (0, 1) = South (+Z)
- (1, 1) = West (-X)
- (2, 1) = North (-Z)

File names are derived from the in-game registry (lowercase, underscores),
for example: `grass.png`, `door_open.png`.

The game builds its atlas at runtime from `textures/blocks/*.png`.
Do not include a prebuilt atlas in this repo.

## Versioning

- V5.x = small additions/removals or minor adjustments.
- V6+ = large texture drops or major pack changes.
- The Artificer Update is versioned as v6 to reflect the scope of the asset drop.

## Release checklist

1) Update `RELEASE_NOTES.md` with the new version tag.
2) Regenerate `Assets.zip` from `fonts/` and `textures/`.
3) Publish a GitHub release using the same tag (ex: `v5.2`).
