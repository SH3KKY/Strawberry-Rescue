# 🍓 Strawberry Rescue

A tiny browser platformer built with **vanilla JavaScript** and an **HTML5 Canvas** — no engines, no frameworks.  
Collect strawberries, dodge spikes and slimes, hit checkpoint flags, and rescue the princess.  
Designed to be lightweight, responsive, and mobile-friendly (tap controls included).

---

## ✨ Features

- 🚫 **Zero dependencies** – single HTML file with inline JS & CSS  
- 🎨 **Pixel-art aesthetic** using procedurally drawn sprites (no assets)  
- 🕹 **Floaty, forgiving platforming** (coyote time, jump buffer, variable gravity)  
- 🏳 **Checkpoints** and ❤️ **extra lives**  
- 📜 **Name overlay & prologue** – choose the Knight & Princess names  
- 📱 **Responsive canvas scaling** with device-pixel-ratio handling  
- 👆 **Touch controls** for mobile (left / right / jump zones)  

---

## 🎮 Controls

### Desktop
- **Move**: `A` / `D` or `←` / `→`  
- **Jump**: `W` / `↑` / `Space`  
- **Click** to advance dialogs / restart  

### Mobile
- **Tap left third** = move left  
- **Tap middle third** = move right  
- **Tap right third** = jump  

---

## 🧠 Game Goal
- 🍓 Collect **10 strawberries** (or as many as you can)  
- ❌ Avoid spikes and slimes  
- 🏳 Touch **flags** to set a checkpoint  
- ❤️ Hearts grant an **extra life**  
- 👑 Reach the princess to win (ending text adapts to your berry count)  

---

## 🛠 Tech Notes
- 🖥 **HTML5 Canvas** (offscreen buffer + scaled blit)  
- 📦 **Simple AABB tile collision** with jam/ground tiles  
- 💥 **Particle bursts** for feedback  
- 🎨 **Procedural sprite generation** via tiny canvas painters  

---

## 🚀 Play Now
👉 [Strawberry Rescue (GitHub Pages)](https://sh3kky.github.io/Strawberry-Rescue/)  

