# astro-dynamic-navbar

A modern, responsive, and accessible navigation bar component for [Astro](https://astro.build/), built with **pure CSS** and ready for production.

## ✨ Features

- ✅ Logo and brand link
- ✅ Built-in light/dark mode toggle (default: dark)
- ✅ Mobile hamburger menu
- ✅ Responsive design with clean layout
- ✅ Minimal dependency (pure HTML/CSS/JS)
- ✅ Easy to install and use — no custom styling required

---
## 🚀 Example Usage

```astro
---
// Example.astro
import Navbar from "astro-dynamic-navbar";

const links = [
  { href: "/", text: "Home" },
  { href: "/about", text: "About" },
  { href: "/contact", text: "Contact" },
];
---

<Navbar
  logoSrc="/favicon.svg"
  brandName="MySite"
  links={links}
/>
```


## 📦 Installation

```bash
npm install astro-dynamic-navbar
