# Mollier h–x Diagram Web App
*A browser-based, pressure-aware psychrometric calculator with live charting.*

## ✨ Features
- **Bidirectional solver** – Enter any two of **T** (°C), **RH** (%), and **x** (g/kg dry air). The app computes the full state: dew-point \(T_{dp}\), enthalpy \(h\), saturation \(p_{ws}\), partial vapour pressure \(p_w\), etc.
- **Altitude-aware** – Barometric pressure \(p\) is derived from **Altitude (m ASL)** via the standard-atmosphere model (no fixed sea-level assumption).
- **Live h–x chart** – Plots the current state, saturation curve, and example RH isopleths (40 % & 60 %) with dew-point and enthalpy annotations.
- **Offline** – 100 % client-side; works after first load.
- **Zero install** – Vanilla HTML/JS + Plotly.

## 🚀 Quick start
1. Clone or download this repository.
2. Open `test.html` in any modern browser (Chromium ≥102, Firefox ≥100, Safari ≥15).  
   *Tip:* serving locally avoids stricter file-URL policies:
   ```bash
   # Python 3
   python -m http.server 8000
   # then visit http://localhost:8000/test.html

