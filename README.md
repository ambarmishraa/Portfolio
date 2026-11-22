# Ambar Mishra — Portfolio

A minimalist, monochrome personal portfolio showcasing my background as an M.Sc. Computer Science student and developer. Built with pure HTML, CSS, and JavaScript — no frameworks, no dependencies.

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

---

## ✨ Features

- **Split Hero Design** — Bold 50/50 black-and-white landing with a scrolling marquee and `mix-blend-mode` typography
- **Monochrome Theme** — Stark black, white, and gray palette across all sections
- **YouTube Integration** — Vlog channel section with a click-to-load player (nothing is loaded from YouTube until the visitor clicks)
- **Privacy-friendly** — Self-hosted fonts, no trackers, no third-party requests on page load
- **Accessible** — Semantic headings, keyboard-friendly menu, respects `prefers-reduced-motion`
- **Scroll Reveal Animations** — Elements fade in as you scroll using `IntersectionObserver`
- **Responsive** — Fully responsive layout with a mobile hamburger menu
- **No Dependencies** — Zero external libraries; pure vanilla HTML/CSS/JS
- **Lightweight** — Images served as optimised WebP (whole `assets/` folder ≈ 1.2 MB)

---

## 📂 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # Complete stylesheet (monochrome + YouTube red)
├── script.js           # Header, scroll reveal, mobile menu, YouTube click-to-load
├── README.md
├── LICENSE
├── 404.html          # Custom "page not found" (served automatically by Vercel)
├── robots.txt
├── sitemap.xml
└── assets/
    ├── fonts/          # Self-hosted Inter & Space Grotesk (OFL)
    ├── img/            # Profile photo, project images, favicon, og-image (WebP/JPG)
    └── skills/
        ├── Data/
        ├── Frontend/
        ├── Backend/
        ├── Mobile/
        ├── Database/
        ├── Devops/
        └── collaboration/
```

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/ambarmishraa/portfolio.git
   cd portfolio
   ```

2. **Run it locally**
   ```bash
   python -m http.server 8000
   ```
   Then open [http://localhost:8000](http://localhost:8000).

   No build step, no `npm install`. Use a local server rather than double-clicking `index.html`:
   browsers block the self-hosted fonts on `file://` pages. (`npx serve` works too.)

---

## 🎨 Design

| Element | Value |
|---|---|
| Background | `#000000` (pure black) |
| Text | `#ffffff` / `#a1a1aa` / `#52525b` |
| YouTube Accent | `#ff0000` / `#ff4444` |
| Fonts | [Inter](https://fonts.google.com/specimen/Inter), [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) (self-hosted) |
| Cards | Glassmorphism with subtle white borders |
| Hero | Split black/white with outline-stroke marquee text |

---

## 📋 Sections

| # | Section | Description |
|---|---|---|
| 1 | **Hero** | Split-screen design with scrolling "DATA & SOFTWARE" marquee |
| 2 | **Experience** | Timeline layout with professional roles |
| 3 | **Projects** | Project cards with GitHub / demo links |
| 4 | **Skills** | Grouped badges — Programming & Data, Frontend, Backend, Mobile, DevOps, etc. |
| 5 | **Education** | Cards for TU Darmstadt (M.Sc.) and AKTU (B.Tech) |
| 6 | **YouTube** | Channel card, click-to-load video, topic chips, subscribe CTA |
| 7 | **Photography** | Link to my photography portfolio site built with Next.js |
| 8 | **Contact** | Phone, email, location + social links + download CV |

---

## 🔗 Links

- **Live Site**: [ambarmishra.vercel.app](https://ambarmishra.vercel.app/)
- **Photography**: [ambarphotography.vercel.app](https://ambarphotography.vercel.app/)
- **YouTube**: [@ambarmishravlogs](https://www.youtube.com/@ambarmishravlogs)
- **GitHub**: [ambarmishraa](https://github.com/ambarmishraa)
- **LinkedIn**: [ambar-mishra](https://www.linkedin.com/in/ambar-mishra)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

> Built with ☕ and passion by **Ambar Mishra**
