# Copilot Instructions for Zool-gico

## Project Overview
This is a personal portfolio website for Jociley, built with vanilla HTML, CSS, and JavaScript. The site showcases projects, a personal profile, and contact information. The codebase is simple and does not use frameworks or build tools.

## Key Files & Structure
- `index.html`: Main HTML file. Contains all sections (Início, Sobre, Projetos, Contato) and links to assets and styles.
- `stile.css`: Main stylesheet. Uses CSS variables for theming and accessibility resets. Custom classes for layout and components.
- `csript.js`: Handles dynamic behaviors (footer year, scroll-to-top button, contact form simulation).
- `assets/`, `img/`, and image files: Used for profile and project images.

## JavaScript Patterns
- All DOM queries use `getElementById` and expect specific IDs (e.g., `toTop`, `form-contato`, `msg-status`).
- The contact form is simulated: on submit, it shows a message and resets the form after a delay.
- The scroll-to-top button appears after scrolling 400px and uses smooth scroll.
- Footer year is set dynamically using JS.

## CSS Patterns
- Uses CSS custom properties (variables) for theme colors and spacing.
- Accessibility: skip-link for keyboard navigation, focus styles, and reset styles.
- Responsive layout via `.container` and section classes.

## Conventions & Practices
- All code and comments are in Brazilian Portuguese.
- No build process: edit files directly and refresh the browser to see changes.
- No external dependencies or package managers.
- Image and asset references are relative to the project root.

## Extending the Project
- Add new sections by editing `index.html` and updating navigation.
- Add new styles in `stile.css` using the existing variable system.
- Add new JS features in `csript.js` following the pattern of DOM selection and event listeners.

## Example: Adding a New Project
1. Add a new `<section>` in `index.html` under the "Projetos" area.
2. Add any new images to `assets/img/` and reference them with a relative path.
3. Style the new section in `stile.css`.

## Known Issues
- The JavaScript file has a typo in its name (`csript.js` instead of `script.js`).
- Some DOM elements referenced in JS may not exist in the HTML (e.g., `toTop` button).

## Contact
For questions, contact Jociley (see profile section in `index.html`).
