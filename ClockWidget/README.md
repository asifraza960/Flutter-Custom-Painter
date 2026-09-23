# ⏰ Flutter Custom Painter Clock

A sleek, highly customizable, and high-performance **Analog & Canvas Clock** built entirely using Flutter's `CustomPainter` and `AnimationController`.

This project demonstrates how to draw smooth hour, minute, and second hands, clock dials, markers, and dynamic shadows on a single Canvas without relying on external UI libraries.

---

## 🚀 Features

* **Real-time Canvas Rendering:** Smooth tick/sweep animation driven by Ticker & AnimationController.
* **Custom Clock Face:** Beautifully rendered hour/minute tick marks, numbers, and center pivot.
* **Neumorphic / Modern UI:** Custom shadows, gradient fills, and subtle depth effects drawn directly on the canvas.
* **Responsive Scaling:** Automatically adjusts canvas size using `Size` parameters to fit any screen resolution.
* **Optimized Performance:** Efficient `shouldRepaint` logic ensuring high FPS with minimal CPU/GPU usage.

---

## 🛠️ Components Drawn

| Component | Description |
| :--- | :--- |
| ⭕ **Clock Dial & Rim** | Circular base with gradient paints and layer shadows. |
| 📏 **Hour/Minute Ticks** | Precise radial geometry using `Math.sin` and `Math.cos`. |
| ⌛ **Clock Hands** | Hour, minute, and second needles with custom pin heads. |
| 🎨 **Dynamic Color Schemes** | Light and Dark mode ready canvas palettes. |

---

## 📦 Getting Started

### Prerequisites

* Flutter SDK (Latest Stable Version)
* Dart SDK

### Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/flutter-custom-painter-clock.git](https://github.com/your-username/flutter-custom-painter-clock.git)
