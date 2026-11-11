# 🏏 3D Hand Cricket: Toss & Match

A modern, responsive, 3D WebGL implementation of the classic **Hand Cricket (Odd-Even Cricket)** game built with **Three.js** and the **Web Audio API**.

Playable seamlessly on **PC, iPhone, iPad, Android Phones & Tablets**.

---

## 🌟 Features

* **🪙 3D Physics Coin Toss:**
  * Real 3D gold coin that flips in mid-air with tumbling physics, shadow projection, and metallic chime sound.
  * Pick **Heads** or **Tails** and choose to **Bat** or **Bowl**.
* **🖐️ 3D Articulated Hands:**
  * Two 3D hands facing each other over the pitch.
  * Real-time finger gestures (1 to 6) dynamically unfolding in sync with the delivery.
* **🏟️ 3D Stadium & Environment:**
  * Green turf pitch with clay strip, crease markings, wooden stumps & bails, and floodlight glow.
* **🔊 Built-in Web Audio FX (Zero External Files):**
  * Synthetic audio generation: coin clinking, bat hit crack, umpire whistle, crowd cheering for 4s and 6s, and countdown ticks.
* **📱 Universal Cross-Device Compatibility:**
  * **Phones & Tablets:** Large thumb-friendly touch pads (1-6) with haptic vibration support.
  * **PC:** Play with mouse clicks or keyboard number keys (`1`, `2`, `3`, `4`, `5`, `6`).
* **🧠 Adaptive AI:**
  * Three difficulty levels: **Easy**, **Pro**, and **Legend** (actively tracks player tendencies and attempts mind games).
* **📊 Broadcast LED HUD:**
  * Current score, overs, target, required run rate, ball-by-ball timeline dots, and dynamic outcome banners (`SIX!`, `FOUR!`, `OUT! 💥`).

---

## 🚀 How to Run

### 1. Locally on your PC
Simply open `index.html` in any web browser, or run a local server:
```bash
python -m http.server 8080
```
Then visit:
* **PC:** `http://localhost:8080`
* **Phone / Tablet / iPad on same Wi-Fi:** `http://<your-local-ip>:8080`

### 2. Play Online (GitHub Pages)
Push this folder to a GitHub repository and turn on **GitHub Pages** under `Settings > Pages > Deploy from branch (main)`. Anyone can play on their phone or computer via your GitHub Pages link!

