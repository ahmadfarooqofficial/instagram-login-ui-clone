# 📸 Instagram Login UI Clone

<div align="center">

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen.svg?style=for-the-badge)](./CONTRIBUTING.md)

A pixel-perfect, hyper-optimized, high-fidelity recreation of the native Instagram Login Interface. Built from scratch using pure **Vanilla HTML5, CSS3, and JavaScript** with zero external libraries or heavy dependencies.

[Explore Codebase](https://github.com/AhmadFarooq/instagram-login-ui-clone) • [Report Bug]

</div>

---

## 🖥️ Live Preview Mockup

Below is a demonstration of the pixel-perfect, responsive login page in action:

<img width="1280" height="858" alt="Desktop-view" src="https://github.com/user-attachments/assets/dfc3a54c-1d3d-4dc8-aab4-e2528d7126b6" />
<p align="center">
  <img width="386" height="707" alt="Mobile-view" src="https://github.com/user-attachments/assets/41130693-2fb1-44d4-8a65-d31ae816a17f" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img width="385" height="703" alt="loading" src="https://github.com/user-attachments/assets/99f433d1-a871-4bbb-8eff-d838de73cfdb" />
</p>



---

## 📖 About The Project

This project is a masterclass in modern, vanilla web engineering. It demonstrates how to achieve stunning, production-ready, and pixel-perfect UI/UX without relying on bloated modern frameworks or CSS preprocessors. Every animation, layout split, asset load, and input transition has been fine-tuned to match the native Instagram web application experience. 

Designed and engineered with absolute attention to detail, it serves as a robust foundation for portfolio demonstration and high-end front-end layout practice.

---

## ⚡ Key Features

- 📱 **Pixel-Perfect Responsive Layout:** Elegant split-screen design on desktop screens ($> 950\text{px}$) showing a dynamic showcase and identity access forms, seamlessly collapsing into a centered native mobile view on smaller viewports.
- 🚀 **High-Performance Asset Preloading:** Leverages `<link rel="preload">` tags to pre-fetch critical heavy assets (background showcase slides, branding elements) to guarantee instant, flicker-free rendering.
- ⏱️ **Native-Match Splash Screen:** A flat, transitionless, hard-cut splash overlay with the Meta branding footprint that perfectly mimics the cold-start behavior of the native Instagram app.
- 🎨 **Inline SVG Icon System:** Rendered entirely via inline SVGs to avoid cross-browser layout shifts, pixelation, or broken asset paths on third-party CDNs.
- 🧪 **CSS Floating Labels:** Smooth, zero-overlap input animations where labels contract and float dynamically on focus or content entry, built entirely with native CSS state bindings.
- 🔄 **Top-Loading Progress Bar:** A global, reusable JavaScript utility triggering a multi-segmented linear gradient progress bar to simulate asynchronous Single Page Application (SPA) API roundtrips.
- 🎯 **Tactile Mobile Feedback:** Spring-press active transforms (`scale(0.97)`) on all major buttons and anchors, combined with custom `-webkit-tap-highlight-color` overrides to eliminate the default browser blue tap box.

---

## 🛠️ Tech Stack & Architecture

This repository is strictly zero-dependency, ensuring maximum speed, security, and portability.

| Technology | Role | Features Utilized |
| :--- | :--- | :--- |
| **HTML5** | Structural Markup | Preloading headers, Semantic containers, Inline SVG markup |
| **CSS3** | Premium Interface Styling | CSS Grid & Flexbox, Custom Keyframe Animations, Floating Labels, Active Scale Springs |
| **JavaScript (ES6)** | Dynamic Interactivity | Splash Screen Timer, Floating States, SPA Loader Simulation, Active Submit Validaion |

---

## 🚀 Quick Start

Because this is a zero-dependency project, setting up the repository locally is instant. No installers, no compilers, no node modules.

### 📥 1. Clone the Repository
```bash
git clone https://github.com/your-username/instagram-login-ui-clone.git
```

### 📂 2. Navigate to Directory
```bash
cd instagram-login-ui-clone
```

### 🌐 3. Launch the Application
- **Option A (Simple):** Simply double-click the `index.html` file to open it directly in any modern web browser.
- **Option B (Recommended):** Use a lightweight HTTP server (like VS Code's **Live Server** extension or Python's `http.server`) to ensure asset preloads function correctly under standard server request headers:
  ```bash
  # Python 3
  python -m http.server 8000
  ```
  Then, open your browser and navigate to `http://localhost:8000`.

---

## 📂 Project Structure

```text
instagram-login-ui-clone/
├── Assets/                 # Local image and icon assets
│   └── img/
│       ├── 1.webp          # Rotational Hero Showcase Image 1
│       ├── 2.webp          # Rotational Hero Showcase Image 2
│       ├── 3.webp          # Rotational Hero Showcase Image 3
│       └── from-meta.png   # Bottom Splash Footprint
├── index.html              # Main webpage with embedded styles & logic
├── README.md               # Repository documentation (This file)
└── CONTRIBUTING.md         # Contribution guidelines
```

---

## 🤝 Contributing

Contributions make the open-source community an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

Please refer to [CONTRIBUTING.md](./CONTRIBUTING.md) for detailed guidelines on coding standards, pull request processes, and development flows.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## ⚠️ Disclaimer

This project is strictly for educational purposes and personal portfolio demonstration. It is a UI/UX clone designed to practice advanced HTML, CSS, and JavaScript techniques. It is not affiliated with, endorsed by, or connected to Meta or Instagram. Do not use this code for phishing, deceptive practices, or any illegal activities.
