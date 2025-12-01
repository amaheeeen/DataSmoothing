# 🚀 DataSmoothing

[![HTML](https://img.shields.io/badge/Language-HTML-orange)](https://github.com/amaheeeen/DataSmoothing)  
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Enable-blue)](https://amaheeeen.github.io/DataSmoothing/)  
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

An interactive browser demo to explore and visualize data smoothing techniques — no backend required. Use sample CSVs or paste your own data, tweak parameters, and see results instantly.

✨ Highlights
- 🔬 Visualize original vs. smoothed series
- ⚙️ Multiple smoothing algorithms with adjustable params
- 📥 Import CSV | 📤 Export smoothed CSV
- 🌐 Pure client-side — works offline after download

---

## 📂 Live Demo
If you enable GitHub Pages for this repo, view the demo at:
https://amaheeeen.github.io/DataSmoothing/

Tip: Enable Pages from the repository settings, set branch to `main` and folder to `/` or `/docs`.

---

## 📋 Table of Contents
- [Getting started](#-getting-started)
- [Usage](#-usage)
- [Supported smoothing methods](#-supported-smoothing-methods)
- [Example CSV formats](#-example-csv-formats)
- [File structure (expected)](#-file-structure-expected)
- [Contributing](#-contributing)
- [License](#-license)
- [Author & Contact](#-author--contact)

---

## ⚡ Getting started

Prerequisites
- Modern web browser (Chrome, Firefox, Edge, Safari)

Run locally
1. Clone the repo
   git clone https://github.com/amaheeeen/DataSmoothing.git
2. Open the demo:
   - Option A: Double-click index.html to open in your browser  
   - Option B (recommended for full browser features):
     python3 -m http.server 8000
     open http://localhost:8000

---

## 🧭 Usage

1. Open index.html in the browser.
2. Load a CSV or paste your series into the input area.
3. Select a smoothing method from the UI.
4. Adjust parameters (window size, smoothing factor, polynomial order, etc.).
5. Compare original vs. smoothed plots.
6. Export smoothed results as CSV or copy to clipboard.

---

## 🧰 Supported smoothing methods
(Adjust this list to reflect what's actually implemented in your repo)
- 🔁 Moving Average (simple / centered)
- ✨ Exponential Smoothing (single)
- 🧮 Savitzky–Golay filter
- 🪄 (Add other methods here)

---

## 🧩 Example CSV formats

Two common forms supported (adjust parser to match your implementation):

With headers:
timestamp,value
2025-01-01,10
2025-01-02,12

Single-column values:
10
12
11
15

Two-column no-headers:
10,12,11,15,14

---

## 📁 File structure (suggested)
- index.html — main demo page
- assets/
  - css/ — styles
  - js/ — smoothing algorithms & plotting
  - data/ — sample CSVs
- README.md — this file
- LICENSE — license file

Update to reflect the actual repository layout.

---

## 🎨 Tips for making the demo nicer
- Add a short animated GIF or image showing the UI in action (place in `/assets/img/demo.gif`).
- Use a lightweight charting lib (Chart.js, Plotly, or similar) for interactive zoom & hover tooltips.
- Provide example CSV files in `/assets/data/` for quick testing.
- Add keyboard shortcuts (space to pause animation or left/right to step) for demo mode.

---

## 🤝 Contributing
Contributions welcome!  
- Open an issue for bugs or feature requests.
- Fork, create a branch, add changes, and submit a pull request.
- Include sample data & tests when adding algorithms.

---

## 📜 License
Choose a license (e.g., MIT). Add a LICENSE file if you haven't already.

---

## 👤 Author
amaheeeen — https://github.com/amaheeeen
