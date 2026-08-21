## 2026-03-30 - Focus-Visible States in Embedded Presentation Explainers
**Learning:** Standalone HTML explainers embedded as iframes within Reveal.js presentations lack browser default focus ring visibility against dark background themes, degrading keyboard navigation accessibility.
**Action:** Always define explicit `:focus-visible` outline styles with high-contrast theme variables (e.g. `var(--gold)`) on interactive links and summary collapsible triggers.
