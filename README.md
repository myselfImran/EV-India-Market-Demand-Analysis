# ⚡ EV India — Drive the Future

> India's premier electric vehicle landing page — a modern, fully responsive, single-page website built for GitHub Pages deployment.

![EV India Banner](https://img.shields.io/badge/EV%20India-Drive%20the%20Future-00ff88?style=for-the-badge&logo=lightning&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Ready-00ff88?style=for-the-badge&logo=github&logoColor=white)

---

## 🚗 Live Demo

👉 **[View Live on GitHub Pages](https://yourusername.github.io/ev-india)**

---

## 📸 Preview

The website features a dark, electric-green themed UI with:
- Animated hero section with grid background
- Vehicle showcase cards (scooters, bikes, cars, SUVs, buses)
- Interactive charging network map
- Customer testimonials
- Contact form
- Fully responsive design

---

## ✨ Features

- ✅ **100% Vanilla** — No frameworks, no dependencies, pure HTML/CSS/JS
- ✅ **Fully Responsive** — Works on mobile, tablet, and desktop
- ✅ **Scroll Animations** — Smooth reveal animations on scroll using Intersection Observer API
- ✅ **Fixed Navigation** — Sticky navbar with active section highlighting
- ✅ **Vehicle Cards** — 6 EV categories with specs (range, speed, price)
- ✅ **Charging Network Map** — Visual India map with animated city dots
- ✅ **Contact Form** — Functional UI with form validation feedback
- ✅ **GitHub Pages Ready** — Deploy in one click with zero build step

---

## 📁 Project Structure

```
ev-india/
│
├── index.html          # Main website file (all-in-one)
└── README.md           # Project documentation
```

> Everything is contained in a single `index.html` file — fonts are loaded from Google Fonts CDN.

---

## 🚀 Getting Started

### Option 1: View Locally

```bash
# Clone the repository
git clone https://github.com/yourusername/ev-india.git

# Navigate to the project
cd ev-india

# Open in browser
open index.html
# or double-click index.html in your file explorer
```

### Option 2: Deploy to GitHub Pages

1. **Fork or clone** this repository
2. Go to your repo on GitHub → **Settings** → **Pages**
3. Under **Source**, select `main` branch and `/ (root)` folder
4. Click **Save**
5. Your site will be live at `https://yourusername.github.io/ev-india` in ~60 seconds

---

## 🎨 Design System

| Element | Value |
|--------|-------|
| Primary Color | `#00ff88` (Electric Green) |
| Background | `#050f0a` (Deep Black-Green) |
| Card Background | `#0d1f14` |
| Text | `#e8f5e9` |
| Muted Text | `#7aad8a` |
| Display Font | Orbitron (Google Fonts) |
| Body Font | Syne (Google Fonts) |

---

## 📱 Sections

| # | Section | Description |
|---|---------|-------------|
| 1 | **Hero** | Fullscreen landing with animated grid + stats bar |
| 2 | **About** | Mission, vision, and key company differentiators |
| 3 | **Vehicles** | 6 vehicle cards with specs across categories |
| 4 | **Features** | 8 technology/service highlights |
| 5 | **Charging** | India map with charging station cities |
| 6 | **Testimonials** | 3 customer reviews |
| 7 | **CTA** | Call-to-action with test drive booking |
| 8 | **Contact** | Full contact form + company info |
| 9 | **Footer** | Links, social media, legal |

---

## 🛠️ Customization Guide

### Change Company Name
Search and replace `EV India` / `EVIndia` in `index.html`.

### Change Colors
Edit the CSS variables at the top of the `<style>` tag:
```css
:root {
  --green: #00ff88;   /* Primary accent color */
  --dark:  #050f0a;   /* Background color */
  --text:  #e8f5e9;   /* Text color */
}
```

### Add/Edit Vehicles
Find the `vehicles-grid` div and copy-paste a `.vehicle-card` block:
```html
<div class="vehicle-card">
  <div class="vehicle-img">🚗</div>
  <div class="vehicle-body">
    <span class="vehicle-tag">Category</span>
    <div class="vehicle-name">Model Name</div>
    <p class="vehicle-desc">Description here.</p>
    <div class="vehicle-specs">
      <div class="spec"><div class="spec-val">000km</div><div class="spec-key">Range</div></div>
      ...
    </div>
  </div>
</div>
```

### Update Contact Details
Search for `1800-EV-INDIA`, `hello@evindia.co.in`, and the address — replace with your real details.

---

## 📦 Dependencies

| Library | Purpose | CDN |
|---------|---------|-----|
| Google Fonts (Orbitron) | Display/heading font | fonts.googleapis.com |
| Google Fonts (Syne) | Body font | fonts.googleapis.com |

No npm, no build tools, no framework required.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

Feel free to use, modify, and distribute for personal or commercial projects.

---

## 🙌 Contributing

Pull requests are welcome! For major changes, please open an issue first.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/NewSection`)
3. Commit your changes (`git commit -m 'Add new section'`)
4. Push to the branch (`git push origin feature/NewSection`)
5. Open a Pull Request

---

## 👨‍💻 Author

Built with ❤️ for a greener India 🇮🇳⚡

---

*© 2025 EV India. Proudly Made in India.*
