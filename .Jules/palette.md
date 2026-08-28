## 2026-08-28 - Focus Indicators and Landmark ARIA in Embedded Explainer IFrames
**Learning:** Interactive web explainers loaded inside Reveal.js iframe slides require explicit `:focus-visible` styling with custom theme variables (e.g. `var(--gold)`) on links (`.toc a`) and `<details>` summary elements. Without explicit focus rings, keyboard tab focus becomes invisible on dark background slides.
**Action:** Always add `:focus-visible` styles on interactive targets in standalone explainer pages and set `aria-label` on navigation landmarks (`<nav>`).
