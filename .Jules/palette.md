## 2026-09-04 - Standalone Explainer Keyboard Navigation
**Learning:** Interactive HTML explainers embedded within slide decks or rendered standalone often lack explicit `:focus-visible` styles on custom summary elements and navigation links, making keyboard navigation invisible.
**Action:** Always add explicit `:focus-visible` outline styles with theme-matching accent colors (e.g. `var(--gold)`) to all interactive elements (`.toc a`, `summary`, `button`) in standalone explainer pages.
