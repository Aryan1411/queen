# Nisha — Data Scientist Portfolio

MIT Licensed single-page portfolio website for Nisha, a Data Scientist with 3 years of experience as a Data Analyst. It highlights skills, projects (MAD1, MAD2, BDM, etc.), experience, and contact details in an aesthetic, performant layout.

## Overview
- Clean, aesthetic design with subtle gradients and glassmorphism
- Sections: Hero, About, Skills, Projects, Experience, Contact
- Fast: no heavy libraries, single HTML with inline CSS/JS
- Accessible: semantic markup, labels, focusable buttons
- Mobile-friendly: responsive grid and mobile menu
- Theme toggle: Light/Dark mode with persistence
- SEO: Person JSON‑LD and meta tags

## Setup
1. Save the files in your repository:
   - index.html
   - README.md
2. (Optional) Add your resume file at the project root as resume.pdf to enable the Download Resume button.
3. Customize links and contact info inside index.html:
   - Replace nisha@example.com with your actual email.
   - Update social links (LinkedIn, GitHub).
   - Replace project links (Case Study, Live Demo, Repo) with real URLs.

To run locally:
- Double-click index.html or serve with any static server (e.g., npx serve .).

To deploy on GitHub Pages:
- Commit to a public repo.
- In Settings → Pages, select the main branch root.
- Wait for the site to build and load at https://<username>.github.io/<repo>/.

## Usage
- Navigate via the top navigation or scroll.
- Toggle theme with the moon icon.
- Contact form shows a confirmation message (no backend). To enable real submissions, connect to a service like Formspree or a serverless function and update contactSubmit in the script.
- Update content:
  - Hero, About, Skills: edit the corresponding sections.
  - Projects: six example cards including MAD1, MAD2, BDM. Replace titles, descriptions, and tags as needed.
  - Experience: adjust dates and bullet points to match your roles.

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