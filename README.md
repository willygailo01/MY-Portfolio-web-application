# Willy Gailo Portfolio

## Short Description
A premium dark-themed personal portfolio website built with pure HTML, CSS, and JavaScript, featuring modular sections, smooth animations, and dynamic content loading.

## Features
- Fully responsive layout (desktop, tablet, mobile)
- Sticky glassmorphism navbar with active section highlight
- Hero section with particles and typewriter effect
- JSON-driven skills, projects, and testimonials
- Project lightbox and testimonial slider
- Custom animated background effects (aurora, grid, glow, hearts)

## Tech Stack
- HTML5
- CSS3 (modular files)
- Vanilla JavaScript (ES modules)

## Run Locally
Use a local server because sections/components/data are loaded via `fetch`.

```bash
python -m http.server 5500
```

Then open:

```text
http://localhost:5500
```

## Project Structure
```text
portfolio/
├── index.html
├── assets/
│   ├── css/
│   ├── js/
│   ├── images/
│   └── fonts/
├── sections/
├── components/
├── data/
├── utils/
├── README.md
└── LICENSE
```

## Notes
- Update content in `sections/*.html`
- Update portfolio entries in `data/projects.json`
- Update social links in `components/footer.html`
