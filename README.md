Of course\! Here is the complete Markdown code for the README file. You can copy and paste this directly into your `README.md` file.

````markdown
<h1 align="center">
  <span style="background: linear-gradient(90deg, #00fff0, #ff00ff, #ffd700); -webkit-background-clip: text; -webkit-text-fill-color: transparent;">LumiTracker</span>
</h1>

<p align="center">
  <strong>Real-time light and motion art in your browser.</strong>
  <br>
  LumiTracker tracks the motion of light particles, inspired by the mesmerizing glow of Diwali lights, to create stunning visuals on the fly.
  <br>
  <a href="https://paprika1212.github.io/lumi_tracker/"><strong>→ Try it Live</strong></a>
</p>

---


**LumiTracker** turns your camera into a canvas for light art.

Get that cool, music-video-style light tracking effect without needing heavy software like **After Effects** or **TouchDesigner**. Just open the link, point your camera at a light, and watch the magic happen.

---

## 🎥 Features

-   **Live Controls**: Tweak brightness, motion, contrast, and more on the fly.
-   **Custom Colors**: Pick glow and text colors to match your vibe.
-   **Visual Modes**: Switch between numbers, lines, geometric blocks and pixel "windows".
-   **Built-in Recording**: Save your creations as `.webm` videos directly from your browser.
-   **Runs Anywhere**: No installs needed. Everything runs locally on your device, GPU-accelerated.

---

## 🧠 How It Works

1.  It grabs your **device's camera** feed.
2.  It detects **bright spots and movement** in real-time.
3.  It uses **Three.js** to turn those points into glowing lines, numbers, and meshes.
4.  You control the final look with the live sliders.

---

## 🎚️ Controls Explained

| Control          | Description                                    |
| ---------------- | ---------------------------------------------- |
| **Threshold** | Minimum brightness needed to detect a point    |
| **Motion** | How sensitive the system is to movement        |
| **Contrast** | Increases video clarity (great for dark rooms) |
| **Points** | Number of motion points being tracked          |
| **Size** | Size of the numbers or particles               |
| **Lines** | Number of line connections drawn               |
| **Link Density** | How far lines can stretch to connect points    |
| **Record** | Start/stop recording and download your clip    |

---

## 🚀 How to Use

1.  Open 👉 [**LumiTracker**](https://paprika1212.github.io/lumi_tracker/)
2.  Grant **camera permission**.
3.  Point it at a light source (your phone's flashlight works great!).
4.  Play with the sliders to change the look.
5.  Hit **Record** to save your video.

💡 **Pro Tip:** Works best in a dim room with a bright, focused light.

---

## 💻 For Developers

```bash
git clone [https://github.com/paprika1212/lumi_tracker.git](https://github.com/paprika1212/lumi_tracker.git)
cd lumi_tracker
# Open index.html in your browser
````

```
```
