# 🧠 Arpit Rangari — AI/ML Engineer Portfolio

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TensorFlow.js](https://img.shields.io/badge/TensorFlow.js-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

**A stunning, fully interactive single-page portfolio for AI/ML engineers — packed with 3D effects, live neural network training, anime scroll characters, and 50+ animations.**

[🚀 Live Demo](#) · [📸 Screenshots](#-screenshots) · [✨ Features](#-features) · [🛠️ Setup](#️-setup)

</div>

---

## 📸 Screenshots

| Dark Mode (Cyberpunk Neon) | Light Mode (Pastel Peach) |
|---|---|
| ![Dark Mode](<img width="1895" height="901" alt="image" src="https://github.com/user-attachments/assets/eb20912d-97b4-4f87-ba92-312135ac0221" />
) | ![Light Mode](https://via.placeholder.com/600x400/fff5ee/e07850?text=Light+Mode+☀️) |

> *Replace the placeholder URLs above with actual screenshots of your deployed site.*

---

## ✨ Features

### 🎨 Visual Effects & Animations

| Effect | Description |
|---|---|
| 🌐 **3D Neural Network** | Three.js animated neural network in the hero section — glowing nodes, pulsing connections, data pulses traveling between layers, floating particles. Camera follows mouse in 3D parallax. |
| 🎌 **Anime Scroll Character** | 4 SVG anime characters in different poses (coding, thinking, celebrating, waving) that morph as you scroll — with blur/scale transitions, sparkle particles, and neon glow disc. |
| 🖱️ **Custom Cursor System** | Neon ring cursor + dot with 8-particle color trail. Expands on hover over interactive elements. |
| ✨ **Particle Sections** | 20+ floating neon particles per section, rising upward in blue/purple/pink/green. |
| 📊 **Scroll Number Counters** | SVG circular progress rings with odometer-style rolling digits + particle burst explosion when stats enter viewport. |
| 🔮 **Animated Border Cards** | Conic gradient border that spins on hover (blue → purple → pink → blue). |
| 💻 **Typing Code Window** | Hero section Python code that types in line-by-line with syntax highlighting. |
| 📡 **Glitch Text Effect** | "Intelligent Machines" title with blue/pink offset glitch animation. |
| 🌊 **Scanline + Grid** | CRT-style scanline sweep and animated perspective grid in hero background. |
| 🖥️ **PC Desk Background** | Fixed CSS-drawn developer desk setup (monitor, keyboard, mouse, coffee with steam, plant, speakers) as ambient watermark. |
| 📜 **Scroll Progress Bar** | Top-fixed neon gradient progress bar with glow shadow. |
| ⬆️ **Fade-Up Reveals** | Staggered scroll-triggered entrance animations on every section. |
| 🔄 **Neon Loading Screen** | "NEURAL.INIT()" gradient text with progress bar and percentage counter. |

### 🧠 Interactive Features

| Feature | Description |
|---|---|
| 🧪 **TensorFlow.js Neural Lab** | Train a neural network on XOR logic directly in the browser. Configure neurons, learning rate, epochs, and activation function. Watch loss curve and decision boundary evolve in real-time. |
| 🤖 **AI Resume Chatbot** | Floating chatbot (bottom-right) that answers questions about skills, experience, projects, education, publications, awards, and contact info — all based on resume data. |
| 🎠 **Project Carousel** | Auto-playing carousel (5s interval) with 6 projects across 2 slides, arrow navigation, dot indicators, and direct GitHub links. |
| 🌙/☀️ **Dark/Light Theme Toggle** | Smooth toggle between Cyberpunk Neon (dark) and Pastel Peach (light) themes. Persists in localStorage. 80+ CSS overrides for complete theme coverage. |
| 📄 **Resume Download** | Green neon download button in hero section. |

### 📐 Section Breakdown

| Section | What's In It |
|---|---|
| **Hero** | 3D neural network background, glitch title, typing code window, CTAs, social links |
| **About Me** | Bio text + 4 scroll-animated stat counters with ring charts (Years, Projects, Papers, Awards) |
| **Skills** | 20-item logo grid using Devicon library (TensorFlow, PyTorch, Docker, K8s, AWS, etc.) with hover glow effects |
| **Projects** | Auto-carousel with 6 project cards, animated canvas visualizations, GitHub links |
| **TF.js Lab** | Full neural network playground — sliders, training, loss chart, decision boundary, XOR predictions |
| **Education** | Horizontal animated timeline — 10th, 12th, B.Tech, M.S. with staggered reveals and neon fill line |
| **Experience** | Vertical scroll-animated timeline — items fade/blur/slide in proportionally as you scroll, fully reversible |
| **Contact** | Contact info cards, social links, form with success feedback |
| **Chatbot** | Floating FAB with expandable chat panel, keyword-matched resume Q&A |

---

## 🛠️ Setup

### Quick Start

```bash
# Clone the repository
git clone https://github.com/yourusername/ai-ml-portfolio.git

# Navigate to the project
cd ai-ml-portfolio

# Open in browser (no build step needed!)
open index.html
# or
python -m http.server 8000
# then visit http://localhost:8000
```

### Requirements

**None!** This is a single `index.html` file with zero build dependencies. All libraries are loaded via CDN:

| Library | Version | Purpose |
|---|---|---|
| [TailwindCSS](https://tailwindcss.com/) | v4 (Browser) | Utility styling |
| [TensorFlow.js](https://www.tensorflow.org/js) | v4.17.0 | Neural network training |
| [Three.js](https://threejs.org/) | r128 | 3D neural network visualization |
| [Font Awesome](https://fontawesome.com/) | v6.5.1 | Icons |
| [Devicon](https://devicon.dev/) | v2.16.0 | Tech stack logos |
| [Google Fonts](https://fonts.google.com/) | — | Orbitron, Rajdhani, JetBrains Mono |

---

## 🎯 Customization

### Personal Info

Edit the HTML directly to replace placeholder data:

```
Name         → Search for "Alex Neural" and "ALEX.NEURAL"
Email        → Search for "alex.neural@email.com"
Location     → Search for "San Francisco"
GitHub URLs  → Search for "github.com/alexneural"
Resume Link  → Find the #resume-dl button onclick handler
```

### Chatbot Knowledge Base

Update the `RESUME` object in the `<script>` section:

```javascript
const RESUME = {
  name: "Your Name",
  title: "Your Title",
  skills: "Your skills...",
  experience: [
    { role: "...", company: "...", period: "...", desc: "..." }
  ],
  education: { degree: "...", school: "...", gpa: "..." },
  projects: ["Project 1", "Project 2"],
  // ... etc
};
```

### Theme Colors

Modify CSS variables in `:root` (dark) and `body.light` (light):

```css
/* Dark Mode — Cyberpunk Neon */
:root {
  --neon-blue: #00f0ff;
  --neon-purple: #bf5af2;
  --neon-pink: #ff2d55;
  --neon-green: #30d158;
  --dark: #030014;
  --surface: #0a0a1a;
}

/* Light Mode — Pastel Peach */
body.light {
  --neon-blue: #e07850;
  --neon-purple: #c06090;
  --dark: #fff5ee;
  --surface: #ffeedd;
}
```

### Education Timeline

Edit the `.edu-node` elements to match your education:

```html
<div class="edu-node" data-edu="0">
  <div class="edu-icon"><i class="fas fa-school"></i></div>
  <div style="position:relative;"><div class="edu-dot"><div class="edu-dot-ring"></div></div></div>
  <div class="edu-label">
    <div class="edu-degree">Your Degree</div>
    <div class="edu-school">Your School</div>
    <div class="edu-year">2020 — 2024</div>
  </div>
</div>
```

### Adding Projects

Add new cards inside `.carousel-slide` divs:

```html
<div class="glow-card">
  <div class="proj-img"><!-- canvas or icon --></div>
  <div class="proj-body">
    <h3 class="proj-title">Project Name</h3>
    <p class="proj-desc">Description</p>
    <div class="proj-links">
      <a href="https://github.com/you/repo" target="_blank">
        <i class="fab fa-github"></i> GitHub
      </a>
    </div>
  </div>
</div>
```

---

## 📁 Project Structure

```
ai-ml-portfolio/
├── index.html          # Single-file application (HTML + CSS + JS)
├── README.md           # This file
└── assets/             # (optional) screenshots, resume PDF
    ├── screenshot-dark.png
    ├── screenshot-light.png
    └── resume.pdf
```

---

## 🏗️ Tech Architecture

```
┌─────────────────────────────────────────────────────────┐
│                      index.html                         │
├─────────────────────────────────────────────────────────┤
│  <style>                                                │
│  ├── CSS Variables (Dark + Light theme)                  │
│  ├── 80+ Light mode overrides                           │
│  ├── Animations (@keyframes)                            │
│  ├── Component styles (cards, timeline, carousel, etc.) │
│  └── Responsive breakpoints                             │
├─────────────────────────────────────────────────────────┤
│  <body>                                                 │
│  ├── PC Desk Background (CSS-drawn, fixed)              │
│  ├── Custom Cursor + Trail                              │
│  ├── Loader Screen                                      │
│  ├── Navigation + Theme Toggle                          │
│  ├── Hero (Three.js container + code window)            │
│  ├── About (text + ring stat counters)                  │
│  ├── Skills (Devicon logo grid)                         │
│  ├── Projects (auto-carousel + canvas viz)              │
│  ├── TF.js Lab (playground)                             │
│  ├── Education (horizontal timeline)                    │
│  ├── Experience (vertical scroll timeline)              │
│  ├── Contact (form + info)                              │
│  ├── Anime Character (4 SVG frames)                     │
│  ├── Chatbot FAB + Panel                                │
│  └── Footer                                             │
├─────────────────────────────────────────────────────────┤
│  <script>                                               │
│  ├── Theme Toggle (localStorage)                        │
│  ├── Loader animation                                   │
│  ├── Custom cursor + trail physics                      │
│  ├── Scroll effects (progress, nav, parallax)           │
│  ├── IntersectionObserver (reveals, stats, skills, edu) │
│  ├── Three.js scene (nodes, connections, particles)     │
│  ├── Canvas project visualizations                      │
│  ├── TensorFlow.js (model, training, charts)            │
│  ├── Carousel auto-play + controls                      │
│  ├── Scroll timeline (rAF-based)                        │
│  ├── Anime character frame switching                    │
│  └── Chatbot (keyword matching + resume data)           │
│                                                         │
│  Libraries (CDN):                                       │
│  ├── Three.js r128                                      │
│  ├── TensorFlow.js 4.17.0                               │
│  ├── Tailwind CSS v4                                    │
│  ├── Font Awesome 6.5.1                                 │
│  └── Devicon 2.16.0                                     │
└─────────────────────────────────────────────────────────┘
```

---

## ⚡ Performance Notes

- **Single file** — No network waterfall, instant load after CDNs
- **Three.js** — Capped at `devicePixelRatio: 2`, uses `AdditiveBlending` for particles
- **TensorFlow.js** — WebGL backend, model disposed on reset to prevent memory leaks
- **Animations** — Heavy effects use `requestAnimationFrame`, CSS animations use `will-change`
- **IntersectionObserver** — Elements only animate when visible (not continuously)
- **Custom cursor** hidden on mobile to save performance

---


## 🙏 Credits

- [Three.js](https://threejs.org/) — 3D WebGL rendering
- [TensorFlow.js](https://www.tensorflow.org/js) — Browser-based ML
- [Font Awesome](https://fontawesome.com/) — Icons
- [Devicon](https://devicon.dev/) — Programming language logos
- [Pexels](https://www.pexels.com/) — Stock photography reference
- [Google Fonts](https://fonts.google.com/) — Orbitron, Rajdhani, JetBrains Mono

---

<div align="center">

**Built with ❤️ and 🧠 by Arpit Rangari**

*If you found this useful, give it a ⭐!*

</div>
