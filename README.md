# Nebula — Vue + Vite Portfolio

[![Netlify Deploy Status](https://github.com/hiteshpatil912/nebula/actions/workflows/netlify-deploy.yml/badge.svg)](https://github.com/hiteshpatil912/nebula/actions/workflows/netlify-deploy.yml)

[![Netlify Deploys](https://api.netlify.com/api/v1/badges/<NETLIFY_BADGE_ID>/deploy-status)](https://app.netlify.com/sites/<YOUR_SITE_NAME>/deploys)
<!-- Replace <NETLIFY_BADGE_ID> and <YOUR_SITE_NAME> with values from Netlify Site settings → Build & deploy → Build badges -->

This project is a Vue 3 app built with Vite and Tailwind CSS (PostCSS).

## Deployment & Build Configuration

This project is configured for automated deployment to Netlify via GitHub Actions:
- **`.nvmrc`:** Pins Node.js to version 18 for consistent builds on Netlify.
- **`.gitignore`:** Excludes `node_modules/` and `dist/` from the repository so Netlify installs fresh dependencies (`npm ci`) during each build, avoiding permission issues with pre-committed node_modules.
- **`netlify.toml`:** Configures build command (`npm run build`) and publish directory (`dist`).
- **`.github/workflows/netlify-deploy.yml`:** GitHub Actions workflow that builds on all branches and deploys to Netlify production only when pushing to `main`.

For Netlify deploy badges, see the placeholders at the top of this README.

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