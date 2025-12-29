# Copilot Instructions for E-com20

## Project Overview
- **E-com20** is a static, single-page web application for an online library platform.
- The project consists of HTML, CSS, and static assets (SVGs, images) only. There is no backend or build system.
- The main entry point is `index.html`, styled by `styles.css`.

## Key Files & Structure
- `index.html`: Main HTML file. Contains navigation, header, and highlights sections.
- `styles.css`: Centralized CSS for all styling. Uses BEM-like class naming for some elements (e.g., `highlight__img`).
- `assets/`: Contains images and SVGs referenced in the HTML and CSS.
- `.github/copilot-instructions.md`: (this file) Project-specific AI agent guidance.

## Patterns & Conventions
- **Class Naming:** Uses double underscores for element modifiers (e.g., `highlight__img`, `header__img--wrapper`).
- **No JavaScript:** All interactivity is handled via HTML and CSS only. No custom JS files are present.
- **Responsive Design:** Layout uses flexbox and relative units for responsiveness.
- **FontAwesome:** Icons are loaded via CDN in the HTML head.
- **Color Palette:** Primary color is `#7700ff` (purple), with accent colors like `#32cbea` (cyan) and gradients.
- **Button Styles:** Buttons use `.brwbks` class for primary actions.

## Developer Workflows
- **No build step:** Open `index.html` directly in a browser to view the site.
- **No tests or scripts:** There are no automated tests or build scripts.
- **Add new assets:** Place images/SVGs in the `assets/` directory and reference them with relative paths.
- **Styling:** All styles should be added to `styles.css`. Follow the existing class naming conventions.

## Integration & Extensibility
- **To add new sections:** Edit `index.html` and add corresponding styles in `styles.css`.
- **To add interactivity:** If JavaScript is needed, create a new `.js` file and link it in `index.html` (not currently present).
- **External dependencies:** Only FontAwesome (via CDN) is used for icons.

## Examples
- To add a new highlight card:
  1. Duplicate a `.highlight` div in the `#hilights` section of `index.html`.
  2. Add any new icons using FontAwesome classes.
  3. Style as needed in `styles.css`.

## References
- See `index.html` for structure and content.
- See `styles.css` for all styling rules and patterns.
- See `assets/` for all static images and SVGs.

---
For questions or major changes, update this file to keep AI agents and developers aligned.
