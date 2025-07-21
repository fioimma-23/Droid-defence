# 🎮 Pixel Fighter - JavaScript Fighting Game

A retro-style 2D fighting game built with **vanilla JavaScript** and **HTML5 Canvas**, featuring animated sprite combat.

---

## ✨ Features

- ⚔️ Two-player combat (keyboard controls)  
- 🏃‍♂️ 8-directional movement with sprite animations  
- 👊 Multiple attack combos  
- ❤️ Health bar system with visual feedback  
- ⏱️ 60-second round timer  
- 🎨 Retro pixel art aesthetic

---

## 🕹️ Controls

| Player 1 | Player 2 | Action |
|----------|----------|--------|
| A / D    | ← / →    | Move   |
| W        | ↑        | Jump   |
| Space    | ↓        | Attack |

---

## 🚀 Quick Start

1. **Clone the repository**  
   ```bash
   git clone https://github.com/fioimma-23/Droid-defence.git
## 🚀 Quick Start

2. **Open `index.html`** in any modern browser  
3. **No installations or builds required**

---

## 🧠 Key Components

- **Sprite Animation System**  
  Frame-based sprite sheets with smooth transitions

- **Physics Engine**  
  Custom gravity and collision detection

- **State Machine**  
  Handles character states: idle, run, jump, attack, etc.

- **GSAP**  
  Used for smooth health bar animations

---
## 🖼️ Sprite Sheets

**Characters:**

- **Samurai Mack** (Player 1)  
- **Kenji** (Player 2)

Each character includes **8 animation states**:

- Idle  
- Run  
- Jump  
- Fall  
- Attack  
- Take Hit  
- Death  
- Special Finishers (optional)

---

> 💥 _"Finish him!"_ – Battle to the death in this JavaScript combat simulator.

---

## 🧾 Notes

- Focuses purely on the game experience  
- Uses minimal technical jargon  
- Highlights the player experience  
- Includes clear instructions  
- Maintains visual appeal with emojis  
- No frameworks – built with pure JavaScript + Canvas

---

## 📂 Project Structure

```plaintext
Droid-defence/
├── index.html         # Main game container
├── index.js           # Core game logic
├── classes.js         # Fighter and Sprite classes
├── utils.js           # Helper functions
├── img/               # Sprite assets
└── .prettierrc        # Code formatting

