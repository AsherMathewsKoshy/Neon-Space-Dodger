````markdown
# 🚀 Neon Space Dodger

<div align="center">

<img src="https://img.shields.io/badge/🎮-Arcade_Game-06b6d4?style=for-the-badge" />
<img src="https://img.shields.io/badge/⚡-Vanilla_JavaScript-6366f1?style=for-the-badge" />
<img src="https://img.shields.io/badge/🌐-HTML5-EF4444?style=for-the-badge" />
<img src="https://img.shields.io/badge/🎨-CSS3-A855F7?style=for-the-badge" />

<br><br>

### 🌌 Dodge. Survive. Beat Your High Score.

A colorful neon arcade game where you pilot a spaceship through an endless asteroid field.

**How long can you survive?**

<br>

⭐ **Single-file game • Zero dependencies • Runs directly in your browser**

</div>

---

## ✨ About

**Neon Space Dodger** is a lightweight browser-based arcade game built entirely with **HTML, CSS, and JavaScript**.

The objective is simple:

> 🚀 Control your spaceship  
> ☄️ Dodge incoming asteroids  
> 💥 Survive as long as possible  
> 🏆 Beat your high score

The game uses the HTML5 Canvas API for real-time rendering, animations, particles, collision detection, and the neon visual effects.

---

## 🎮 Gameplay

Your spaceship starts at the bottom of the screen while asteroids continuously fall from above.

As you survive:

```text
TIME SURVIVED
      ↓
    SCORE
      ↓
DIFFICULTY ↑
      ↓
ASTEROIDS FASTER
      ↓
    💀 ???
````

The longer you survive, the more challenging the game becomes.

One collision ends the mission.

---

## 🌈 Features

| Feature              | Description                                         |
| -------------------- | --------------------------------------------------- |
| 🚀 Spaceship         | Smooth player movement with animated engine effects |
| ☄️ Asteroids         | Randomly generated obstacles with different shapes  |
| 🌌 Starfield         | Animated background stars                           |
| 💫 Particles         | Explosion and movement particle effects             |
| 📈 Score System      | Score increases as you survive                      |
| 🏆 High Score        | Best score is saved locally                         |
| ⚡ Dynamic Difficulty | Asteroids become progressively faster               |
| ⏸️ Pause             | Pause and resume the game                           |
| 🔄 Restart           | Restart the mission instantly                       |
| 📱 Mobile Controls   | Touch-friendly movement buttons                     |
| 🎨 Neon UI           | Gradient-based arcade interface                     |
| 📦 Zero Dependencies | No libraries or packages required                   |

---

## 🕹️ Controls

### 💻 Desktop

| Key     | Action          |
| ------- | --------------- |
| `←`     | Move left       |
| `→`     | Move right      |
| `A`     | Move left       |
| `D`     | Move right      |
| `SPACE` | Pause / Resume  |
| `P`     | Pause / Resume  |
| `ENTER` | Start / Restart |

### 📱 Mobile

Use the on-screen:

`◀` **Left**     **Right** `▶`

buttons.

---

## 🎨 Visual Design

The game uses a futuristic neon-inspired interface featuring:

* 🌊 Cyan gradients
* 🔵 Deep space backgrounds
* 🟣 Purple highlights
* 💎 Glass-like UI panels
* ✨ Glowing particles
* 🌌 Animated stars
* 🚀 Neon spaceship effects
* ☄️ Glowing asteroid effects

The goal was to make a simple game feel like a small arcade interface rather than a plain HTML project.

---

## 🧠 How It Works

The game is rendered using the browser's **HTML5 Canvas API**.

### Game Loop

```text
        ┌──────────────────┐
        │   Start Game     │
        └────────┬─────────┘
                 ↓
        ┌──────────────────┐
        │   Read Controls  │
        └────────┬─────────┘
                 ↓
        ┌──────────────────┐
        │ Update Game State│
        └────────┬─────────┘
                 ↓
        ┌──────────────────┐
        │ Spawn Asteroids  │
        └────────┬─────────┘
                 ↓
        ┌──────────────────┐
        │ Check Collision  │
        └────────┬─────────┘
                 ↓
        ┌──────────────────┐
        │ Render Canvas    │
        └────────┬─────────┘
                 ↓
             Repeat 🔄
```

The animation loop is driven by:

```javascript
requestAnimationFrame()
```

which allows the game to update and render smoothly according to the browser's refresh cycle.

---

## 🛠️ Technology Stack

### Frontend

* **HTML5**
* **CSS3**
* **JavaScript**
* **HTML5 Canvas API**

### Browser APIs

* `CanvasRenderingContext2D`
* `requestAnimationFrame`
* `localStorage`
* `Pointer Events`

No external frameworks are required.

---

## 📂 Project Structure

```text
neon-space-dodger/
│
└── index.html
```

That's it.

The entire game is contained in a single file.

```text
HTML
 ├── Interface
 └── Game Canvas

CSS
 ├── Neon Theme
 ├── Responsive Layout
 └── Animations

JavaScript
 ├── Game Engine
 ├── Player
 ├── Asteroids
 ├── Collision Detection
 ├── Particles
 ├── Score System
 ├── Controls
 └── Local High Score
```

---

## 🚀 Run Locally

No installation is required.

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/neon-space-dodger.git
```

### 2. Open the project

```bash
cd neon-space-dodger
```

### 3. Launch the game

Simply open:

```text
index.html
```

in any modern web browser.

That's it. 🎮

---

## 💾 High Score

Your best score is stored using the browser's:

```javascript
localStorage
```

This means the high score remains available even after refreshing the page.

No database or server is required.

---

## 📱 Responsive Design

The interface automatically adapts to smaller screens.

```text
Desktop
   ↓
Keyboard Controls

Mobile
   ↓
Touch Controls
```

The game can therefore be played on both desktop and mobile browsers.

---

## 🎯 Learning Objectives

This project was built to practice:

* JavaScript game loops
* Canvas rendering
* Object movement
* Collision detection
* Randomized object generation
* Particle effects
* Keyboard event handling
* Touch/pointer events
* Local browser storage
* Responsive UI design
* CSS gradients and visual effects

---

## 🔮 Future Improvements

Possible additions:

* [ ] 🔊 Sound effects
* [ ] 🎵 Background music
* [ ] 🛡️ Shield power-up
* [ ] ⚡ Speed boost
* [ ] 💎 Collectible crystals
* [ ] 👾 Different enemy types
* [ ] 🏆 Online leaderboard
* [ ] 🎨 Multiple spaceship skins
* [ ] 🌌 Multiple space environments
* [ ] 🥇 Achievement system
* [ ] 🎮 Difficulty selection
* [ ] 📊 Detailed statistics

---

## 📸 Screenshots

Add screenshots of the game here after playing it:

```text
screenshots/
├── gameplay.png
├── game-over.png
└── mobile.png
```

Example:

```markdown
![Gameplay](screenshots/gameplay.png)
```

---

## ⚡ Performance

The game is intentionally lightweight.

There are:

* ❌ No frameworks
* ❌ No backend
* ❌ No database
* ❌ No external assets
* ❌ No package installation

Just:

**HTML + CSS + JavaScript + Canvas**

---

## 📜 License

This project is available for educational and personal use.

---

<div align="center">

### 🚀 Keep Dodging. Keep Surviving. Keep Improving.

**Made with HTML, CSS & JavaScript**

☄️   🌌   🚀   🌌   ☄️

</div>
```
