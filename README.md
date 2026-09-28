# Kalyani Charitable Trust — Official Website

A production-ready, cinematic, 3D-animated, and interactive website for **Kalyani Charitable Trust** (Cuttack, Odisha).

---

## 🚀 Deployment Instructions for GitHub & Vercel

This website has been built with **strict universal compatibility**:

### Option 1: Direct Single-File Upload (Static)
1. Create a new repository on [GitHub](https://github.com/new).
2. Upload `index.html` directly into the root of the repository (`/index.html`).
3. Go to [Vercel](https://vercel.com) and click **"Add New Project"** → **Import** your repository.
4. Leave all settings default (Vercel automatically detects the static HTML project).
5. Click **"Deploy"** — your website is live instantly!

### Option 2: Full Git Repository Push
1. Clone or push this entire repository to GitHub:
   ```bash
   git add .
   git commit -m "feat: Kalyani Charitable Trust premium website"
   git push origin main
   ```
2. Import the repository into **Vercel**.
3. Vercel automatically detects Vite and runs `npm run build` with the `dist` directory.
4. Click **"Deploy"**.

---

## 🌟 Key Features
- **Cinematic 3D Preloader**: Smoothly unlocks and places the visitor directly at the **Hero Section** (`#home`).
- **10 Core Pages**: Home, About Us, Programmes, Our Impact, Get Involved, Donate / Support, Stories & Reviews, 3D Rotating Gallery, Resources & News, Contact & Google Maps.
- **Specific Google Maps Integrations**:
  - Direct 3D link to **Google Maps Reviews**
  - Direct 3D link to **Google Photos Gallery**
  - Interactive embedded map + Turn-by-Turn **Google Maps Directions**
- **Centralized `NGO_CONFIG`**: Located near the top of the script tag in `index.html` for easy phone, WhatsApp, email, and social media updates.
- **Zero-Dependency Core**: All styles, icons (Lucide CDN), and audio effects are self-contained.
