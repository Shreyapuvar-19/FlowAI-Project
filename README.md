# 🚦 FlowAI — Traffic Intelligence System

A real-time AI-powered traffic route analysis system for **Ahmedabad & Gandhinagar**, built as a single-file web app — no build step, no dependencies to install.

![FlowAI](https://img.shields.io/badge/FlowAI-v2.0-6366f1?style=flat-square)
![Leaflet](https://img.shields.io/badge/Map-Leaflet%201.9.4-34d399?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)

---

## ✨ Features

- 🗺️ **Real-Road Routing** — Leaflet map with CartoDB dark tiles + GPS-accurate node positions
- ⚡ **Dijkstra's Algorithm** — Shortest path across a 30-node weighted graph
- 🤖 **AI Flow Recommendations** — Congestion prediction, signal timing, load redistribution
- 📊 **Live Dashboard** — Session stats, route history, hourly traffic index chart
- 🔔 **Notifications Panel** — Real-time alerts from route analysis
- 🔐 **Auth System** — Login + Sign Up with password strength meter
- 📱 **Responsive** — Works on mobile, tablet, and desktop

---

## 🚀 Quick Start

No install needed. Just open in a browser:

```bash
# Option 1 — open directly
open index.html

# Option 2 — serve locally (recommended)
npx serve .
# or
python3 -m http.server 8080
# then visit http://localhost:8080
```

**Demo credentials:** `admin` / `1234`

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| UI | Vanilla HTML + CSS + JavaScript |
| Map | Leaflet.js 1.9.4 + CartoDB Dark tiles |
| Algorithm | Dijkstra (min-heap priority queue) |
| Fonts | Syne, Manrope, JetBrains Mono (Google Fonts) |
| Routing | GPS-coordinated node graph (30 nodes, ~60 edges) |

---

## 📁 Project Structure

```
flowai-project/
├── index.html          # Entire app — HTML + CSS + JS in one file
├── README.md           # This file
├── .gitignore          # Standard web .gitignore
└── LICENSE             # MIT License
```

---

## 📊 Graph Coverage

- **30 nodes** — Ahmedabad + Gandhinagar metro area
- **~60 bidirectional edges** with real km distances and traffic tier weights
- Key nodes: Ellis Bridge, Chandkheda, Science City, Vatva GIDC, Gandhinagar Sectors 7/11/16/21/28, GIFT City

---

## 🌐 Deploy

### GitHub Pages (free)
1. Push to GitHub
2. **Settings → Pages → Source: main / root**
3. Live at `https://yourusername.github.io/flowai-project/`

### Netlify Drop
Drag the folder to [netlify.com/drop](https://app.netlify.com/drop) — live in 30 seconds.

---

## 📝 License

MIT — free to use, modify, and distribute.
