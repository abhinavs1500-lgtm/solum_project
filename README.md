# SOLUM — Land Intelligence & Civic Decision Support

> **One view. Every layer. A safer tomorrow.**
> Built for Tamil Nadu communities, municipal teams, and planners.
> Hosted directly via [GitHub Pages](https://abhinavs1500-lgtm.github.io/solum_project/).

---

## 🌐 Live Web Application

- **Production URL**: [https://abhinavs1500-lgtm.github.io/solum_project/](https://abhinavs1500-lgtm.github.io/solum_project/)
- **Core Pages**:
  - **Home**: [index.html](https://abhinavs1500-lgtm.github.io/solum_project/) — Hazard news, live weather forecasts, 3D animated city stories, trust verification.
  - **Prepare**: [prepare.html](https://abhinavs1500-lgtm.github.io/solum_project/prepare.html) — Photorealistic 3D terrain mesh (Google Maps 3D Platform), 24-hour scenario simulation timeline, emergency preparation checklists, and the Ask SOLUM guide.
  - **Resolve**: [resolve.html](https://abhinavs1500-lgtm.github.io/solum_project/resolve.html) — Neighbourhood repair priorities, issue tracking for Tamil Nadu districts, complaint raising with geo-coordinates and photo evidence.
  - **Report**: [report.html](https://abhinavs1500-lgtm.github.io/solum_project/report.html) — Pre-construction land assessment, terrain elevation, slope, waterbody buffer calculation.
  - **Officials**: [officials.html](https://abhinavs1500-lgtm.github.io/solum_project/officials.html) — Municipal coordination workspace, progress tracking with interactive checkout boxes, resource budget allocation, and immutable audit history.

---

## ⚡ Architecture & Deployment

This repository contains the standalone, fully-functional SOLUM frontend web application configured specifically for direct hosting on **GitHub Pages** (`github.io`).

- **Static Hosting**: Powered by GitHub Pages (`main` branch, root `/`).
- **No External Build Dependency**: Pure vanilla modern JavaScript, CSS, and SVG assets.
- **Direct Live Weather**: Integrated with Open-Meteo live API directly from the browser with graceful fallback to bundled static snapshots.
- **Geocoding & Maps**: Embedded Google Maps 3D Platform integration with Copernicus DEM elevation data.
- **Persistent Backend Connect**: Includes an in-app "Connect Backend" dialog to seamlessly pair with any deployed FastAPI backend instance.
- **No Netlify Dependencies**: Free of Netlify CLI, serverless functions, or Netlify headers.

---

## 🛠 Enabling GitHub Pages

1. Go to repository **Settings** > **Pages**.
2. Under **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: **`main`** / folder: **`/(root)`**
3. Click **Save**.
4. Your site will be published at `https://abhinavs1500-lgtm.github.io/solum_project/`.

---

© 2026 SOLUM. All rights reserved.
