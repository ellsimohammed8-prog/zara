# ZARA — New Collection

<div align="center">

![ZARA](https://img.shields.io/badge/ZARA-Luxury%20Fashion-black?style=for-the-badge&labelColor=000000&color=ffffff)
![Next.js](https://img.shields.io/badge/Next.js-Static%20Export-black?style=for-the-badge&logo=next.js&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-Styling-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

**A modern, luxury fashion e-commerce frontend inspired by ZARA — built with Next.js & Tailwind CSS**

[Live Demo](#) · [Report Bug](https://github.com/ellsimohammed8-prog/zara/issues) · [Request Feature](https://github.com/ellsimohammed8-prog/zara/issues)

</div>

---

## ✨ Overview

This project is a **luxury fashion e-commerce website** inspired by the ZARA brand, showcasing a clean, high-end aesthetic with smooth animations and a responsive layout. Built as a **Next.js static export**, it features full-screen hero sections for each fashion category with glassmorphic UI elements and cinematic transitions.

---

## 🖼️ Features

- 🎬 **Full-screen Hero Sections** — Immersive category showcases for Trousers, Shoes, Dresses, Outerwear, Tops, and Bags
- 🪟 **Glassmorphic UI** — Frosted-glass buttons and overlays for a premium look
- 🌙 **Dark Luxury Theme** — Deep black backgrounds with gradient overlays and refined typography
- 📱 **Fully Responsive** — Mobile-first design with adaptive navigation (hamburger menu on mobile)
- ⚡ **Optimized Performance** — Image preloading with `fetchpriority="high"` for hero images
- 🧭 **Category Navigation** — Dedicated pages for each product category (`/category/[slug]`)
- 🛒 **Product Pages** — Dynamic product detail routing (`/product/[id]`)
- 🎞️ **Scroll Animations** — Smooth reveal animations triggered on scroll
- 🔤 **Luxury Typography** — Wide letter-spacing and uppercase styling for a high-fashion feel

---

## 🗂️ Project Structure

```
zara/
├── index.html              # Main homepage (static export)
├── 404.html                # Custom 404 error page
├── category/
│   └── [slug].html         # Category listing pages
├── product/
│   └── [id].html           # Product detail pages
├── images/
│   └── hero/
│       ├── trousers-hero.png
│       ├── shoes-hero.png
│       ├── dresses-hero.png
│       ├── outerwear-hero.png
│       ├── tops-hero.png
│       └── bags-hero.png
└── _next/
    └── static/
        ├── css/            # Compiled Tailwind CSS
        └── chunks/         # Next.js JavaScript bundles
```

---

## 🛍️ Categories

| Category    | Route                   | Description                     |
|-------------|-------------------------|---------------------------------|
| Trousers    | `/category/trousers`    | Curated trouser collection      |
| Shoes       | `/category/shoes`       | Footwear for every occasion     |
| Dresses     | `/category/dresses`     | Elegant dress collection        |
| Outerwear   | `/category/outerwear`   | Coats, jackets & outerwear      |
| Tops        | `/category/tops`        | Tops and blouses                |
| Bags        | `/category/bags`        | Luxury bags & accessories       |

---

## 🚀 Tech Stack

| Technology     | Purpose                              |
|----------------|--------------------------------------|
| **Next.js**    | React framework with static export   |
| **Tailwind CSS** | Utility-first CSS styling          |
| **React**      | Component-based UI architecture      |
| **HTML5/CSS3** | Semantic markup & custom animations  |

---

## 📦 Getting Started

### Prerequisites

- Node.js `18+`
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/ellsimohammed8-prog/zara.git
cd zara
```

### Run Locally (Static)

Since this is a **Next.js static export**, you can serve it with any static file server:

```bash
# Using npx serve
npx serve .

# Using Python
python -m http.server 3000

# Using VS Code Live Server extension
# Right-click index.html → Open with Live Server
```

Then open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 🎨 Design Highlights

- **Color Palette**: Pure black backgrounds, luxury grey tones (`luxury-200` → `luxury-500`), pure white accents
- **Typography**: Wide tracking (`tracking-[0.4em]`), uppercase transforms, bold display text up to `9xl`
- **Animations**: CSS `translateY` + `opacity` scroll reveals, `duration-500` transitions
- **Layout**: Max-width `1400px` centered container, responsive padding

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

> **Disclaimer**: This project is a personal/educational frontend clone inspired by ZARA's design language. It is not affiliated with, endorsed by, or connected to Inditex or ZARA in any way.

---

<div align="center">

Made with ❤️ by [ellsimohammed8-prog](https://github.com/ellsimohammed8-prog)

⭐ Star this repo if you found it helpful!

</div>
