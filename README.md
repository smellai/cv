# stefania.mellai.it — CV

Personal CV website for **Stefania Mellai**, Expert Engineer · Front End.

## ✦ About

An HTML/CSS curriculum vitae. No frameworks, no build step, no dependencies. The design prioritises:

- **Readability**
- **Accessibility** — semantic HTML, sufficient colour contrast
- **Responsiveness** — adapts from wide desktop down to small mobile screens
- **Print-friendliness** — a dedicated `@media print` stylesheet for the detailed version

## 📁 Structure

```
.
├── index.html            # Web version
├── en/
│   └── index.html        # Detail version / Print version
└── cv_mellai_english.pdf # Downloadable PDF snapshot
```

## 🖨 Print / PDF

Open `en/index.html` in a browser and use **File → Print** (or `Cmd/Ctrl + P`).  
The print stylesheet hides the navigation buttons and surfaces the `stefania.mellai.it` URL inline so the printed version is self-contained.

Recommended print settings:
- Paper: A4
- Margins: Default
- Background graphics: off (not needed)


## 📝 Updating

The CV is intentionally low-tech so it's easy to maintain:

1. Edit `index.html` directly
2. Update the `<footer>` date at the bottom
3. Export a fresh PDF snapshot and replace `cv_mellai_english.pdf`

---

*Last updated: April 2026*