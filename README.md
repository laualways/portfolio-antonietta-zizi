# 🎨 Antonietta Zizi Monograph Portfolio

A production-ready, elegant, and highly responsive monographic digital art catalog built for the renowned Sardinian artist **Antonietta Zizi**, showcasing her lifetime work across Painting, Ceramics, Conservative Restoration, and Monumental Muralism.

The architecture of this project departs from generic templates to embrace a strict **"fine-art book / print monograph" aesthetic**, utilizing a warm, minimal layout, rigid alignment structures, and balanced typography.

## 🚀 Live Demo
🚧 **Project Status:** Under Active Refinement (Production Phase)  
🔗 • Live Demo: [Visit Live Site](https://antoniettazizi.netlify.app/)

## 📐 Engineering & Architectural Highlights

Even without relying on JavaScript, this project serves as a showcase of semantic engineering, advanced layout layouts, and strict modern frontend web standards:

* **Fluid & Rigid Layout Grid:** Built completely from scratch using native CSS3 features. All core sections (Navbar, Hero, Body content, and Footer) inherit a global `padding: 0 10%` system, ensuring mathematical symmetry and layout alignment across high-resolution desktop environments.
* **Production-Grade Typography & Palette:** Implements a calculated institutional contrast system:
    * **Background:** `#f9f9f9` (Elegantly muted off-white)
    * **Primary Text:** `#333333` (Highly readable dark charcoal)
    * **Institutional Accent Colors:** `#d4af37` (Gallery Gold) and Deep Espresso Brown (`#4a3c31`).
* **The Date Alignment Resolution (CSS Flexbox):** Solved the common junior pitfall of timeline detail wrapping by enforcing hard min-widths (`min-width: 160px; flex-shrink: 0;`) on CV date columns, guaranteeing that text blocks never overlap or collapse on modern screens.
* **Press Card Micro-interactions:** The institutional Press Section utilizes modular card components that dynamically respond to hover mechanics (`transform: translateY(-5px);`) with smooth CSS transitions, mimicking modern app patterns using vanilla layout engines.
* **Strict Responsive Architecture:** Handcrafted responsive layout transitions via localized Media Queries. Below `850px`, complex side-by-side components reflow elegantly: the Bio-Hero section utilizes a `flex-direction: column-reverse` stack to prioritize biographical narrative below the portrait on smaller mobile interfaces.

---

## 🛠️ Tech Stack & Ecosystem

* **Frontend:** Semantic HTML5, Advanced CSS3 (Flexbox, Custom Layout Properties).
* **Methodology:** Atomic CSS Structure, Clean Code principles, zero external framework overhead.
* **Quality & Standards:** Targeting optimal Google Lighthouse scores (>90) for Accessibility, SEO, and Performance.
* **Deployment:** Integrated via Git workflows and continuous deployment pipelines.

---

## 📂 Page Architecture

```text
├── index.html        # Main Monograph Portal
├── biography.html    # Artist Biography & Professional Path
├── gallery.html      # Fine Art Portfolio Matrix
├── contacts.html     # Artist Inquiries & Institutional Links
├── style.css         # Global Stylesheet
└── images/           # Assets & Art Catalog Images