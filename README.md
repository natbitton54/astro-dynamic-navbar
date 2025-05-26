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
import Navbar from "../components/Navbar.astro";

const links = [
  { href: "/", text: "Home" },
  { href: "/about", text: "About" },
  { href: "/contact", text: "Contact" },
];
---
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Custom Navbar</title>

    <style>

      body {
        margin: 0;
        background: #222;
        font-family: system-ui, sans-serif;
      }

      main {
        padding: 3rem;
        text-align: center;
        color: white;
      }
    </style>
  </head>

  <body>
    <Navbar
      logoSrc="/favicon.svg"
      brandName="MySite"
      links={links}
    />

    <main>
      <h1>Welcome to MySite</h1>
      <p>This is a live preview of your fully styled navbar.</p>
    </main>
  </body>
</html>
```

## 📦 Installation

```bash
---
import Navbar from "@natbitton54/astro-dynamic-navbar";
