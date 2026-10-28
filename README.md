# Portfolio — Shameen Dudekula

Personal portfolio of **Shameen Dudekula**, a Computer Science and Engineering student (exchange at Blekinge Institute of Technology, Sweden) working on full-stack web development and applied AI. It is a single responsive page built with HTML, Tailwind CSS and Alpine.js, deployed on Vercel.

---

## 🌍 Live Demo

🔗 **https://portfolio-shameen.vercel.app**

---

## 🗂 Sections

| Section | Content |
|--------|---------|
| **Hero** | Name, location, current roles, resume view/download, photo |
| **About** | Short introduction, Education (BTH, JNTUA) and a 2024–2026 journey timeline |
| **Experience** | Infosys Springboard Virtual Internship 7.0 |
| **Skills** | Programming, Web & Backend, Data & Applied AI, Tools |
| **Projects** | WardrobeIQ, COVID-19 Simulation, AI Real Estate Valuation, XMENTOR (research), Student Learning Hub |
| **Certificates & Activities** | Web Development Internship, Ideation 2026 Phase 1 |
| **Contact** | Contact form plus LinkedIn, GitHub and email |

---

## ✨ Features

| Feature | Details |
|--------|---------|
| **Responsive design** | Mobile-first layout tested at 375px, 768px, 1024px and 1440px; no horizontal scrolling on phones |
| **Mobile navigation** | Hamburger menu below 768px that closes when a link is tapped, on outside click or with Esc; headings are offset so they aren't hidden under the fixed navbar |
| **Project showcase** | Project cards with category labels and Alpine.js filters: All, Full-Stack Web, Python & AI, Research |
| **Contact form** | Name / Email / Message form sent via [FormSubmit](https://formsubmit.co) using `fetch()`, with client-side validation, a "Sending…" state, success/error messages and a honeypot spam filter |
| **Dark mode** | Toggle in the navbar; follows the system preference, remembers your choice (`localStorage`) and is applied before the page paints (no white flash) |
| **Accessibility** | Labelled buttons, `aria-expanded` / `aria-pressed` states, and `prefers-reduced-motion` support that turns off animations |
| **Resume** | View or download the latest CV (PDF) from the hero section |
| **Scroll animations** | Sections fade in on scroll using `IntersectionObserver` |

---

## 🛠 Tech Stack

- **HTML5** — semantic page structure
- **Tailwind CSS 3.4** (CDN) — utility-first styling and responsive breakpoints
- **Alpine.js 3.14** — mobile menu, dark-mode toggle, project filters, navbar scroll effect
- **JavaScript (ES6+)** — contact form submission and scroll reveal
- **FormSubmit** — form-to-email service (no backend needed)
- **Git & GitHub** — version control
- **Vercel** — hosting with automatic deploys from `main`

---

## 🚀 Run Locally

```bash
git clone https://github.com/Shameendudekula/portfolio.git
cd portfolio
npx serve .
```

Then open http://localhost:3000.

> **Note:** The first time the contact form is used, FormSubmit sends a one-time activation email to the receiving address. Messages are delivered once it is confirmed.

---

## 📁 Project Structure

```
portfolio/
├── index.html           # The whole site (markup, Tailwind config, scripts)
├── Shameen_Resume.pdf   # Latest CV (linked from the hero buttons)
├── passport_photo.jpg   # Profile photo
└── README.md
```

---

## 📸 Screenshots

> _Screenshots coming soon._

| View | Screenshot |
|------|-----------|
| Desktop — Hero | `![Desktop hero](screenshots/desktop-hero.png)` |
| Desktop — Projects | `![Desktop projects](screenshots/desktop-projects.png)` |
| Mobile (375px) | `![Mobile view](screenshots/mobile.png)` |
| Mobile menu | `![Mobile menu](screenshots/mobile-menu.png)` |
| Dark mode | `![Dark mode](screenshots/dark-mode.png)` |
| Contact form | `![Contact form](screenshots/contact-form.png)` |

---

## 📬 Contact

- Email: dudekulasha2006@gmail.com
- LinkedIn: https://linkedin.com/in/shameen-d
- GitHub: https://github.com/Shameendudekula
