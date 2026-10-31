<div align="center">

<img src="assets/banner.svg" alt="Medical Store POS" width="100%"/>

<br/>

<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js"/> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/> <img src="https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white" alt="Electron"/> <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite"/> <img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS"/>

<br/>

<img src="https://img.shields.io/badge/Status-Active%20development-success?style=flat-square" alt="status"/>
<img src="https://img.shields.io/badge/Source-Private%20(commercial)-lightgrey?style=flat-square" alt="source"/>

**[Request a live demo](https://rootocloud.com) · [Hire me](mailto:faizan.developer9200@gmail.com) · [More projects](https://github.com/MuhammadFaizan73)**

</div>

---

## 📌 Overview

A point-of-sale for pharmacies and medical stores, built with Next.js inside Electron so it runs as an offline desktop app backed by a local SQLite database.

## ✨ Key Features

### Sales
- Fast POS billing
- Returns handling
- Cashier shifts with opening and closing

### Stock
- Inventory management
- Purchases from suppliers
- Customer records

### Insights
- Sales and stock reports with charts
- Configurable store settings

## 🏗️ Architecture

```mermaid
flowchart LR
  UI[Next.js UI<br/>Tailwind + Radix] --> L[Local data layer]
  L --- DB[(SQLite)]
  subgraph Electron Desktop App
    UI
    L
    DB
  end
```

## 🧰 Tech Stack

| Layer | Technology |
|---|---|
| **Framework** | Next.js · TypeScript |
| **Desktop** | Electron |
| **UI** | Tailwind CSS · Radix UI · lucide-react |
| **State** | Zustand |
| **Database** | SQLite (better-sqlite3) |
| **Charts** | Recharts |

<!-- SCREENSHOTS -->
<!-- /SCREENSHOTS -->

## 🔒 About the Source Code

This is a **commercial / client project**, so the source code is kept in a private repository.
This page documents what the system does and how it is built.

- 🎥 **Live walkthrough** — available on request
- 💼 **Want something similar for your business?** I build custom versions of this for clients.

## 👨‍💻 Author

**Muhammad Faizan** — Founder, [Rootocloud](https://rootocloud.com)
AI agents & automation · Web & mobile apps · Custom software

[![Website](https://img.shields.io/badge/rootocloud.com-0B1220?style=for-the-badge&logo=googlechrome&logoColor=white)](https://rootocloud.com)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:faizan.developer9200@gmail.com)

<div align="center"><sub>© Muhammad Faizan. All rights reserved.</sub></div>
