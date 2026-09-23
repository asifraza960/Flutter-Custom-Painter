# 🐱 Doraemon Custom Painter Widget in Flutter

A pixel-perfect, interactive, and beautifully rendered **Doraemon Character Widget** built entirely from scratch using Flutter's `CustomPainter` and `Path` APIs.

This repository showcases advanced custom drawing techniques in Flutter, including multi-layered paths, facial geometry calculations, bezier curves, and custom feature clipping without using any static images or SVGs.

---

## 🚀 Features

* **100% Vector Canvas Art:** Entirely drawn using `Canvas`, `Path`, and `Paint` objects (No external images/assets).
* **Detailed Facial Features:** 
  * Round head layout and white face contour.
  * Expressive double-eyes with pupils and highlight dots.
  * Bright red nose with light reflection highlights.
  * Classic 6-whisker symmetrical drawing using math vectors.
  * Red collar with the iconic yellow bell & keyhole details.
* **Fully Responsive:** Scale-ready implementation using canvas relative bounds (`Size`).
* **Clean Code Architecture:** Modular painting layers for easy modification and animation extensions.

---

## 🛠️ Anatomy & Canvas Layers

| Feature | Painter Implementation Details |
| :--- | :--- |
| 🔵 **Base & Face** | Concentric circles and curved shapes using `drawCircle` and `drawPath`. |
| 👀 **Eyes & Nose** | Layered ovals with distinct stroke and fill paints. |
| 🐱 **Whiskers & Smile** | Multi-point quadratic curves (`quadraticBezierTo`) for smooth facial expressions. |
| 🔔 **Collar & Bell** | `RRect` for the collar band and overlapping arcs for the golden bell. |

---

## 📦 Getting Started

### Prerequisites

* Flutter SDK (Latest Stable Version)
* Dart SDK

### Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/doraemon-custom-painter.git](https://github.com/your-username/doraemon-custom-painter.git)
