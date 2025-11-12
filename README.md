# Nisha — Data Scientist Portfolio

MIT Licensed single-page portfolio website for Nisha, a Data Scientist with 3 years of experience as a Data Analyst. It highlights skills, projects (MAD1, MAD2, BDM), experience, and contact details in a colorful, performant layout.

## Overview
- Colorful, animated gradients with tasteful glassmorphism
- New animated buttons: gradient, glow, and ripple on click
- Sample portrait image embedded (offline-friendly SVG)
- Sections: Hero, About, Skills, Projects, Experience, Contact
- Fast: zero dependencies, single HTML with inline CSS/JS
- Accessible: semantic markup, labels, keyboard focus/contrast
- Responsive: mobile-first grid and sticky, blur nav
- Theme toggle: Light/Dark mode with localStorage persistence
- SEO: Person JSON‑LD, meta tags

## Setup
1. Save files at the project root:
   - index.html
   - README.md
2. (Optional) Add your resume as resume.pdf in the project root to enable the “Download Resume” button.
3. Customize content in index.html:
   - Replace nisha@example.com with your actual email.
   - Update social links inside the JSON‑LD and any anchors.
   - Replace project links (Case Study, Live Demo, Repo) with real URLs.
   - Swap the embedded SVG portrait with your image by changing the src of the hero <img>. You can link a local image (e.g., portrait.jpg) or another data URI.

To run locally:
- Double‑click index.html or serve with any static server (for example: npx serve .).

To deploy on GitHub Pages:
- Commit to a public repo.
- In Settings → Pages, select the main branch and root.
- Wait for the site to build and load at https://<username>.github.io/<repo>/.

## Usage
- Navigate using the top navigation or scroll.
- Toggle theme with the icon in the header; preference persists.
- Try the animated buttons; they glow and ripple on click.
- Contact form shows a confirmation message (no backend). To enable real submissions, connect to a service like Formspree or a serverless function and update the submit handler in the script.

Updating content:
- Hero, About, Skills: edit text inside the relevant sections.
- Projects: three example cards (MAD1, MAD2, BDM). Replace titles, descriptions, tags, and links.
- Experience: adjust companies, dates, and bullets.
- Images: the hero contains an embedded SVG portrait; replace with your own image if desired.

## Improvements in Round 2
From the previous version, this update adds:
- More color: multi‑radial animated background gradients and vibrant accents.
- Button animations: gradient primary/ghost buttons with hover elevation, glow, and click ripple.
- Sample picture: an embedded SVG portrait image in the hero (fast, offline, and license‑safe).
- Micro‑interactions: scroll‑reveal animations and animated halo ring around the portrait.
- Visual polish: gradient borders, soft shadows, and refined cards while keeping accessibility and performance.

## License
MIT License

Copyright (c) 2025 Nisha

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the “Software”), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.