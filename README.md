# ButterflyPoet Engineering Portfolio

A static, bilingual engineering portfolio starter. No build tools required.

## Deploy to GitHub Pages

1. Unzip this package.
2. Upload `index.html`, `assets/`, `lang/`, and this `README.md` into the **root** of `ButterflyPoet/ButterflyPoet.github.io` on the `main` branch.
3. Replace the existing `index.html` and `README.md` when prompted.
4. Keep Settings > Pages > Deploy from a branch > main > /(root).
5. Visit https://butterflypoet.github.io/ after deployment.

## Edit content

- `lang/zh.json` and `lang/en.json`: visible Chinese and English text.
- `assets/js/data.js`: projects, categories, technical notes, timeline, skills.
- `assets/css/style.css`: theme colors and layouts.
- `index.html`: page structure and navigation.

All initial projects and timeline items are explicitly labeled placeholders. Replace them with verified information. The skill tags are examples, not claims of expertise.

Project detail buttons currently open a modal. Add verified project links to each item in `data.js` as `{label:'Repository',url:'https://...'}` when available.

## Notes

The site uses Fetch to load language files, so use a local HTTP server for testing, such as `python -m http.server 8000`. Opening `index.html` directly as `file://` can block translation files.

This implementation is original and draws on common static portfolio architecture patterns. The visual direction is inspired by the public Lain-Ego portfolio; no original author images or source files have been copied. Reference: https://github.com/Lain-Ego0/Lain-Ego0.github.io
