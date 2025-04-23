# ✝️ Yireh 3D Website

This is the official custom-coded website for **Yireh Business Solutions**, built entirely with love, purpose, and pixels that mean something.

No templates. No WordPress. Just clean, faith-driven code designed from scratch using modern tools and powerful 3D visuals.

---

## 🚀 Live Vision

The site is a full 3D landing experience, powered by React Three Fiber and optimized for performance, engagement, and premium vibes — built with intention to reflect the excellence and faith at the heart of the Yireh brand.

---

## 🛠️ Tech Stack

- **Vite** — Lightning-fast build tooling
- **React** — Component-based frontend
- **React Three Fiber** — 3D engine for immersive scenes
- **Three.js** — Core WebGL power under the hood
- **TailwindCSS** — Utility-first styling
- **EmailJS** — Lightweight form handling (contact integration)
- **Framer Motion / GSAP** — (Optional) Smooth animations
- **Custom Shaders & Blender Models** — Handcrafted assets (coming soon)

---

## 📁 Project Structure

```bash
yireh3Dsite/
├── public/           # Static assets (models, textures, favicon, etc.)
├── src/
│   ├── components/   # Reusable UI and 3D components
│   ├── constants/    # Configs, links, static text
│   ├── hooks/        # Custom hooks (e.g. scroll control)
│   ├── sections/     # Main sections of the page
│   └── App.jsx       # Root app structure
├── index.html        # Entry point
├── vite.config.js    # Vite configuration
└── dist/             # ✅ Production build output (upload this to hosting)
⚙️ Development
To run the site locally in dev mode:

bash
Copy
Edit
npm install
npm run dev
Open http://localhost:3000 (or whatever port it shows) to view the site live.

📦 Production Build
To generate the build for deployment:

bash
Copy
Edit
npm run build
The compiled static files will appear in the dist/ folder.
Upload everything inside dist/ to your server’s public_html/ directory.

🌐 Hosting Notes
Hosting: domains.co.za

Recommended: Upload via cPanel or FTP

Make sure to delete any WordPress files first

Add this .htaccess to enable routing (if using React Router):

apache
Copy
Edit
<IfModule mod_rewrite.c>
  RewriteEngine On
  RewriteBase /
  RewriteRule ^index\.html$ - [L]
  RewriteCond %{REQUEST_FILENAME} !-f
  RewriteCond %{REQUEST_FILENAME} !-d
  RewriteRule . /index.html [L]
</IfModule>
📬 Contact Form Integration
We’re using EmailJS to handle contact form submissions without a backend. Configure it in the component and add your public key, service ID, and template ID.

Tip: Rotate or hide keys in .env if you push this to GitHub.

✨ Credits
This project was handcrafted by Dylan Jonker, for the glory of God and the future of Yireh.

"But seek first the kingdom of God and His righteousness, and all these things will be given to you as well." — Matthew 6:33

yaml
Copy
Edit
