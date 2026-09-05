## 2026-09-05 - Focus-Visible Indicators in Standalone Presentation Explainers
**Learning:** Standalone HTML explainer pages embedded in slide decks or loaded in iframes often lack default browser focus indicators or inherit low-contrast defaults that make keyboard navigation impossible to see against dark theme backgrounds.
**Action:** Always declare explicit `:focus-visible` styles with brand-matched outline colors (e.g. `outline: 2px solid var(--gold); outline-offset: 2px;`) on all interactive TOC links, summary disclosures, and buttons in dark-themed explainer components.
