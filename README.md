# Ramim Ahmed — 3D Portfolio

**Software Developer & AI Systems Builder 🚀**

[![Next.js](https://img.shields.io/badge/Next.js-16-black?logo=nextdotjs)](https://nextjs.org/)
[![React Three Fiber](https://img.shields.io/badge/Three.js-R3F-blue?logo=threedotjs)](https://docs.pmnd.rs/react-three-fiber)
[![Tailwind CSS v4](https://img.shields.io/badge/Tailwind_CSS-v4-38B2AC?logo=tailwindcss)](https://tailwindcss.com/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?logo=typescript)](https://www.typescriptlang.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

An immersive, interactive 3D developer portfolio owned, created, and maintained by **Ramim Ahmed**. Built with Next.js App Router, React Three Fiber, Three.js, and Tailwind CSS v4, this portfolio showcases custom AI assistants, automated workflows, and full-stack web applications with high-performance 3D graphics and seasonal aesthetics.

🌐 **Live Website:** [https://twkrofficial.github.io/Ramim-Portfolio-3d/](https://twkrofficial.github.io/Ramim-Portfolio-3d/)  
💻 **GitHub:** [@twkrofficial](https://github.com/twkrofficial)  
📫 **Contact:** [Ramimahmeedhome@gmail.com](mailto:Ramimahmeedhome@gmail.com)

---

## 🌟 Highlights & Features

- **Interactive 3D Mechanical Keyboard** — An interactive 3D mechanical keyboard rendered in real-time with React Three Fiber and Three.js. Keys respond to user interaction with realistic physics, dynamic lighting, and mechanical switch audio effects.
- **Seasonal Visual Themes** — 4 distinct seasonal palettes (Winter, Spring, Summer, Autumn) dynamically altering lighting, particle effects, background gradients, and UI tokens in real-time.
- **Bilingual Interface (ES / EN)** — Native custom bilingual i18n support with instant switching and local storage persistence.
- **Fluid Cursor & Magnetic UI** — Smooth physics-driven custom cursor with magnetic snapping on interactive controls and buttons.
- **Smooth Scrolling** — Powered by Lenis smooth scrolling with scroll-triggered reveal animations.
- **Mobile-First & Responsive** — Optimized WebGL fallbacks, touch gestures, and responsive layouts designed for mobile, tablet, and desktop viewports.
- **Security-First Architecture** — Preconfigured HSTS, X-Frame-Options, MIME-sniff protection, Referrer-Policy, and Permissions-Policy headers.

---

## 🛠️ Tech Stack

| Domain | Technology |
|---|---|
| **Core Framework** | [Next.js 16](https://nextjs.org/) (App Router, Turbopack) |
| **3D & Graphics** | [React Three Fiber](https://docs.pmnd.rs/react-three-fiber), [@react-three/drei](https://github.com/pmndrs/drei), [Three.js](https://threejs.org/) |
| **Styling & UI** | [Tailwind CSS v4](https://tailwindcss.com/) |
| **Smooth Scrolling** | [Lenis](https://github.com/darkroomengineering/lenis) |
| **Icons** | [Simple Icons](https://simpleicons.org/) |
| **Language** | [TypeScript](https://www.typescriptlang.org/) |
| **Deployment** | GitHub Pages, Vercel, Docker (Standalone output) |

---

## 🚀 Getting Started

### Prerequisites

- **Node.js** 20.9+ (or newer)
- **npm** 10+

### Installation & Local Development

```bash
# Clone the repository
git clone https://github.com/twkrofficial/Ramim-Portfolio-3d.git
cd Ramim-Portfolio-3d

# Install dependencies
npm install

# Start local development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the application.

### Production Build

```bash
npm run build
npm start
```

### Docker Deployment

A multi-stage `Dockerfile` is included for containerized environments:

```bash
docker build -t ramim-portfolio-3d .
docker run -p 3000:3000 ramim-portfolio-3d
```

---

## 📁 Project Architecture

```
├── app/
│   ├── globals.css         # Tailwind CSS v4 design tokens and seasonal themes
│   ├── icon.svg            # Custom RA branding icon
│   ├── layout.tsx          # Root layout, HTML head, and global providers
│   └── page.tsx            # Main page sections (Hero, 3D Keyboard, Focus Areas, Contact)
├── components/
│   ├── Carousel.tsx        # Responsive media showcase carousel
│   ├── CopyEmail.tsx       # Interactive clipboard copy button
│   ├── CustomCursor.tsx    # Smooth custom cursor with hover states
│   ├── FrozenBackground.tsx# Seasonal canvas particle system
│   ├── FrozenKeyboard.tsx  # React Three Fiber 3D interactive keyboard
│   ├── LanguagePicker.tsx  # Language toggle control
│   ├── LanguageProvider.tsx# Lightweight i18n context provider
│   ├── MagneticTargets.tsx # Button magnetic snap behavior
│   ├── ProjectModal.tsx    # Detailed modal viewer
│   ├── Reveal.tsx          # Scroll-driven reveal animations
│   ├── ScrollProgress.tsx  # Reading & scroll progress indicator
│   ├── SeasonPicker.tsx    # Seasonal theme selector
│   ├── SeasonProvider.tsx  # Theme context & CSS variable injector
│   ├── SectionNav.tsx      # Lateral section dot navigation
│   └── smooth-scroll.tsx   # Lenis smooth scroll provider
├── lib/
│   ├── i18n.ts             # Multilingual dictionary (EN / ES)
│   ├── profile.ts          # Centralized personal info & metadata
│   ├── seasons.ts          # Theme color palettes and configuration
│   ├── skills.ts           # Tech stack definitions and icons
│   └── useIsMobile.ts      # Viewport detection utility
├── public/
│   ├── fonts/              # Typefaces for 3D typography
│   └── sounds/             # Audio assets for mechanical key switches
├── Dockerfile              # Multi-stage standalone production build
├── next.config.ts          # Next.js configuration and security headers
└── package.json            # Project manifest and scripts
```

---

## 👤 Author & Maintainer

**Ramim Ahmed**  
*Software Developer & AI Systems Builder*

- **GitHub:** [@twkrofficial](https://github.com/twkrofficial)
- **Email:** [Ramimahmeedhome@gmail.com](mailto:Ramimahmeedhome@gmail.com)
- **Portfolio:** [https://twkrofficial.github.io/Ramim-Portfolio-3d/](https://twkrofficial.github.io/Ramim-Portfolio-3d/)

---

## 📄 License

This project is open-source and licensed under the [MIT License](LICENSE) © 2026 Ramim Ahmed.
