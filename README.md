# YunoUI for World of Warcraft (ToxiUI-Based)

> 🖥️ Optimized for **1440p resolution** at **0.53 UI scale**.  
> ⚠️ If you're using **1080p** or any **UI scale other than 0.53**, elements will be misaligned and require manual repositioning.  
> I currently **do not plan** to create layouts for 1080p or other UI scales.

---

## 📦 Installation Instructions

### ✅ First-Time Setup

> ⚠️ **Make a backup first!** Backup your existing `Interface` and `WTF` folders before proceeding.

1. **Delete** your `Interface` and `WTF` folders.
2. Start the game and log in with any character once.
3. Close the game.
4. Open up WoWUp-CF, click **"My Addons"**, click the three dots and click **"Import/Export Addons"**. Import the [**WowUp** string](https://github.com/yunodu/yunoUIcxkvsdugz/blob/main/wowupimportstring) and click **Install**.
5. Navigate to: *"retail/WTF/Account/youraccountnumber/SavedVariables/"* and paste the contents of the [**WTF export** zip](https://github.com/yunodu/yunoUIcxkvsdugz/blob/main/WTF%20export.zip) here. Overwrite any existing files.
6. Launch the game again.
- If an error message pops up, click **"Load Anyway"** > **"Okay"**.
7. Once fully loaded and greeted by the **ToxiUI installation** window:
- Click **"Skip Process"** (⚠️ Do NOT go through the installer).
8. Type `/ec`
- Go to **Profiles** → **Existing Profiles** → select `yuno-dps` or `yuno-heal`.
- Click **Cancel** and **ignore** the warning.
9. Still in `/ec`, go to the **Private** tab:
- Under **Existing Profiles**, choose `yuno`.
- Click **Accept** and let the UI reload.
10. Configure additional addon profiles:
 - `/bw` → **Profiles** → select `yuno`
 - `/warp` → **Profiles** → select `yuno`
 - `/omnicd` → **Profiles** → select `yuno-dps`
 - `/plater` → **Profiles** → **Open Profile Settings** → select `yuno` → click **Yes** to reload UI

---

### 🔁 Setup on Alt Characters

After all addons are initialized:

1. On ToxiUI installation window, click **"Skip Process"** (do NOT run the installer).
2. Type `/ec` → **Profiles** → choose `yuno-dps` or `yuno-heal`, click **Cancel** and ignore the warning.
3. In the **Private** tab, select `yuno` and reload.
4. Repeat:
- `/bw` → **Profiles** → `yuno`
- `/warp` → **Profiles** → `yuno`
- `/omnicd` → **Profiles** → select `yuno-dps`
- `/plater` → **Profiles** → select `yuno` → click **Yes**

---

## ❓ FAQ

**Q: Enemy nameplates are missing?**  
A: Go to **ESC** → **Options** → **Interface** → **Nameplates** and enable **"Enemy Unit Nameplate"**.

**Q: My castbar is missing?**  
A: Castbars are handled by WeakAuras. If you’re not using the class WeakAuras, re-enable the ElvUI castbar manually.

**Q: How do I import class WeakAuras?**  
A: Go to **ESC** → **Options** → **AddOns** → **NaowhUI**.  
Select your class → click **Import** → wait for the progress bar to complete.  
The WeakAuras will auto-position correctly.

**Q: What Icon Pack do you use?**  
A: I use [CleanIcons](https://github.com/AcidWeb/Clean-Icons-Mechagnome-Edition).

**Q: When i swap to Cat/Bear/Stealth form my Actionbars are swapping?**  
A: Thats "Actionbar Paging". To disable that go to /ec -> Actionbars -> Player Bars -> Action Paging and remove the text in the box. You only have to do this for "Bar 1".

---

## 🌟 Features & Tips
- ⚠️ **Don't** update any of the Core WeakAuras. You **will** break positioning and then need to manual reposition stuff.  

- **Dungeon Prep UI**  
  Mouseover-faded bars above the chat show your flasks, food, oils, etc.

- **Quick Travel Menu**  
  Hold **ALT+H** to access the travel menu.

- **Hidden Minimap Buttons**  
  Hover just above the minimap to reveal hidden addon buttons.

- **LiteMount Integration**  
  Go to **ESC** → **Keybinds** → scroll to **LiteMount**
  Set a key for **"LiteMount Key Binding 1"**  
  LiteMount auto-selects the best mount based on your zone.

  ---

 ## 💬 Support
 
 If something breaks or doesn't align, double-check:
 - You’re using **1440p resolution**
 - Your **UI scale is exactly 0.53**
 
 For other resolutions, adjustments must be made manually.
 
 Enjoy the UI!

— Yuno
