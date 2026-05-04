# lisaesterhuizen0-wq.github.io

Portfolio site for Lisa Myburgh, AI Operations.

Single-page static HTML/CSS, no build step, no JavaScript. Deployed via GitHub Pages from the `main` branch root, served at the root URL: <https://lisaesterhuizen0-wq.github.io/>.

## Structure

```
.
├── index.html   # the page
├── style.css    # design system (jade / cream / jasper)
└── README.md
```

## Design system

Reused across the EA Toolkit, the Competitive Org Map demo, and any future sanitised case studies.

- **Palette**: cream `#F5F2EA`, jade `#373C2B`, jasper accent `#DAFF00`, amber highlight `#d4892b`
- **Type**: `Instrument Serif` (italic for emphasis), `Inter Tight` body, `JetBrains Mono` for eyebrow/labels
- **Tone**: editorial, quiet confidence, generous whitespace. Avoid gradients, neon, glassmorphism, and AI cliché iconography.

## Updating

Edit `index.html` directly. No build step. Push to `main`. GitHub Pages picks it up.

When a new case study is ready (Harcourts, Cross-Portal Auto-Fill), flip its disabled "in progress" pill on the project card to a real link. The disabled state is intentional, placeholder controls should look inert, never live.
