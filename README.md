# Tran Minh Huy — Personal Website

Academic personal website / portfolio of **Tran Minh Huy**, Computer Science undergraduate (HCMUT — Japan-Oriented Program), researching computer vision, multimodal retrieval, and 3D/4D scene reconstruction.

## 🌐 Live site
👉 https://Huyrua27.github.io

## 📂 Structure
- `index.html` — Main page: animated hero (canvas particles), about, education, experience, skills, projects, publications, awards, image gallery (lightbox), additional information, contact.
- `Resume_Tran_Minh_Huy.pdf` — CV (downloadable from the site).
- `Photometric_4DGS_Paper.pdf` — Research manuscript, "Photometric-consistent 4D Gaussian Splatting for Multimodal Sensor Alignment in Dynamic Multi-Person Scenes".
- `AIC.jpg`, `OAI.jpg`, `SOICT1.jpg`, `SOICT2.jpg`, `SummerCourse.jpg`, `Vinhdanh1.jpg`, `Vinhdanh2.JPG` — Event photos used in the Gallery section.
- `README.md` — This file.

## ✨ Highlights
- Academic, minimal, professional design: Fraunces (serif) + Inter (sans) + JetBrains Mono.
- Subtle "constellation" canvas background with drifting glow orbs (disabled automatically under `prefers-reduced-motion`).
- Scroll-reveal animation per section, animated education/experience timeline.
- Bento-grid image gallery with click-to-zoom lightbox.
- No framework or build step — plain HTML/CSS/JS, opens directly in a browser.

## 🚀 Deploying to GitHub Pages
1. Create a GitHub repository named **`yourusername.github.io`** (replace with your GitHub username, e.g. `Huyrua27`).
2. Clone it locally:
   ```bash
   git clone https://github.com/Huyrua27/Huyrua27.github.io.git
   cd Huyrua27.github.io
   ```
3. Copy the contents of this folder into the repo, commit, and push:
   ```bash
   git add .
   git commit -m "Update personal site with new CV and projects"
   git push origin main
   ```
4. The site auto-deploys at `https://Huyrua27.github.io` within a few minutes.

## 🛠️ Updating content
- Edit CV information directly inside the corresponding `<section>` in `index.html`.
- To add a gallery photo: drop the image file in the project root and add a `<div class="gitem g-x" data-full="filename.jpg">...</div>` block inside the `#gallery` section.
- When updating the CV, replace `Resume_Tran_Minh_Huy.pdf` (keep the same filename) so the "Download CV" button keeps working.
