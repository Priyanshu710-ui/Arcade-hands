# 🪐 ORRERY·LIVE — Hand-Controlled Solar System

> **Your hand controls the planets.**
>
> A browser-based interactive orrery where real-time hand gestures become the controls for a living 3D solar system.

<p align="center">
  <a href="https://priyanshu710-ui.github.io/Arcade-hands/">
    <strong>🚀 OPEN THE LIVE EXPERIENCE</strong>
  </a>
</p>

<p align="center">
  🖐️ Hand Tracking &nbsp;•&nbsp; 🌍 3D Solar System &nbsp;•&nbsp; 🤏 Pinch Interaction &nbsp;•&nbsp; ✨ WebGL
</p>

---

## 🟢 Live Demo

### **[🚀 Launch ORRERY·LIVE](https://priyanshu710-ui.github.io/Arcade-hands/)**

The project is deployed with **GitHub Pages** and runs directly in the browser.

> 💡 **Best experience:** use a laptop/desktop with a webcam, good lighting, and a modern browser.

---

## 🌌 What is ORRERY·LIVE?

ORRERY·LIVE turns your webcam into a natural interface for a 3D solar system. Instead of clicking through a normal UI, you use your hand to explore the planets.

The project uses **MediaPipe Hands** to track hand landmarks in the browser and **Three.js/WebGL** to render the interactive space scene. The current experience includes the Sun, all eight planets, orbital rings, a star field, focus mode, and gesture-driven controls. fileciteturn4file0L296-L299 fileciteturn4file0L356-L364 fileciteturn4file0L395-L403

---

## ✋ Gesture Controls

| Gesture | Action |
|---|---|
| 🤏 **Pinch** | Grab and drag a planet |
| ✋ **Tilt your hand** | Rotate the solar system |
| ↕️ **Move hand up/down** | Zoom in and out |
| 👉 **Point** | Cycle through focused planets |
| ✊ **Fist** | Pause / resume planetary orbits |
| 🖐️ **Open palm** | Reset the current view |

These controls are built directly into the project's hand-processing logic, including pinch detection, finger-state detection, zoom mapping, rotation mapping, focus cycling, pause/resume, and reset behavior. fileciteturn4file0L611-L670

---

## 🪐 Explore the Solar System

The scene includes:

- ☀️ Sun with a glowing visual halo
- ☿ Mercury
- ♀ Venus
- 🌍 Earth
- ♂ Mars
- ♃ Jupiter
- ♄ Saturn with rings
- ♅ Uranus
- ♆ Neptune
- ✨ Dynamic star field
- 🎯 Planet focus mode with facts

Each planet has its own orbit, scale, color, speed, and short fact displayed when focused. fileciteturn4file0L395-L403

---

## 🎮 How to Use

1. Open the **[Live Demo](https://priyanshu710-ui.github.io/Arcade-hands/)**.
2. Allow camera access.
3. Keep your hand clearly visible and use good lighting.
4. Move your hand to rotate and zoom the system.
5. Pinch to grab a planet.
6. Point to cycle focus.
7. Make a fist to pause or resume the orbits.
8. Open your palm to reset the view.

The app includes a mouse fallback as well, so the experience can still be explored without camera tracking. fileciteturn4file0L793-L815

---

## ⚙️ Built With

- **HTML5**
- **CSS3**
- **JavaScript**
- **Three.js** — 3D rendering and scene management
- **WebGL** — accelerated graphics
- **MediaPipe Hands** — real-time hand landmark tracking
- **GitHub Pages** — deployment

The project loads Three.js and MediaPipe Hands directly in the browser and initializes hand tracking from the webcam. fileciteturn4file0L287-L299 fileciteturn4file0L724-L785

---

## 🔐 Privacy

Camera access is used for the live hand-tracking experience in the browser. The interface explicitly describes the tracking as local to the browser and states that the camera feed is not recorded or sent elsewhere. fileciteturn4file0L267-L282

---

## 🚀 Run Locally

```bash
git clone https://github.com/Priyanshu710-ui/Arcade-hands.git
cd Arcade-hands
```

Then serve the project with a local development server such as **VS Code Live Server** and open the provided localhost URL.

> Camera access works best from `https://` or a local development server such as `http://localhost` / `http://127.0.0.1`.

---

## 📁 Project Structure

```text
Arcade-hands/
│
├── index.html     # Interactive 3D solar system
└── README.md      # Project documentation
```

---

## ✨ Why this project?

ORRERY·LIVE explores a simple idea:

> **What if your hands were the controller for a digital universe?**

It combines computer vision, creative coding, 3D graphics, and human-computer interaction into one browser experience.

---

<p align="center">
  <strong>Made with curiosity, code, and a little cosmic chaos. 🌌</strong>
  <br><br>
  ⭐ If you enjoy the project, consider giving the repository a star.
</p>
