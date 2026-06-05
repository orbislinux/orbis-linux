<div align="center">

<img src="https://orbislinux.org/branding/orbis-logo.png" alt="Orbis Linux Logo" width="120"/>

# ORBIS LINUX

**Free. Open. For everyone.**

A free and open-source Linux distribution based on Linux 7.0, featuring KDE Plasma 6 desktop, designed for home users worldwide.

[![Version](https://img.shields.io/badge/version-1.0-7F77DD?style=flat-square)](https://orbislinux.org)
[![License](https://img.shields.io/badge/license-GPL%20v3-534AB7?style=flat-square)](LICENSE)
[![Desktop](https://img.shields.io/badge/desktop-KDE%20Plasma%206-7F77DD?style=flat-square)](https://kde.org)

[🌐 Website](https://orbislinux.org) · [⬇️ Download](https://orbislinux.org/#download) · [📄 Release Notes](https://orbislinux.org/release-notes) · [🐛 Report Bug](https://github.com/orbislinux/orbis-linux/issues)

</div>

---

## 📸 Screenshots

*Coming soon — screenshots will be added with the first public release.*

---

## ✨ Features

- 🖥️ **KDE Plasma 6.6** — Modern, fast and highly customizable desktop with Wayland support
- 📦 **Ready Out of the Box** — LibreOffice, Firefox, VLC, GIMP and more pre-installed
- 🛡️ **Secure & Stable** — Built on Linux 7.0 (Lazy) with regular security updates
- 🌍 **Multi-Language** — Full Turkish and English support out of the box
- ⚡ **Light and Fast** — Runs smoothly on hardware with as little as 2 GB RAM
- 🖨️ **Easy Installation** — Guided graphical installer (Calamares)
- 💿 **Live USB Support** — Try before you install
- 🔓 **Forever Free** — Open-source, no cost, always

---

## 💻 System Requirements

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| CPU | 64-bit (x86_64) | Multi-core |
| RAM | 2 GB | 4 GB+ |
| Storage | 20 GB | 40 GB+ |
| Display | 1024×768 | 1920×1080 |
| ISO Size | ~2.3 GB | — |

---

## 🚀 Getting Started

### 1. Download the ISO

Download the latest ISO from [orbislinux.org](https://orbislinux.org/#download).

### 2. Create a bootable USB

**Windows:** Use [Rufus](https://rufus.ie) or [Balena Etcher](https://etcher.balena.io)

**Linux/macOS:**
```bash
sudo dd if=orbis-linux-1.0.iso of=/dev/sdX bs=4M status=progress
```

### 3. Boot and Install

1. Boot your computer from the USB drive
2. Click **"Install Orbis Linux"** on the desktop
3. Follow the guided installation wizard
4. Reboot and enjoy! 🎉

---

## 🛠️ Building from Source

Orbis Linux is built using `live-build` on a Linux 7.0 host system.

### Prerequisites

```bash
sudo apt install live-build debootstrap squashfs-tools xorriso
```

### Build

```bash
git clone https://github.com/orbislinux/orbis-linux.git
cd orbis-linux
chmod +x build.sh
./build.sh
```

The ISO will be created in the project directory as `live-image-amd64.hybrid.iso`.

> ⚠️ Build requires a Linux 7.0 host system and approximately 10-15 GB of free disk space.

---

## 📁 Repository Structure

```
orbis-linux/
├── build.sh              # Main build script
├── branding/             # Logos, wallpapers, icons
│   ├── orbis-logo.png
│   ├── orbis-logo.svg
│   └── orbis-wallpaper.png
├── docs/                 # Documentation
│   ├── installation.md
│   └── contributing.md
└── README.md
```

---

## 🗺️ Roadmap

| Version | Codename | Status | ETA |
|---------|----------|--------|-----|
| v1.0 | Core | ✅ Released | May 2026 |
| v1.1 | Pulse | 🔧 In Development | Q3 2026 |
| v1.2 | Orbit | 📋 Planned | Q4 2026 |
| v2.0 | Nova | 📋 Planned | 2027 |

See the full [Roadmap](https://orbislinux.org/roadmap) for details.

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

- 🐛 **Report bugs** via [GitHub Issues](https://github.com/orbislinux/orbis-linux/issues)
- 💡 **Suggest features** via [GitHub Issues](https://github.com/orbislinux/orbis-linux/issues)
- 🌍 **Help with translations**
- 📖 **Improve documentation**
- ⭐ **Star this repository**

---

## 📄 License

Orbis Linux is released under the [GNU General Public License v3.0](LICENSE).

---

## 👨‍💻 Created by

**Murat KOZAN** — Founder & Lead Developer

🌐 [orbislinux.org](https://orbislinux.org) · 📸 [@orbislinux](https://instagram.com/orbislinux) · 🐙 [GitHub](https://github.com/orbislinux)

---

<div align="center">
<sub>© 2026 Orbis Linux — Free. Open. For everyone.</sub>
</div>
