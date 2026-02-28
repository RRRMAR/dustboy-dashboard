<div align="center">
  <h1>🌐 NEURAL-DUST: 3D Visualization Dashboard</h1>
  <p>A Sci-Fi themed, interactive WebGL 3D Data Visualizer for live PM2.5/PM10 MQTT streams.</p>

  [![Launch Dashboard](https://img.shields.io/badge/LAUNCH_SYSTEM-NEURAL_DUST-00ffcc?style=for-the-badge&logo=shazam&logoColor=black)](https://rrrmar.github.io/dustboy-dashboard/)
</div>

---

## 🛰️ Access the Live Uplink
**Click here to launch:** [**NEURAL-DUST 3D Dashboard**](https://rrrmar.github.io/dustboy-dashboard/)

## 📝 Features & Aesthetics
- **Sci-Fi Cyber Grid:** A dark immersive environment built with Three.js rendering an endless digital grid and rotating energy cores.
- **Real-Time Data Streams:** Direct WebSocket subscription to the `DUSTBOY` hardware MQTT endpoints.
- **Dynamic 3D Nodes:** Every incoming sensor payload constructs an energy pillar in 3D space. 
- **Hazard Color Coding:** Pillars glow based on PM2.5 severity:
  - 🟢 **Safe:** ≤ 50 AQI
  - 🟡 **Warning:** 51 - 100 AQI
  - 🔴 **Danger:** > 100 AQI
- **Hacker UI Overlay (HUD):** A glassmorphism interface displaying a live scrolling telemetry feed and an auto-sorting leaderboard of the Top 5 most hazardous zones.

## 🕹️ Controls
* **[Left Mouse Button]** - Orbit & Rotate Camera
* **[Right Mouse Button]** - Pan Camera
* **[Mouse Scroll]** - Zoom In / Out

## 🛠️ Technology Stack
* **HTML5 Canvas & CSS3 Glassmorphism**
* **JavaScript (ES Modules)**
* **Three.js** (WebGL Rendering Engine)
* **Paho MQTT** (WebSocket Client Protocol)

---
<div align="center">
  <i>"Reflecting pure data as aesthetic light."</i>
</div>
