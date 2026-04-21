# Konstantin Aksenov — CV

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://kosmaster87.github.io)
[![EN](https://img.shields.io/badge/Language-EN-blue)](https://kosmaster87.github.io?lang=en)
[![DE](https://img.shields.io/badge/Language-DE-grey)](https://kosmaster87.github.io?lang=de)

Personal CV page hosted on GitHub Pages.
Available in English and German — language is auto-detected from the browser, saved per session, and can be forced via URL parameter.

## Live

| URL                                                                    | Language      |
| ---------------------------------------------------------------------- | ------------- |
| [kosmaster87.github.io](https://kosmaster87.github.io)                 | Auto-detected |
| [kosmaster87.github.io?lang=en](https://kosmaster87.github.io?lang=en) | English       |
| [kosmaster87.github.io?lang=de](https://kosmaster87.github.io?lang=de) | Deutsch       |

## Content

- Profile summary
- Technical skills (Frontend, Backend, Infrastructure & Tools)
- Professional experience
- Selected projects with live links
- Education
- Languages
- Contact

## Language Switching

The page uses a lightweight, framework-free i18n system:

1. **URL parameter** `?lang=de` or `?lang=en` — takes highest priority
2. **localStorage** — restores the last manually selected language
3. **Browser language** — used as the initial default if nothing else is set

## Tech

- Plain HTML, CSS, and vanilla JavaScript — no build step, no framework
- Google Fonts: IBM Plex Serif + Space Grotesk
- Responsive layout (mobile, tablet, desktop)
- Print-optimized CSS

## Project Structure

```
KosMaster87.github.io/
├── index.html    # CV page with embedded i18n
├── style.css     # All styles including responsive and print rules
├── README.md     # This file
└── assets/
    └── favicon.ico
```

## Run Locally

```bash
git clone https://github.com/KosMaster87/KosMaster87.github.io.git
cd KosMaster87.github.io
npx serve .
# or
python -m http.server 8000
```

Then open `http://localhost:8000`.

## License

MIT — see [LICENSE](LICENSE).

---

© 2026 Konstantin Aksenov
