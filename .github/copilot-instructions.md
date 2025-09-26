# Copilot Instructions for AI Coding Agents

## Project Overview
This is a static HTML project for a Russian-language clothing and equipment store. The main file is `index.html`, styled with Tailwind CSS via CDN. Images are stored in the `img/` directory. There is no build system, backend, or dynamic scripting present.

## Key Files and Structure
- `index.html`: Main entry point. Contains all markup and references Tailwind CSS.
- `img/`: Contains product and UI images. Use relative paths for referencing images in HTML.

## Patterns and Conventions
- Use Tailwind CSS utility classes for all styling. Do not add custom CSS files unless requested.
- All navigation and UI elements are static. If adding interactivity, use inline JavaScript in `index.html`.
- Russian is the default language for content and UI labels.
- Maintain semantic HTML structure for accessibility and SEO.

## Developer Workflows
- No build or test commands are required. Open `index.html` directly in a browser to preview changes.
- For image updates, add new files to `img/` and reference them with correct relative paths.
- If adding new pages, create additional `.html` files in the root directory and link them from `index.html`.

## Integration Points
- Tailwind CSS is loaded via CDN. No local installation or configuration is needed.
- No external JavaScript libraries are used by default.

## Examples
- To add a new product image: Place the image in `img/`, then add an `<img src="img/your-image.png" alt="...">` tag in `index.html`.
- To add a new navigation link: Edit the `<nav>` section in `index.html` and use Tailwind classes for styling.

## Special Notes
- Do not introduce frameworks, build tools, or package managers unless explicitly requested.
- Keep all code changes minimal and focused on static site improvements unless the user requests dynamic features.

---
_Last updated: September 2025_
