<h1 align="center">🌈 Virtual RGB Keyboard Simulator</h1>

<p align="center">
  <strong>Experience premium laptop RGB lighting directly in your browser.</strong>
</p>

## 💡 About The Project

I built this project for fun, but it serves a highly practical purpose: **experiencing and customizing an RGB keyboard without needing to own one.** Not everyone has access to a premium gaming laptop, and this simulator bridges that gap. It is built specifically for:
* **Enthusiasts & Gamers:** Anyone who just wants to play around with RGB layouts and create cool lighting profiles.
* **First-Time Buyers:** If you are planning to purchase an RGB-enabled laptop (like a Lenovo Legion, Razer Blade, or ASUS ROG) but have never used one, this tool lets you test the different lighting zones and get used to how the effects work *before* you buy.

No downloads, no expensive hardware, no bloated software—just pure, customizable RGB right in your browser.

## ✨ Features

* **🖌️ Per-Key RGB Painting:** Click and drag your mouse across the keys to "paint" them with custom colors, just like a high-end digital brush.
* **🚥 Multiple Zone Modes:**
  * **1-Zone (Global):** Change the entire keyboard color at once for a clean, unified look.
  * **4-Zone (Sections):** Simulate classic gaming laptop layouts by controlling 4 distinct vertical sections.
  * **24-Zone (Spectrum):** Use a slider to shift a rainbow spectrum across 24 vertical slices.
* **🎬 Dynamic Effects Overlay:**
  * **Breathing:** A smooth, continuous pulsing animation.
  * **RGB Wave:** A color-shifting wave across the entire board.
  * **Reactive:** Keys remain dark until pressed, then flash brightly and smoothly fade out.
  * **Repulse (Ripple):** Clicking a key sends a calculated wave of light rippling outward across the rest of the keyboard.
* **⌨️ Physical Keyboard Sync:** Typing on your actual physical keyboard triggers the virtual keys and interactive effects in real-time.

## 🚀 Live Demo

[👉 Click here to try the Live Interactive Demo!](https://rishank012.github.io/RGB-Keyboard-Simulator/) 

## 🛠️ Built With

This project is built entirely from scratch to be lightweight and fast, without relying on any external libraries.

* **HTML5:** Structured matrix layout mimicking a full-size laptop keyboard (including a Numpad and function row).
* **CSS3:** Flexbox for precise alignment, CSS Variables (`--var`) for state management, 3D shadowing for depth, and `@keyframes` for smooth animations.
* **JavaScript (Vanilla):** `Map()` object for efficient state management of individual key colors.
  * Mathematical distance calculations (Pythagorean theorem) to generate the ripple effect delays.
  * Event listener mapping to sync physical keystrokes with virtual DOM elements.

## 💻 How to Run Locally

If you want to download and modify the code yourself, it's incredibly simple:

1. Clone this repository to your local machine:
   ```bash
   git clone [https://github.com/rishank012/RGB-Keyboard-Simulator.git](https://github.com/rishank012/RGB-Keyboard-Simulator.git)
   ```
2. Open the downloaded folder.
3. Double-click the `index.html` file to open it in your web browser. That's it! No local server or installations required.

## 🤝 Contributing

Got an idea for a cool new lighting effect (like "Raindrop" or "Starlight") or a different laptop layout (like a 60% keyboard)? Feel free to fork this project, submit pull requests, or open an issue!
