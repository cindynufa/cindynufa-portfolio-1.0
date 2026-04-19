<div align="center">

# ✦ Cindy Nufa — Portfolio

**A refined personal portfolio landing page, handcrafted with pure HTML & Vanilla CSS.**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![No Framework](https://img.shields.io/badge/No_Framework-Zero_Dependencies-d98ca0?style=flat-square)](/)
[![Status](https://img.shields.io/badge/Status-Live-a8c4b0?style=flat-square)]()

<br />

> *"Simplicity is the essence of beauty — where soft visuals meet purposeful functionality."*

</div>

---

## 📸 Preview

> A soft, elegant portfolio built to showcase frontend craftsmanship — clean layout, warm rose tones, and thoughtful typography.

---

## ✨ Features

- **Responsive Navigation** — Fixed header with smooth scroll links and a hamburger menu for mobile
- **Hero Section** — Profile photo with a soft blob frame, tagline, and dual CTA buttons
- **About Section** — Personal bio with animated stat cards (experience, projects, clients)
- **Skills Section** — Asymmetric CSS grid layout showcasing 5 skill categories with tags
- **Contact Section** — Info display + fully styled contact form
- **Footer** — Minimal, elegant bottom section with site-wide navigation

---

## 🎨 Design System

This project uses a **custom design system** defined entirely in CSS custom properties.

### Color Palette

| Token | Value | Usage |
|-------|-------|-------|
| `--colour-primary` | `#d98ca0` | Rose pink — brand color |
| `--colour-primary-light` | `#ebb8c5` | Hover states |
| `--colour-primary-soft` | `#fdf0f3` | Card backgrounds |
| `--colour-bg` | `#fdfaf8` | Page background |
| `--colour-text-primary` | `#3d2b35` | Headings |
| `--colour-text-secondary` | `#7a5f6a` | Body text |
| `--colour-accent-sage` | `#a8c4b0` | Availability badge |

### Typography

| Role | Font |
|------|------|
| Display / Headings | `Playfair Display` — elegant serif |
| Body | `DM Sans` — clean, modern sans-serif |
| Italic / Accents | `Cormorant Garamond` — refined italic |

### Spacing Scale

```
xs → 0.5rem  |  sm → 1rem  |  md → 2rem  |  lg → 4rem  |  xl → 6.5rem
```

---

## 📁 Project Structure

```
portfolio/
├── index.html              # Main HTML file
├── css/
│   └── style.css           # All styles (design system + components)
└── assets/
    ├── icons/
    │   ├── hamburger.svg
    │   └── arrow-down.svg
    └── images/
        └── cindy.webp      # Profile photo
```

---

## 🚀 Getting Started

No build tools. No dependencies. Just open and go.

```bash
# Clone the repository
git clone https://github.com/your-username/cindy-nufa-portfolio.git

# Navigate into the project
cd cindy-nufa-portfolio

# Open in browser
open index.html
```

Or simply drag `index.html` into your browser. ✦

---

## 🛠️ Built With

| Technology | Purpose |
|------------|---------|
| **HTML5** | Semantic structure & accessibility |
| **CSS3** | All styling — layout, animations, design system |
| **CSS Custom Properties** | Design tokens (colors, spacing, typography) |
| **CSS Grid & Flexbox** | Responsive layout |
| **Google Fonts** | DM Sans, Outfit, Quicksand |
| **`clamp()`** | Fluid, responsive typography |

> **Zero JavaScript. Zero frameworks. Zero build steps.**

---

## 📐 CSS Highlights

### Fluid Typography
```css
font-size: clamp(1.8rem, 0.5rem + 3.1vw, 3rem);
```

### Asymmetric Skills Grid
```css
.skills-description {
  display: grid;
  grid-template-columns: repeat(6, 1fr);
}
/* Cards 1–3 span 2 cols, cards 4–5 span 3 cols */
```

### Organic Photo Frame
```css
border-radius: 50% 50% 48% 48% / 55% 55% 38% 38%;
```

### Gradient Backgrounds
```css
background: linear-gradient(
  160deg,
  var(--colour-bg) 55%,
  var(--colour-primary-soft) 90%
);
```

---

## 🗺️ Sections

| # | Section | Description |
|---|---------|-------------|
| 1 | **Hero** | Name, profession, description, CTA buttons, profile photo |
| 2 | **About** | Bio paragraphs + stat cards (1+ yr exp, 20+ projects, 5+ clients) |
| 3 | **Skills** | Frontend, Frameworks, UI, Animation, Tools & Workflow |
| 4 | **Contact** | Email, location, availability status + contact form |

---

## 📬 Contact

Made with ♡ by **Cindy Nufa**

- 📧 xindicode@gmail.com
- 🌏 Indonesia
- 💼 *Open to work*

---

<div align="center">

*Crafting elegant digital experiences — one pixel at a time.*

</div>
