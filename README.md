# 🌱 AVABODH Foundation — NGO Website

> **Building aware minds and resilient communities.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=for-the-badge&logo=googlechrome)](https://avabodh-foundation.netlify.app)
[![Framework](https://img.shields.io/badge/Framework-React%2018-61DAFB?style=for-the-badge&logo=react)](https://react.dev)
[![Styling](https://img.shields.io/badge/Styling-TailwindCSS-38BDF8?style=for-the-badge&logo=tailwindcss)](https://tailwindcss.com)
[![Build Tool](https://img.shields.io/badge/Build-Vite-646CFF?style=for-the-badge&logo=vite)](https://vitejs.dev)
[![Version](https://img.shields.io/badge/Version-0.0.1-orange?style=for-the-badge)](#)
[![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)](#)

---

## 📖 About

This is the official website for **AVABODH Foundation** — a grassroots non-profit organization committed to building informed, empowered, and resilient communities across India. The name "AVABODH" means *awareness and understanding*, values that sit at the heart of everything the foundation does.

The website serves as a digital presence for the foundation, showcasing its mission, initiatives, photo gallery, and providing a way for volunteers, partners, and supporters to connect.

---

## 🖥️ UI Preview

<div align="center">
  <img src="https://github.com/user-attachments/assets/41ad6e58-766e-43a7-b9c9-8e89ceee030a" 
       alt="AVABODH Foundation Website UI Preview" 
       width="900"
       style="border-radius: 10px; box-shadow: 0 4px 20px rgba(0,0,0,0.2);" />
</div>
---

## ✨ Features

| Feature | Description |
|---|---|
| 🏠 **Home Page** | Hero section with mission statement, social media cards, and CSR partnership section |
| 📖 **About Page** | Foundation story, mission & vision, focus areas, and core values |
| 🖼️ **Photo Gallery** | Filterable masonry grid with 43+ images and a full lightbox viewer |
| 📬 **Contact Page** | Contact form (mailto-based), FAQ accordion, and CSR collaboration card |
| 🌙 **Dark Mode** | Full dark/light mode toggle with smooth transitions |
| 📱 **Responsive Design** | Mobile-first layout that works on all screen sizes |
| ⚡ **Vite Build** | Fast development server and optimized production builds |
| 🔗 **React Router** | Client-side routing with scroll-to-top on navigation |

---

## 🗂️ Pages & Components

### Pages
| Page | Route | Description |
|---|---|---|
| Home | `/` | Hero, stats strip, initiatives grid, CSR section |
| About | `/about` | Foundation story, mission/vision, focus areas, values |
| Gallery | `/gallery` | Filterable photo grid with lightbox |
| Contact | `/contact` | Contact form, contact methods, FAQ |

### Components
| Component | Description |
|---|---|
| `Navigation` | Sticky navbar with dark mode toggle and mobile hamburger menu |
| `Header` | Full-page hero with social media cards and contact info |
| `Stats` | Three-column impact highlights strip |
| `Initiatives` | Card grid of the three flagship intervention areas |
| `CSR` | Dark-background CSR partnership call-to-action section |
| `Footer` | Four-column footer with links, contact details, and social icons |
| `Logo` | Logo components (`LogoIcon`, `LogoFull`) from SVG/PNG assets |

---

## 🏗️ Project Structure

```
NGO/
│
├── public/
│   └── images/
│       ├── folder1/          # Event photography (RCP_68xx.JPG)
│       └── folder2/          # Activity & program photos (img*.jpg, IMG_*.jpg)
│
├── src/
│   ├── assets/               # Logo files (logo-1.png, logo-2.png, logo-3.svg)
│   │
│   ├── components/
│   │   ├── Navigation.jsx    # Sticky nav with dark mode toggle
│   │   ├── Header.jsx        # Hero section with social cards
│   │   ├── Stats.jsx         # Impact highlights strip
│   │   ├── Initiatives.jsx   # Flagship program cards
│   │   ├── CSR.jsx           # CSR partnership section
│   │   ├── Footer.jsx        # Site footer
│   │   └── Logo.jsx          # Logo components
│   │
│   ├── pages/
│   │   ├── Home.jsx          # Composes Header + Stats + Initiatives + CSR
│   │   ├── About.jsx         # Foundation story, values, focus areas
│   │   ├── Gallery.jsx       # Filterable masonry gallery + lightbox
│   │   └── Contact.jsx       # Contact form + FAQ accordion
│   │
│   ├── App.jsx               # Root app with router + dark mode state
│   ├── main.jsx              # React entry point
│   └── index.css             # Global styles
│
├── dist/                     # Production build output
├── index.html                # HTML entry point
├── tailwind.config.js        # Tailwind configuration
├── vite.config.js            # Vite configuration
├── postcss.config.js         # PostCSS config
└── package.json              # Dependencies & scripts
```

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **React 18** | UI component framework |
| **React Router DOM v7** | Client-side navigation and routing |
| **Tailwind CSS v3** | Utility-first styling |
| **Vite v4** | Development server and build tool |
| **PostCSS + Autoprefixer** | CSS processing |

---

## 🚀 Getting Started

### Prerequisites
- Node.js v16 or higher
- npm or yarn

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME/NGO

# 2. Install dependencies
npm install

# 3. Start the development server
npm run dev
```

The app will be available at `http://localhost:5173`

### Build for Production

```bash
# Build optimized production files into /dist
npm run build

# Preview the production build locally
npm run preview
```

---

## 📜 Available Scripts

| Script | Command | Description |
|---|---|---|
| Dev server | `npm run dev` | Start Vite development server with HMR |
| Build | `npm run build` | Create optimized production build in `/dist` |
| Preview | `npm run preview` | Serve the production build locally |

---

## 🎨 Design System

The website uses a custom Tailwind configuration with the following design tokens:

| Token | Value | Usage |
|---|---|---|
| `primary` | Blue (`#1d4ed8`) | CTAs, links, active states |
| `secondary` | Green | Education tag, success states |
| `accent` | Amber | Community tag, warm highlights |
| `background-light` | White | Light mode page background |
| `background-dark` | Dark gray | Dark mode page background |
| `card-light` / `card-dark` | Surface colors | Card backgrounds |
| `font-display` | Display font | Headings and brand name |
| `font-sans` | Sans-serif | Body text |

**Dark mode** is implemented using Tailwind's `dark:` variant, toggled via a `isDark` state in `App.jsx`.

---

## 🖼️ Image Gallery

The gallery contains **43+ real photos** from AVABODH Foundation's programs, split into two categories:

- **Events & Gatherings** (13 photos) — `public/images/folder1/` — Professional event photography (RCP series)
- **Activities & Programs** (30 photos) — `public/images/folder2/` — Field activity and program documentation

The gallery features a category filter, responsive masonry grid, hover zoom effect, full-screen lightbox with prev/next navigation, and an image counter.

---

## 📬 Contact & Links

| Channel | Link |
|---|---|
| 📧 Email | [avabodhfoundation@gmail.com](mailto:avabodhfoundation@gmail.com) |
| 📷 Instagram | [@avabodh_foundation](https://www.instagram.com/avabodh_foundation/) |
| 💼 LinkedIn | [Avabodh Foundationn](https://www.linkedin.com/company/avabodh-foundationn) |
| 📞 Phone | +91 86002 90844 / +91 90966 17654 |

---

## 🤝 CSR Partnership

AVABODH Foundation actively collaborates with companies and institutions for CSR (Corporate Social Responsibility) programs. The website's CSR section highlights:

- Need-Aligned Program Design
- Field-Led Execution Support
- Structured Progress Communication

**To initiate a CSR partnership**, reach out at [avabodhfoundation@gmail.com](mailto:avabodhfoundation@gmail.com?subject=CSR%20Partnership%20Enquiry)

---

## 🔮 Future Enhancements

- [ ] Deploy to Netlify / Vercel with custom domain
- [ ] Add donation gateway integration
- [ ] Blog/news section for updates and articles
- [ ] Volunteer registration form with backend
- [ ] Multilingual support (Hindi, Marathi)
- [ ] PWA support for offline access
- [ ] SEO optimization with meta tags and Open Graph

---

## 📄 License

This project is developed for **AVABODH Foundation**. All rights reserved.

---
