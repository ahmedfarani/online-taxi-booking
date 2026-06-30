<div align="center">

# 🚖 Online Taxi Booking - Landing Page

**A responsive, multi-section landing page for a taxi booking service, with sticky navigation and scroll-reveal animations.**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![ScrollReveal](https://img.shields.io/badge/ScrollReveal-animation-orange)

</div>

---

## 📖 Overview

A full **marketing landing page** for a fictional taxi booking company, covering five sections - Home, About, Services, Features, and Contact/Footer. The page is built to feel like a production-ready product site: sticky navigation, animated section reveals, and a fully responsive layout across 8 breakpoints.

## ✨ Features

- **Sticky header on scroll** | the navigation bar gains a `.sticky` class once the user scrolls past 160px, via a `scroll` event listener
- **Auto-closing mobile menu** | the hamburger menu not only toggles open/closed on click, it also automatically closes itself if the user scrolls while it's open
- **Scroll-reveal animations** | powered by [ScrollReveal](https://scrollrevealjs.org/), with directional reveals (left/right/top) and staggered `interval` timing across hero text, images, service cards, and feature blocks
- **Five distinct sections** | Home (hero + stats), About (trust copy + highlights), Services (3-card grid), Features (3-column layout with a centered icon image), and Contact (4-column footer with a QR code)
- **8-tier responsive design** | breakpoints from `1700px` down to `530px` for smooth scaling on tablets and mobile

## 🛠️ Tech Stack

- **HTML5 / CSS3** | semantic sectioned layout with custom responsive breakpoints
- **JavaScript (Vanilla)** | sticky header logic, mobile menu toggle, scroll-triggered menu close
- **[ScrollReveal](https://scrollrevealjs.org/)** | scroll-based reveal animation library (via CDN)
- **[Boxicons](https://boxicons.com/)** | menu icon
- **[Remix Icon](https://remixicon.com/)** | section and social icons
- **Google Fonts (Lexend)** | primary typeface

## 🚀 Getting Started

```bash
git clone https://github.com/ahmedfarani/online-taxi-booking.git
cd online-taxi-booking
```

Open `index.html` directly in a browser. ScrollReveal, Boxicons, Remix Icon, and Google Fonts load from public CDNs, so an internet connection is required for full styling and animation.

## 📁 Project Structure

```
online-taxi-booking/
├── index.html       # Header + 5 sections: Home, About, Services, Feature, Contact
├── style.css         # Theme, layout, and 8-breakpoint responsive design
├── script.js          # Sticky header, mobile menu, ScrollReveal config
└── img/
    ├── logo.png, qrcode.png
    ├── home.png, about1.jpg, about2.png
    ├── s1.jpg, s2.jpg, s3.jpg    # Service section images
    └── f1.png, c.jpg, bg.jpg
```

## 📜 License

This project is open source and available for personal or educational use.

---

<div align="center">

Built by **Ahmed Farani**

</div>
