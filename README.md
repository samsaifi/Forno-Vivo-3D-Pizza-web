# 🍕 Forno Vivo — Immersive 3D Pizzeria Experience

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Three.js](https://img.shields.io/badge/Three.js-r160-black.svg?logo=three.js)](https://threejs.org/)
[![JavaScript](https://img.shields.io/badge/ES6+-Vanilla%20JS-F7DF1E.svg?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![HTML5](https://img.shields.io/badge/HTML5-WebGL-E34F26.svg?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API)

> **"Step inside an authentic 3D Italian pizzeria. Choose your table, customize your pizza with real-time toppings, watch it bake in a glowing wood-fired oven, and dine — directly in your browser."**

---

## 🌟 Highlights & Features

- **🏛️ Handcrafted 3D Environment**: Fully procedural textures (terracotta brick, aged wood, awnings, neon/gold signage) with realistic shadow maps and warm ambient interior lighting.
- **🚶 Animated Waiter & Cinematic Camera**: Seamless camera transitions guiding you from street entrance to your chosen table, guided by an animated waiter NPC.
- **🍕 Real-Time 3D Pizza Builder**:
  - Interactive crust options (thin, classic, thick, stuffed).
  - Procedural sauce, mozzarella cheese, and dynamic 3D scatter toppings (pepperoni, mushrooms, olives, peppers, onions, fresh basil, and jalapeños).
- **🔥 Wood-Fired Oven Stage**: Watch your pizza enter the roaring brick oven with smoke particles, dynamic fire glow, and baking countdown.
- **🛎️ Table Dining & Interactive Courses**: Order additional courses (pastas, salads, drinks, artisanal tiramisù) delivered straight to your table.
- **🧾 Bill & Checkout Simulation**: Complete breakdown with tax, customizable tip selector, and instant order receipt.
- **⚡ Zero Build Dependencies**: Standalone HTML5 and ES modules with Three.js loaded via native browser `importmap`. Runs instantly without Node build pipelines.

---

## 🚀 Quick Start

Because Forno Vivo is completely buildless, you can run it with any static web server:

### Option 1: Python
```bash
# Python 3
python -m http.server 8000
```
Then visit `http://localhost:8000`.

### Option 2: Node / npx
```bash
npx serve .
```

### Option 3: PHP / Apache / XAMPP
Place this directory inside your web root (e.g., `htdocs/pizza`) and open `http://localhost/test/pizza/` in your browser.

---

## 🎮 How to Play

1. **Step Inside**: Click **"Step Inside"** from the street view to open the rustic wooden doors.
2. **Select Table**: Choose from Table 1 to Table 6 (window seats, quiet corners, or chef's oven-side tables).
3. **Customize Pizza**: Pick your favorite crust and add your toppings.
4. **Watch it Bake**: Experience the warm glow of the Neapolitan oven.
5. **Enjoy & Pay**: Enjoy your meal with music and settle the check.

---

## 🛠️ Tech Stack

- **Graphics**: [Three.js r160](https://threejs.org/) (WebGL Renderer, ACESFilmicToneMapping, PCFSoftShadowMap)
- **Styling**: Vanilla CSS3 with responsive panels and glassmorphism UI
- **Typography**: Playfair Display & Inter (Google Fonts)
- **Audio & Particles**: HTML5 Web Audio API & procedural canvas sprites

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
