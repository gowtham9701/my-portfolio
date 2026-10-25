# Gowtham Kumar — Software Engineer Portfolio

A responsive, motion-enhanced portfolio for **Nayudu Venkata Gowtham Kumar**, a Software Engineer at Ford Credit in Chennai, India. The site presents his experience, SmartEscrow project, technical toolkit, education, certifications, resume, and contact information in an original dark editorial design.

- **Live code:** <https://github.com/gowtham9701/my-portfolio>
- **GitHub profile:** <https://github.com/gowtham9701>
- **LinkedIn:** <https://www.linkedin.com/in/n-v-gowtham-kumar-428830190/>

## Highlights

- Responsive layout with a mobile navigation menu.
- Animated hero entrance, orbital portrait accents, and reveal-on-scroll section transitions.
- Honors the visitor's `prefers-reduced-motion` setting.
- Featured SmartEscrow project overview, Ford Credit experience, technical skills, education, and certifications.
- Downloadable copy of the resume included in `assets/`.
- Accessible skip link, semantic page sections, descriptive portrait text, and keyboard-operable navigation.

## Technology

This is a dependency-free static site built with:

- Semantic HTML
- CSS, responsive layouts, and keyframe transitions
- Vanilla JavaScript for the mobile menu and scroll reveals
- Google Fonts (Manrope, Space Grotesk, and DM Mono)

There is no package installation, bundling, or build step.

## Run locally

Install Python 3, then serve the project root:

```bash
python3 -m http.server 4173 --bind 127.0.0.1
```

Open <http://127.0.0.1:4173> in a browser. A local server makes the resume download work consistently; the external typefaces require an internet connection.

## Project structure

```text
.
├── index.html
├── styles.css
├── script.js
├── README.md
└── assets/
    ├── favicon.svg
    ├── gowtham-portrait.png
    └── Venkata_Gowtham_Kumar_Nayudu_Resume.pdf
```

## Updating content and assets

- Edit portfolio text, links, and section content in `index.html`.
- Replace `assets/gowtham-portrait.png` to change the portrait, keeping the same filename or updating its reference in the HTML.
- Replace `assets/Venkata_Gowtham_Kumar_Nayudu_Resume.pdf` to update the resume download.
- Edit `styles.css` for colors, layout, responsive breakpoints, and transitions.
- Edit `script.js` for mobile navigation and reveal-on-scroll behavior.

## Deploy

The repository is ready to deploy as a static site:

- **GitHub Pages:** In repository **Settings → Pages**, choose **Deploy from a branch**, select `main` and the `/ (root)` folder, then save.
- **Vercel / Netlify:** Import the repository and select a static site with the repository root as the publish directory. No build command is needed.

Keep `index.html`, `styles.css`, `script.js`, and the `assets/` folder together at the site root.
