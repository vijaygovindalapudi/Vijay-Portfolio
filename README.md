# Vijaya Nooka Raju — 3D Interactive Portfolio

A responsive React + Vite portfolio with CSS 3D orbital artwork, mouse-tilt project cards, Framer Motion section reveals, and reduced-motion accessibility.

## Run locally
1. Install Node.js 20+.
2. Open this folder in VS Code.
3. Run `npm install`.
4. Run `npm run dev`.
5. Open the local URL printed by Vite (usually http://localhost:5173).

## Build and deploy
Run `npm run build`. Upload the `dist` folder to a static hosting provider, or connect this repository to Vercel/Netlify with build command `npm run build` and output directory `dist`.

## Customize
- Content, project and certificate links: `src/main.jsx`
- Colors, animation and responsive styling: `src/style.css`
- Resume download: replace `public/Vijaya_Nooka_Raju_Resume.pdf`.

## Notes
- Project descriptions are based on the provided resume, not a source-code audit.
- FinRelief AI has no supplied repository or demo link.
- Certificate links use the supplied Google Drive URLs; public sharing permissions must be checked by the owner.
- Contact button opens the visitor's email app; no backend or form submission is claimed.
- The 3D visual uses CSS rather than WebGL, making it lightweight and mobile friendly.
