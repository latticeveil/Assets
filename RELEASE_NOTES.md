## 🧱 Asset Pack Cleanup (Per-Block Sources) 🧱

### 🔧 Changed
- Removed the prebuilt cube-net atlas from the pack (runtime builds it).
- Trimmed menu/button textures to only those referenced by the game.
- Regenerated `Assets.zip` from `fonts/` + `textures/` only.

### ✅ Fixes
- Inventory and in-hand blocks now pull from the same cube-net sources.
- Restored missing menu backgrounds using the MainMenu base.

### 🧪 Technical Impact
- Smaller download size and faster updates.
- One-file-per-block workflow for modding.

### 💡 Rationale
The pack is now a single source of truth: block cube-nets on disk, atlas at runtime.
This keeps inventory, hand, and world rendering consistent and easier to customize.

---

✨ *Crisp blocks. Single source. Smaller pack.* ✨
