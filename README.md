# ⚡ EV Charger Repair Pro

A Progressive Web App (PWA) providing a comprehensive professional troubleshooting and repair manual for e-bike SMPS chargers.

![License](https://img.shields.io/badge/license-MIT-green)
![PWA](https://img.shields.io/badge/PWA-Installable-blue)

## 📋 Features

- **Complete Repair Guide** - Based on professional SMPS charger repair expertise
- **Offline Access** - Works without internet once installed
- **Mobile Optimized** - Responsive design for phone, tablet, and desktop
- **Searchable Content** - Quick topic search across all sections
- **Installable PWA** - Add to home screen like a native app

## 📖 Guide Contents

| Section | Description |
|---------|-------------|
| 🔋 Charger Overview | Specifications, supported faults, model reference |
| 🧩 Block Diagram | Visual power flow from AC input to DC output |
| 📐 Schematic Diagram | Traced circuit with UC384X pinout |
| ⚡ AC Voltage Flow | Test points with expected readings (220V -> 320V DC) |
| 🔋 DC Conversion | Rectification, filtering, switching, feedback explained |
| 🔧 Component Analysis | 12+ components: function, failure, testing method |
| 📟 Multimeter Testing | Step-by-step procedures with expected/fault readings |
| 🔍 Troubleshooting | Decision flowcharts for common problems |
| ⚠️ Common Faults | 8 detailed fault analyses with repair guidance |
| 🛠️ Repair Procedure | 9-step professional repair process |
| 🛡️ Safety Guidelines | High voltage warnings, emergency procedures |

## 🚀 Quick Start

### Use Online
Visit: `https://YOUR_USERNAME.github.io/ev-charger-repair-guide/`

### Install as App
- **Android**: Chrome menu -> "Add to Home screen"
- **iPhone**: Safari Share -> "Add to Home Screen"
- **Desktop**: Chrome address bar -> Install icon

## 🛠️ Tech Stack

- Pure HTML5, CSS3, JavaScript (no frameworks)
- Service Worker for offline caching
- Web App Manifest for PWA installability
- GitHub Pages for free hosting

## 📁 Repository Structure

```
├── index.html          # Main application
├── manifest.json       # PWA manifest
├── sw.js              # Service worker
├── offline.html       # Offline fallback
├── DEPLOY-GUIDE.txt   # Deployment instructions
├── README.md          # This file
└── icons/             # App icons
    ├── icon-72.png
    ├── icon-96.png
    ├── icon-128.png
    ├── icon-192.png
    └── icon-512.png
```

## ⚠️ Safety Disclaimer

This guide involves **lethal high voltages** (220-240V AC, 310-325V DC). Only qualified individuals should attempt repairs. Always follow safety procedures including capacitor discharge, series bulb testing, and proper protective equipment.

## 📄 License

MIT License - Free for personal and commercial use.

## 🙏 Credits

Based on professional e-bike charger repair documentation and SMPS design principles using UC384X PWM controllers.

---

**⚡ Repair Safely. Charge Confidently.**