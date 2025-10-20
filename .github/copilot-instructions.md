# Copilot Instructions for AI Coding Agents

## Project Overview
This project is a simple static website using Bootstrap 5.3.8. It is structured for rapid prototyping and learning Bootstrap features. There is no build system, backend, or advanced tooling—just HTML and Bootstrap assets.

## Key Files and Structure
- `index.html`: Main entry point. All custom HTML and Bootstrap usage is here.
- `bootstrap-5.3.8-dist/`: Contains all Bootstrap CSS and JS files. No CDN is used; all assets are local.
  - `css/`: Bootstrap CSS files (minified and unminified, RTL variants).
  - `js/`: Bootstrap JS files (bundle, ESM, minified, etc.).

## Development Workflow
- **No build or test commands**: Edit `index.html` directly and refresh in the browser to see changes.
- **No package manager**: All dependencies are included locally in `bootstrap-5.3.8-dist/`.
- **No custom scripts or automation**: All logic is in HTML and Bootstrap usage.

## Project-Specific Conventions
- Always reference Bootstrap assets using relative paths (e.g., `bootstrap-5.3.8-dist/css/bootstrap.min.css`).
- Do not use external CDNs for Bootstrap; rely on the local `bootstrap-5.3.8-dist/` directory.
- Keep all custom HTML in `index.html`. If more pages are added, follow the same pattern.
- No custom JavaScript unless explicitly added to `index.html`.

## Examples
**Linking Bootstrap CSS:**
```html
<link rel="stylesheet" href="bootstrap-5.3.8-dist/css/bootstrap.min.css">
```
**Linking Bootstrap JS Bundle:**
```html
<script src="bootstrap-5.3.8-dist/js/bootstrap.bundle.min.js"></script>
```

## Integration Points
- No backend or API integration.
- No third-party JS libraries by default.

## Summary
This is a static HTML+Bootstrap project. Focus on clear, maintainable HTML and correct Bootstrap usage. All assets are local. No build, test, or deployment automation is present.
