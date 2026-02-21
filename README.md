# ✨ Cosmic Calculator

A beautifully animated calculator built with **React**, **TypeScript**, **Material UI**, and **Tailwind CSS** — featuring particle effects, a live star field, multiple themes, and both standard and scientific modes.

![React](https://img.shields.io/badge/React-18-61DAFB?style=flat-square&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-4.9-3178C6?style=flat-square&logo=typescript)
![MUI](https://img.shields.io/badge/MUI-v5-007FFF?style=flat-square&logo=mui)
![TailwindCSS](https://img.shields.io/badge/Tailwind-v3-06B6D4?style=flat-square&logo=tailwindcss)

---

## 🚀 Features

- 🌌 **Animated star field** background with twinkling stars
- 💥 **Particle burst** effect on every button press
- ✨ **Shimmer glow** on the display when a result is computed
- 🎨 **4 color themes** — Cosmic, Ocean, Forest, Ember
- ⚗️ **Scientific mode** — sin, cos, tan, √, x², log, π, e, n! and more
- 📜 **Calculation history** dropdown panel
- ⌨️ **Full keyboard support**
- 🌊 Ripple effects, glow animations, and smooth transitions throughout

---

## 🛠️ Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) v16 or higher
- npm (comes with Node.js)

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/usamajehangir/cosmic-calculator.git

# 2. Navigate into the project folder
cd cosmic-calculator

# 3. Install dependencies
npm install

# 4. Start the development server
npm start
```

The app will open automatically at [http://localhost:3000](http://localhost:3000)

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `0–9` | Input digits |
| `+ - * /` | Operators |
| `Enter` or `=` | Calculate |
| `Escape` or `C` | Clear |
| `Backspace` | Delete last digit |
| `.` | Decimal point |

---

## ⚗️ Scientific Functions

| Button | Description |
|--------|-------------|
| sin / cos / tan | Trigonometry (in degrees) |
| √ | Square root |
| x² / x³ | Powers |
| log / ln | Logarithms |
| π / e | Mathematical constants |
| 1/x | Reciprocal |
| n! | Factorial |

---

## 📁 Project Structure

```
src/
├── components/
│   ├── Calculator.tsx       # Main logic and layout
│   ├── CalcButton.tsx       # Animated button with ripple
│   ├── Display.tsx          # Glowing display + history
│   ├── ParticleEffect.tsx   # Particle burst on click
│   └── StarField.tsx        # Background star animation
├── App.tsx
├── index.tsx
└── index.css                # Custom keyframe animations
```

---

## 🧰 Tech Stack

- **React 18** + **TypeScript**
- **Material UI (MUI) v5** — Buttons, Tooltips, Chips
- **Tailwind CSS v3** — Layout and utility styling
- **Custom CSS animations** — Keyframes for particles, shimmer, glow, shake

---

## 📄 License

MIT — feel free to use, modify, and share!
