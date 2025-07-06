![Visitor Count](https://komarev.com/ghpvc/?username=tamil05t&color=blue&style=flat&label=Visitors)

# Complete Guide: My Android Customization Journey (EvolutionX, Magisk, ReVanced, LSPosed)

This guide documents my journey exploring Android customization after a short break. It includes the tools I explored (EvolutionX ROM, Magisk, ReVanced, LSPosed), steps I followed, issues I faced, and what actually worked — structured as a comprehensive reference you can publish on GitHub Pages or similar.



## ✨ Introduction
After taking a short break from LinkedIn, I went deep into Android system customization. My focus was on setting up a custom ROM, rooting the phone, and testing premium bypass and customization tools like ReVanced and LSPosed modules.

My test device: **Redmi Note 8 (Ginkgo)**  
ROM used: **EvolutionX (Android 15)**



## 🚀 Setup: Installing EvolutionX (Custom ROM)

### Steps:
1. **Unlock bootloader** via Mi Unlock Tool.
2. Boot into custom recovery (**OrangeFox or TWRP**).
3. Wipe: Dalvik, Cache, System, Vendor, Data.
4. Flash latest **EvolutionX ROM zip**.
5. Flash **NikGapps (Core or Full)**.
6. Reboot to system.

### What Worked:
- EvolutionX flashed cleanly.
- GApps were included or flashed separately.
- Everything smooth; booted fine.

### Resources:
- ROM: [https://evolution-x.org](https://evolution-x.org)



## ⚙️ Rooting with Magisk

### Steps:
1. Download **Magisk v26+** zip.
2. Flash it in recovery after ROM install.
3. Boot into system, install **Magisk app (APK)**.
4. Grant root to apps and modules.

### What Worked:
- Magisk flashed fine.
- Root access stable.

### Link:
- Magisk GitHub: [https://github.com/topjohnwu/Magisk](https://github.com/topjohnwu/Magisk)



## 🛡️ Bypassing Google Play Integrity (GPay, UPI Fix)

### Problem:
- GPay account added & verified.
- But UPI payments failed silently (no debit, no error).

### Fix:
1. Install **Play Integrity Fix (Magisk Module)**
2. Enable **Zygisk** + **DenyList** in Magisk.
3. Add GPay + GMS to DenyList.
4. Install **Shamiko** if hiding root silently.
5. Reboot & re-verify in **YASNAC** or Play Integrity Checker.

### Links:
- [Play Integrity Fix](https://github.com/kdrag0n/play-integrity-fix)
- [Shamiko](https://github.com/LSPosed/LSPosed.github.io/wiki/Shamiko)



## 🌟 Installing ReVanced

### Goal:
- Use **YouTube without ads** and **unlock premium features**.

### Steps:
1. Install **ReVanced Manager APK**
2. Install **Vanced MicroG** (if non-root)
3. Patch YouTube (non-root) or use root variant
4. Flash recommended **ReVanced Magisk modules** for root install

### Link:
- [https://revanced.app](https://revanced.app)



## 🪖 Using LSPosed + Modules

### Goal:
- System-level feature tweaking (e.g., hide root, improve battery, spoof features)

### Steps:
1. Flash **LSPosed (Zygisk version)** via Magisk
2. Install **LSPosed Manager APK**
3. Use modules like:
   - Improve Battery Life
   - GMS Doze
   - Sensor Disabler
   - Lucky Patcher / XPrivacyLua (with caution)

### Link:
- [https://github.com/LSPosed/LSPosed](https://github.com/LSPosed/LSPosed)



## 🚀 Extra Tools Explored

### Debrid Tools for File Hosts:
- Tools like **Cocoleech**, **Deepbrid**, **LeechAll** support rapidgator/filejoker.
- No LSPosed/ReVanced modules exist to bypass such file host limits client-side.

### Modded APKs:
- Modders use APKs from **ModDroid**, **Modyolo**, or **RockMods** (e.g., for TextNow).
- Shared premium accounts also used (e.g., PikPak via `pikpak-plus`).


## 🎨 Customization (Wallpapers + Themes)

### Static Anime Wallpapers (Pro Modders Use):
- [Wallhaven (Anime Tag)](https://wallhaven.cc/search?q=anime&categories=111&purity=100&sorting=toplist)
- [Zerochan](https://www.zerochan.net)
- [Pixiv](https://www.pixiv.net)
- Telegram Channels: `@Anime4Kwalls`, `@AmoledWalls`

### Tools:
- Use **Wallpaper Engine (PC)** → Filter by `Image` only → Sync to Android app
- Use static instead of live wallpapers for battery/performance




## 📆 Summary
This exploration covered:
- Flashing EvolutionX
- Rooting with Magisk
- Passing Play Integrity for UPI/GPay
- Installing ReVanced
- Using LSPosed + modules
- Handling premium file hosts
- Static anime wallpapers for customization

More experiments soon (including kernel tweaking, Monet color overrides, and system automation).

