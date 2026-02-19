# Nebula — Vue + Vite Portfolio

[![Netlify Deploy Status](https://github.com/hiteshpatil912/nebula/actions/workflows/netlify-deploy.yml/badge.svg)](https://github.com/hiteshpatil912/nebula/actions/workflows/netlify-deploy.yml)

This project is a Vue 3 app built with Vite and Tailwind CSS (PostCSS).

Important notes
- `index.html` must remain in the project root (this is the Vite entry/mount point). Do NOT open `index.html` directly in the browser using `file://` — it relies on Vite's dev server or an HTTP server to load ES modules.
- The Tailwind styles are built during the Vite build process from `src/assets/index.css`. The dev server (npm run dev) injects the compiled CSS via HMR.

Quick start (PowerShell):
```powershell
cd "d:\DWEBPIXEL\practice\AI\AI Template\New folder\NEBULA"
npm install
npm run dev       # preview at http://localhost:5173 (dev)
# For production build:
npm run build
npm run preview   # serve the built files
```

If changes are not showing in your browser:
1. Make sure you start the dev server (npm run dev) and open http://localhost:5173.
2. Do a hard refresh (Ctrl+F5) or clear cache; service workers or cached files may show old assets.
3. If you previously opened `dist/index.html` directly in the browser or served `dist/` from another server, rebuild after changes: `npm run build`.

Recommended next steps I can do for you
- Add a theme toggle (light/dark) with CSS variables.
- Replace placeholder images with your assets and add responsive srcset.
- Run Lighthouse and fix accessibility/contrast issues.
- Create a deploy script for Netlify/Vercel/GH Pages.

Tell me which next step you'd like and I'll implement it.