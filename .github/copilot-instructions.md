# Copilot Instructions for Deonify Website Project

## Project Overview
This is a static HTML/CSS website for "Deonify", an online electronics store. The site consists of multiple pages: home (index.html), shop, about, and contact.

## Architecture
- **Static multi-page site**: No JavaScript or frameworks, pure HTML and CSS.
- **Shared styling**: All pages link to `style.css` for consistent appearance.
- **Navigation**: Header navbar with links to all pages.
- **Content structure**: Hero section on home, stats/info sections.

## Key Patterns
- **HTML structure**: Use semantic elements, include meta charset and viewport.
- **CSS classes**: 
  - `.navbar` for header navigation
  - `.Home` for hero section (note: case-sensitive, differs from common `.home`)
  - `.container` and `.stats` for content layout
  - Stats pattern: `<div class="stats"><p class="stats_value">value</p><p class="stats_label">label</p><p class="about_our elektroniks">description</p></div>`
- **Images**: Store in `img/` folder, reference with relative paths.
- **Language**: Content in Albanian (lang="sq" or "en" depending on page).

## Development Workflow
- Edit HTML files directly in VS Code.
- Update `style.css` for styling changes.
- No build tools required; open index.html in browser to preview.
- For new pages, copy the navbar structure from `index.html` and adapt content.

## Conventions
- Page titles: "Deonify" for home, "About Us", "Shop", "Contact" for others.
- Color scheme: Dark background (#0f172a), blue accents (#38bdf8).
- Font: Arial, sans-serif.

## Key Files
- `index.html`: Exemplifies complete page structure with navbar, hero, and stats sections.
- `style.css`: Contains all styling rules.
- `img/`: Directory for image assets.

Ensure new code follows the established patterns in `index.html` for consistency.