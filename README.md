# 🏛️ Arsha Landing Page — Professional Corporate UI

![Status](https://img.shields.io/badge/Status-Production%20Ready-success?style=for-the-badge)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)

A clean, modern, and high-performance corporate landing page built with a focus on **Semantic HTML5**, **Bootstrap 5**, and **Lightweight JavaScript**. This project demonstrates the implementation of a professional business interface with a strong emphasis on cross-browser compatibility and responsive performance.

---

## 🚀 Features

* **Responsive Corporate Layout**: A fully adaptive interface optimized for business showcase.
* **Filterable Portfolio Gallery**: Integrated with Isotope for smooth, category-based content sorting.
* **Interactive FAQ Accordion**: Clean, script-driven UI for handling complex information architecture.
* **Skill Progress Indicators**: Dynamic bars to visualize professional competencies.
* **Smooth Scroll Navigation**: One-page navigation logic with active-link state management.
* **Optimized Contact Form**: A structured layout for lead generation and business inquiries.

---

## 🛠️ Tech Stack

* **Structure**: Semantic HTML5 for SEO and accessibility.
* **Styling**: Bootstrap 5 (CSS Framework) for grid-based layout and utility classes.
* **Interactions**: Vanilla JavaScript & jQuery for DOM manipulation and event handling.
* **Animations**: AOS (Animate On Scroll) for high-performance scroll-triggered transitions.
* **Assets**: GLightbox for image viewing and Isotope for dynamic layout filtering.

---

## 🧠 Engineering Highlights

### 1. Mobile-First Grid Orchestration
The layout is engineered using the **Bootstrap 5 Grid System**. By leveraging flexbox-based row/column structures, the project maintains structural integrity across diverse screen sizes without the overhead of custom media query management.

### 2. High-Performance Scroll Animations
Instead of heavy animation libraries, this project utilizes **AOS (Animate On Scroll)**. This ensures that visual entrance effects are hardware-accelerated and only triggered when elements enter the viewport, maintaining a high frame rate on mobile devices.

### 3. SEO & Accessibility Optimization
The code follows W3C standards, utilizing semantic tags (`<section>`, `<article>`, `<nav>`) to improve search engine indexing and screen reader compatibility. Image assets are optimized with appropriate `alt` tags and lazy-loading attributes.

### 4. Efficient Asset Management
Utilizing a modular CSS structure where global styles are separated from component-specific styles. This approach simplifies maintenance and allows for faster CSSOM (CSS Object Model) construction by the browser.

---

## 📁 Folder Structure

```text
ArshaLandingPage/
├── assets/
│   ├── css/          # Main stylesheet and vendor CSS (Bootstrap, AOS, etc.)
│   ├── js/           # Main logic (main.js) and vendor scripts
│   ├── img/          # Optimized portfolio and team photography
│   └── vendor/       # External libraries (GLightbox, Isotope, etc.)
├── index.html        # Main entry point and semantic structure
└── README.md         # Project documentation
```

---

## Getting Started

### 1. Clone the repoitory
git clone [https://github.com/K01J10W19/ArshaLandingPage.git](https://github.com/K01J10W19/ArshaLandingPage.git)

### 2. Open the project
Simply open index.html in any modern web browser.

### 3. Deployment
The project is ready to be hosted on GitHub Pages, Vercel, or Netlify as a static site.

---

## Responsive Strategy

* **Smartphones (390px - 640px)**: Content is stacked into a single column with a focus on touch-friendly navigation.
* **Tablets (768px - 1024px)**: 2-column grid layout for services and team sections.
* **Large Screens (1280px+)**: Full-width container management with generous whitespace to maintain a premium corporate feel.
