# Muhammad Mansoor - Portfolio

Muhammad Mansoor's personal portfolio, showcasing backend and full-stack projects, technical skills, professional experience, and contact links.

## Features

- Responsive layout with a dark theme
- Project cards linking to GitHub repositories
- About, skills, experience, and contact sections
- Smooth navigation between sections

## Technologies

- HTML5
- CSS3
- Vanilla JavaScript, embedded in `index.html`

The site uses static files and requires no build step or package installation.

## Project Structure

```text
index.html   Page content, metadata, and navigation scripts
style.css    Layout, theme, and responsive styles
README.md    Project documentation
```

## Local Development

Clone the repository:

```bash
git clone https://github.com/engr-muhammad-mansoor/portfolio-.git
cd portfolio-
```

Open `index.html` directly in your browser. To preview through a local server instead, run the following from the repository directory with Python 3 installed:

```bash
python -m http.server 8000 --bind 127.0.0.1
```

Visit [http://127.0.0.1:8000](http://127.0.0.1:8000). Press `Ctrl+C` in the terminal to stop the server.

## Editing the Portfolio

- Update text, project links, contact details, and page metadata in `index.html`.
- Update colors, spacing, layouts, and responsive breakpoints in `style.css`.
- Preview the page at desktop and mobile widths, and check navigation and external links after making changes.

## Deployment

Deploy the repository root to a static hosting service, serving `index.html` as the entry page. Keep `style.css` beside it so the relative stylesheet link works. No build command or generated output directory is needed.

## License

© 2026 Muhammad Mansoor. All rights reserved.

