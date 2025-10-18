<h1 align="center">
  <span style="background: linear-gradient(90deg, #00fff0, #ff00ff, #ffd700); -webkit-background-clip: text; -webkit-text-fill-color: transparent;">LumiTracker</span>
</h1>

<p align="center">
  <strong>Real-time Light + Motion Visualizer — No After Effects. No TouchDesigner. Just Your Browser.</strong><br>
  <a href="https://paprika1212.github.io/lumi_tracker/">→ Try it now</a>
</p>

---

## ✨ What is LumiTracker?

**LumiTracker** turns your camera feed into a living, breathing mesh of **glowing lines, numbers, and motion-reactive visuals** — all in your browser.  
It’s built for creators who want that *music-video-like light tracking aesthetic* without opening heavy tools like **Adobe After Effects** or **TouchDesigner**.

🪄 Just open the link : [**LumiTracker**](https://paprika1212.github.io/lumi_tracker/)  → grant camera access → move lights around → and watch visuals come alive.

---

## 🎥 Features

-  **Real-time Controls** — tweak parameters like brightness, motion, contrast, and more  
-  **Contrast Boost** — helps capture LED or low-light visuals better  
-  **Custom Colors** — select glow and text colors to match your vibe  
-  **Blocks / Windows Modes** — geometric visual overlays or pixel “windows”  
-  **Lines + Link Density** — control the number and reach of glowing connections  
-  **Record** — save your visuals as `.webm` videos directly from your browser  
-  **No Installations** — everything runs locally in the browser, GPU-accelerated  

---

## 🧠 How It Works

1. LumiTracker uses your **device camera** through the `MediaDevices API`.  
2. It processes frames in real time to detect **light intensity + motion**.  
3. Detected points are turned into **dynamic meshes, lines, and glowing sprites** rendered using **Three.js**.  
4. You can fully customize the look through the live control panel.  

---

## 🎚️ Controls Explained

| Control | Description |
|----------|--------------|
| **Threshold** | Minimum brightness needed to detect a point |
| **Motion** | How sensitive the system is to movement |
| **Contrast** | Increases video clarity (helps in dark rooms) |
| **Points** | Number of motion points being tracked |
| **Size** | Size of numbers / particles |
| **Lines** | Number of line connections drawn |
| **Link Density** | Maximum distance between two connected points |
| **Blocks / Windows** | Switch between two overlay styles |
| **Record** | Start/stop recording and automatically download your clip |

---

## 📱 How to Use (on Phone)

> ⚡ The easiest setup: No installs. No coding. Just open the link.

1. Open 👉 [**LumiTracker on GitHub Pages**](https://paprika1212.github.io/lumi_tracker/)  
2. Grant **Camera Permission** when prompted.  
3. **Tap the screen** once if nothing appears (especially on iPhone Safari).  
4. For smoother performance and privacy, open it in **Incognito Mode**.  
5. Adjust sliders — move a light or your hand — and watch the visuals react.  
6. Hit **Record** to download your video directly.

💡 **Pro Tip:** Works best in dim lighting with a few focused light sources (phone flash, LED, etc).

---

## 🚀 Quick Start (for developers)

```bash
git clone https://github.com/paprika1212/lumi_tracker.git
cd lumi_tracker
