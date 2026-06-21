# 📱 Rozana Khaata – POS & Inventory Management

[![Flutter](https://img.shields.io/badge/Flutter-3.16-blue.svg)](https://flutter.dev)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

## 📖 Overview

**Rozana Khaata** is a production-ready POS application for small businesses in Pakistan. It handles daily sales, inventory, and udhar (credit) management - all working offline.

> **🚀 Live in Production**  
> Currently serving 50+ businesses across Pakistan

---

## ✨ Key Features

### 🛒 Sales Management
- Complete cart system
- Item & cart-level discounts
- Cash & Credit payments
- Sales history & refunds

### 👥 Udhar (Credit) Management
- Customer profiles
- Balance tracking
- Partial payments
- Due date tracking

### 📦 Inventory Control
- Add/Edit/Delete products
- Stock adjustments
- Low-stock alerts
- Product categories

### 🖨️ Printing System
- Bluetooth thermal printing
- ESC/POS support
- TSPL support (Zebra)
- PDF bill generation

### 📊 Analytics Dashboard
- Daily/Weekly/Monthly sales
- Top selling items
- Payment distribution
- Customer insights

### 💾 Backup & Restore
- One-tap backup
- Email backup
- One-tap restore

---

## 🏗️ Technology Stack

| Layer | Technology |
|-------|------------|
| Frontend | Flutter 3.x (Dart) |
| State Management | Provider |
| Local Database | SQLite (sqflite) |
| Authentication | Firebase Auth |
| Cloud | Cloud Firestore |
| Printing | ESC/POS + TSPL |
| PDF Generation | pdf package |

## 📸 Screenshots

<div align="center">
  
| 🏠 Home | 📊 Dashboard | 🛒 Sales | 📜 History | 📦 Inventory | ⚙️ Settings | 💰 Udhar |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| <img src="screenshots/home_screen.jpeg" width="80"> | <img src="screenshots/Dashboard_screen.jpeg" width="80"> | <img src="screenshots/sales_screen.jpeg" width="80"> | <img src="screenshots/Sales_history_screen.jpeg" width="80"> | <img src="screenshots/inventory_screen.jpeg" width="80"> | <img src="screenshots/Setting_Screen.jpeg" width="80"> | <img src="screenshots/udhar_payments_screen.jpeg" width="80"> |

</div>


  


## 🔒 Source Code Access

**This repository is for public showcase only.**

The full source code is maintained in a **private repository** to protect:
- 🔐 Business logic
- 🔐 Client data
- 🔐 Firebase credentials

### Request Access
1. Connect on [LinkedIn](https://www.linkedin.com/in/ibrahim-zia-b13894408?utm_source=share_via&utm_content=profile&utm_medium=member_android)
2. Email: ibrahimzia889@gmail.com

> **Note:** Access granted on a case-by-case basis.

---

# 📁 rozana-khaata-portfolio — Repository Structure

```
rozana-khaata-portfolio/
│
├── README.md                          # 📄 Main documentation
├── LICENSE                            # ⚖️ MIT License
├── CONTRIBUTING.md                    # 🤝 Contribution guidelines
├── CHANGELOG.md                       # 📋 Version history
├── .gitignore                         # 🚫 Git ignore rules
│
├── docs/
│   └── architecture.md               # 🏗️ Architecture details
│
├── screenshots/                       # 📸 App screenshots
│   ├── home_screen.jpeg
│   ├── Dashboard_screen.jpeg
│   ├── sales_screen.jpeg
│   ├── Sales_history_screen.jpeg
│   ├── inventory_screen.jpeg
│   ├── Setting_Screen.jpeg
│   └── udhar_payments_screen.jpeg
│
├── lib/                               # 💙 Flutter source code
│   ├── core/                         # 🔧 Theme, constants, DI, Firebase
│   ├── features/                     # ✨ Feature-first modules
│   │   ├── auth/                     # 🔐 Login, signup, auth wrapper
│   │   ├── onboarding/               # 🚬 Quit date, smoking data, summary
│   │   ├── dashboard/                # 🏠 Home screen + live AppDataCon
│   │   ├── achievements/             # 🏆 20-badge achievement engine
│   │   ├── health/                   # ❤️ WHO health benefit timeline
│   │   ├── progress/                 # 📊 Periodic statistics
│   │   ├── settings/                 # ⚙️ App settings & profile
│   │   └── account_linking/          # 🔗 Guest → Google upgrade
│   ├── routes/                       # 🗺️ Named routes
│   └── shared/                       # 🧩 Models, repos, services, utils
│
└── .github/
    ├── ISSUE_TEMPLATE/
    │   ├── bug_report.md             # 🐛 Bug report template
    │   └── feature_request.md        # 💡 Feature request template
    └── workflows/
        └── build.yml                 # 🔄 CI/CD build workflow
```

---

## 📂 Folder Descriptions

| Folder / File | Description |
|---|---|
| `README.md` | Main project documentation |
| `LICENSE` | MIT open source license |
| `CONTRIBUTING.md` | How to contribute to the project |
| `CHANGELOG.md` | All version history and release notes |
| `.gitignore` | Files/folders excluded from Git tracking |
| `docs/architecture.md` | App architecture explanation |
| `screenshots/` | All app UI screenshots (JPEG format) |
| `lib/core/` | Theme, constants, DI container, Firebase config |
| `lib/features/` | Feature-first modular architecture |
| `lib/features/auth/` | Login, signup, authentication wrapper |
| `lib/features/onboarding/` | Quit date setup, smoking data, summary |
| `lib/features/dashboard/` | Home screen with live data connection |
| `lib/features/achievements/` | 20-badge achievement engine |
| `lib/features/health/` | WHO-based health benefit timeline |
| `lib/features/progress/` | Periodic statistics and tracking |
| `lib/features/settings/` | App settings & user profile |
| `lib/features/account_linking/` | Guest to Google account upgrade |
| `lib/routes/` | Named routes for navigation |
| `lib/shared/` | Shared models, repositories, services, utils |
| `.github/ISSUE_TEMPLATE/` | GitHub issue templates |
| `.github/workflows/build.yml` | GitHub Actions CI/CD pipeline |
```
