# Academic homepage

Static personal homepage published at https://jzhws.github.io/ using GitHub Pages (`main`, repository root).

## Local development

Run `python3 -m http.server 8000` from the repository root. No dependency installation or build step is required.

## Languages

Use the header's 中文 / EN button to switch languages. The selection is saved locally; `?lang=zh` and `?lang=en` provide shareable language links and override the saved preference.

- `index.html` contains the default English markup and `data-i18n` bindings.
- `i18n.js` contains English/Chinese interface copy and Chinese publication titles and summaries.
- `app.js` applies translations and renders publications. Canonical English titles, author names, and BibTeX remain available in either language; search matches English and Chinese titles.
- Institution marks are stored locally under `assets/`; see [their sources](assets/LOGO-SOURCES.md).
