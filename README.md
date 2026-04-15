# 🧮 Ultimate Scientific Calculator (AptCalc)

Hey there! Welcome to the **Ultimate Scientific Calculator, AptCalc**, a powerful, browser-based engineering calculator made with ❤️ by me, ie: **Apratim Das**. 

I built this project to bridge the gap between simple web calculators and the physical, heavy-duty calculators engineering students use every day. Inspired by the sleek interface of the **Casio ClassWiz fx-991CW**, this calculator is a pure numerical beast capable of handling complex phasors, matrices, base-N conversions, and advanced trigonometry right in your browser.

![Calculator Preview](https://via.placeholder.com/800x400.png?text=Add+a+Screenshot+Here!)

## ✨ Features

This isn't just a basic `+` and `-` calculator. It comes packed with advanced math engines:

* **⚡ Smart Parsing Engine:** Type the way you think. It automatically translates human inputs like `3x√(27)` into machine code `nthRoot(27, 3)` behind the scenes.
* **📐 Advanced Trigonometry:** Fully supports standard and inverse trig functions, with a clickable `[D]` / `[R]` toggle to switch between Degrees and Radians instantly.
* **⚡ Complex Numbers & Phasors:** Native support for $i$. Easily work in rectangular or polar coordinates (using the `∠` shift key) for AC circuit analysis. 
* **💾 Variable Storage (STO):** Store your answers into variables (like `x`) and use them in later equations, just like real hardware.
* **🖥️ Interactive Dual-Line UI:** A custom-built screen where you can tap anywhere on your math expression to move the blinking cursor and make edits without deleting the whole line.
* **🔢 Multi-Mode System:**
  * **Calculate:** General math and matrix/vector operations.
  * **Complex:** Dedicated mode for $i$ and phasors.
  * **Base-N:** Instantly converts answers across DEC, HEX, BIN, and OCT.
  * **Table:** Generates an $f(x)$ table over a custom range.
* **📱 Fully Responsive:** Carefully optimized CSS ensures it looks and feels like a native app on Windows, Android, and iOS tablets.

## 🛠️ Tech Stack

This project is lightweight, fast, and requires zero backend server.

* **HTML5:** For the structural layout of the calculator body and screen.
* **CSS3:** Heavy use of CSS Grid and Flexbox to perfectly replicate the circular and pill-shaped keycaps of modern Casio calculators. Includes custom animations (like the blinking cursor) and touch-optimizations for mobile (`touch-action: manipulation`).
* **Vanilla JavaScript:** Powers the state-machine, the menu system, the UI renderer, and the smart parser.
* **[Math.js (v11.8.0)](https://mathjs.org/):** The core mathematical brain of the operation. I implemented custom overrides to force standard Degree calculations and precision-snapping to mimic hardware limits.

## 🚀 How to Use / Installation

Because this is a purely frontend application, you don't need Node.js, Python, or any complicated build tools.

**Option 1: Use it Live (Recommended)**
Access the calculator directly from any browser here: 
👉 **[https://uncomparablex.github.io/AptCalc/](https://uncomparablex.github.io/AptCalc/)**

**Option 2: Run it Locally**
1. Clone this repository: `git clone https://github.com/apratimdas/scientific-calculator.git`
2. Open the folder.
3. Double-click `index.html` to open it in Chrome, Safari, Firefox, or Edge. 

## 🧠 Note on Limitations (Numerical vs. Symbolic)
This calculator is an advanced **Numerical Engine**. It will flawlessly calculate the determinant of a 3x3 matrix, the cross product of vectors, or complex division. However, it is not a Computer Algebra System (CAS). It cannot evaluate purely symbolic calculus (like rendering algebraic Laplace transforms or Fourier series equations). 

## 🤝 Contributing
Found a bug with a specific mathematical edge case? Have an idea for a new feature? Feel free to open an issue or submit a pull request. Let's make this the best free calculator on the web!

---
*Designed & Engineered by [Apratim Das](https://github.com/uncomparablex)*
