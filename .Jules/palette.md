## 2026-03-08 - Embedded HTML Explainers Focus States
**Learning:** Interactive standalone HTML explainer pages embedded in slide decks often lack default browser focus indicators or rely on subtle default focus rings that blend into dark themes.
**Action:** Always define explicit `:focus-visible` styles with theme high-contrast colors (`var(--gold)`) and explicit `outline-offset` on interactive links (`.toc a`) and collapsible summary elements (`summary`) in dark-themed explainer pages.
