# ZyraOS

ZyraOS is a minimal, performance‑focused Windows‑based operating system designed for clean aesthetics, fast boot times, and a distraction‑free desktop environment.  
Built with precision and intention, ZyraOS removes visual clutter, unnecessary themes, and stock wallpapers — replacing them with a single, custom‑designed gradient background and a refined Aero experience.

**First Release:** April 23, 2026

---

## ✨ What Makes ZyraOS Different

- 🎨 **Unified Visual Identity**  
  ZyraOS ships with a single, custom blue‑pink gradient wallpaper and a curated Aero theme.  
  No extra themes. No stock images. No visual noise.

- ⚡ **Minimal by Design**  
  Only the essential Windows components remain.  
  Everything else — wallpapers, themes, Spotlight assets, and unnecessary UI packs — is removed for a clean, console‑like environment.

- 🧩 **Stable & Compatible**  
  ZyraOS maintains full compatibility with Windows applications, drivers, and updates while delivering a streamlined experience.

- 🖥️ **Optimized for Low‑Power Hardware**  
  Perfect for N100 mini‑PCs, small form‑factor systems, and lightweight deployments.

---

## 📁 System Modifications

ZyraOS includes the following curated changes:

### ✔ Custom Wallpaper
- Replaces the default `img0.jpg` with a custom gradient background  
- Removes all other wallpapers and theme assets

### ✔ Theme Cleanup
- Only the following remain:
  - `aero.theme`
  - `Aero/` theme folder  
- All other `.theme` files and theme packs removed

### ✔ Spotlight & Lock Screen Cleanup
- Spotlight wallpaper folders removed  
- No rotating images  
- No fallback assets

### ✔ Clean File Structure
- No unused theme directories  
- No OEM bloat  
- No redundant resources

---

## 🛠️ Build Process (High‑Level Overview)

ZyraOS is created by:

1. Extracting the base Windows image  
2. Mounting `install.wim`  
3. Injecting the custom wallpaper  
4. Removing all stock wallpapers and themes  
5. Preserving only the Aero theme  
6. Cleaning Spotlight and lock screen assets  
7. Committing the image  
8. Rebuilding the ISO for deployment

This ensures a reproducible, minimal, and stable build.

---

## 📦 Release Philosophy

ZyraOS follows three core principles:

- **Minimalism** — Only what’s needed, nothing more  
- **Consistency** — A unified visual and functional experience  
- **Performance** — Faster boot, lower memory footprint, cleaner UI

---

## Downloading a browser

ZyraOS comes with no browser! Please use one of the commands in powershell to install one:

- **Firefox:** `winget install Mozilla.Firefox`
- **Chrome:** `winget install Google.Chrome`
- **Brave:** `winget install Brave.Brave`
- **Opera:** `winget install Opera.Opera`

---

## 🗓️ Release History

### **v1.0 — April 23, 2026**
- Initial release of ZyraOS  
- Custom wallpaper integration  
- Theme and wallpaper cleanup  
- Spotlight removal  
- Aero‑only environment  
- ISO rebuild and deployment

---

## 📜 License

ZyraOS does not distribute Microsoft binaries.  
This repository contains only scripts, documentation, and customization instructions.  
Users must supply their own legitimate Windows installation media.

---

## 🤝 Contributing

Contributions are welcome — whether it’s improving documentation, refining the build process, or suggesting new minimalism‑focused enhancements.

---

## 🌐 About ZyraLabs

ZyraOS is a project by **ZyraLabs**, focused on intelligent systems, automation, and next‑generation digital infrastructure.

