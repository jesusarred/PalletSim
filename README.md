# PalletSim 3D

Interactive 3D pallet simulation tool built for logistics and packaging optimization.

## Features

- 🎲 **3D visualization** — Three.js real-time rendering with drag-to-rotate and scroll-to-zoom
- 📦 **3 packing configurations** — L×W Standard, W×L Rotated, Brick Pattern with smart feedback
- 📐 **Pallet options** — Standard US (40"×48") or fully custom dimensions
- ⚔️ **Competitor comparison** — Side-by-side 3D view vs TM (or any competitor)
- 🧪 **ETO Sterilization analysis** — Chamber fit, gas flow, weight, stability checks
- ⚠️ **Waste overlay** — Red highlight shows unused pallet surface
- ➡️ **Orientation arrows** — Per-box arrows show box length direction on every layer
- 📏 **CM / IN toggle** — Switch units at any time
- 🏷️ **Simulation title** — Label your simulation as an overlay on the 3D view

## Deploy

Deployed on Vercel. Visit: **[your-url].vercel.app**

## Usage

1. Set box dimensions (L × W × H)
2. Choose pallet size (Standard US or Custom)
3. Optionally set ETO chamber dimensions and box weight
4. Press **SIMULATE**
5. Compare Config A / B / C in the bottom bar
6. Click **⟺ Side by Side** to compare against competitor
7. Click **⚔️ vs TM** to open the metrics scorecard

## Local use

Just open `index.html` in any browser — no server needed.

## Built with

- [Three.js r128](https://threejs.org/)
- [Google Fonts — Syne + DM Mono](https://fonts.google.com/)
- Vanilla HTML/CSS/JS — zero dependencies

---

Built by Jesus Arredondo — Avanos Medical Tijuana
