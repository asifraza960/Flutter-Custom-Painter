# 😊 Flutter Animated Smile Custom Painter Widget

A smooth, customizable, and high-performance **Smile / Expression Widget** built completely from scratch using Flutter's `CustomPainter` and `Canvas` API.

This repository demonstrates how to draw expressive facial paths, interactive curved lips using quadratic bezier curves, dynamic eyes, and color transitions without relying on external image assets or SVGs.

---

## 🚀 Features

* **100% Vector Canvas Rendering:** Pure `Paint` and `Path` drawing for crisp, resolution-independent visuals.
* **Interactive Curved Mouth:** Dynamic smiley mouth created using `quadraticBezierTo` for smooth curve adjustments.
* **Expressive Eye Shapes:** Supports simple circles, blinking arcs, or playful wink animations.
* **Dynamic Color Transitions:** Smooth color shifts matching mood or satisfaction levels.
* **Lightweight & High FPS:** Fully optimized rendering with minimum rebuild overhead.

---

## 🛠️ Anatomy & Canvas Geometry

| Component | Drawing Mechanism |
| :--- | :--- |
| 🟡 **Face Base** | Layered circle with gradient or solid `Paint`. |
| 👀 **Eyes** | Symmetric oval pairs or curved arcs using `drawArc`. |
| 😊 **Smile Path** | Quadratic Bezier Curve (`quadraticBezierTo`) anchored to dynamic control points. |
| 🎨 **Cheeks** | Soft radial gradient overlays for blushing effects. |

---

## 📦 Getting Started

### Prerequisites

* Flutter SDK (Latest Stable Version)
* Dart SDK

### Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/flutter-smile-widget.git](https://github.com/your-username/flutter-smile-widget.git)

<img width="1920" height="1440" alt="715shots_so" src="https://github.com/user-attachments/assets/e6318cb7-67d3-4f70-92c5-f126da887891" />
