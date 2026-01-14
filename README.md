# ⚔️ Data Heist

> **A high-octane, abstract cyberpunk tactical shooter running entirely in a single HTML file.**

**Data Heist** is a fast-paced action roguelite inspired by *Hotline Miami* and *Superhot*. You play as a rogue AI infiltrating a secure mainframe. The rules are simple: One shot kills you, one shot kills them. Move fast, think faster.

---

## 🎮 How to Play

### **Controls**

| Key | Action |
| :--- | :--- |
| **W, A, S, D** | Move Player |
| **Mouse Cursor** | Aim |
| **Left Click** | Fire Weapon / Swing Blade |
| **Right Click** | **THROW WEAPON** (Insta-kill projectile) |
| **Spacebar** | **DASH** (Invincible for 0.2s) |
| **Left Shift** | **FOCUS** (Slow Motion Matrix Style) |

---

## 🔫 Weapons & Combat Systems

You can only hold **one weapon** at a time. Adaptability is key.

### **The Scavenge System**
* **Ammo Stacking:** If you pick up a gun you already have, you gain its ammo.
* **Swapping:** If you pick up a different gun, you drop your current one.
* **Throwing:** Right-click throws your gun. If it hits an enemy, they die instantly. You revert to your **Data-Blade** (Melee) until you find a new gun.

### **The Arsenal**
1.  **Data-Blade (Melee):** Your fallback weapon. Wide arc, infinite ammo. Can slash through enemy bullets to destroy them.
2.  **Pistol:** Reliable, yellow plasma rounds. Moderate fire rate.
3.  **Shotgun:** Fires a spread of 5 cyan pellets. Devastating at close range, useless at long range.
4.  **SMG:** High rate of fire with purple tracers. Low accuracy, but great for suppression.
5.  **Grenade Launcher:** Fires a slow green orb. Explodes on impact, killing anything in a radius.

---

## 🤖 Enemy Database

Know your enemy to survive the breach.

* **🟢 The Rusher (Green Triangle):** High speed. No gun. Tries to tackle you. *Counter: Shoot early or melee.*
* **🔵 The Shield (Blue Arc):** Blocks all damage from the front. Carries a pistol. *Counter: Dash behind them or use Grenades.*
* **🟣 The Sniper (Purple + White Outline):** Tracks you with a laser sight for 1.5s, then fires a wall-piercing railgun. *Counter: Break line of sight or Dash through the shot.*
* **🟧 The Shotgunner (Orange Square):** Aggressive. Fires a 3-bullet spread. *Counter: Keep your distance. Do not dash directly at him.*
* **🔴 The Minigunner (Red Pentagon):** Heavy tank. Fires a continuous stream for 3 seconds, then reloads. *Counter: Wait for the reload, then strike.*

---

## 🛠️ Installation & Running

No installation required! This game is built using the HTML5 Canvas API and Web Audio API.

1.  Download the `index.html` file (or whatever you named your game file).
2.  Double-click to open it in any modern web browser (Chrome, Firefox, Edge).
3.  **Click the screen once** to initialize the Audio Engine (Browsers block sound until interaction).
4.  Hack the system.

---

## ⚙️ Technical Details

* **Engine:** Custom Vanilla JavaScript (No libraries).
* **Rendering:** HTML5 `<canvas>`.
* **Audio:** Procedural synthesis using `AudioContext` (No external .mp3/.wav files needed).
* **Physics:** Predictive collision detection with wall-sliding logic.
