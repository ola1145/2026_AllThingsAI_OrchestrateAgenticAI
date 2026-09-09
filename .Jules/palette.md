## 2026-03-31 - Explicit focus-visible indicators on HTML explainers embedded in Reveal.js

**Learning:** Standalone HTML explainer pages embedded via iframe in Reveal.js slides strip default focus rings in some browsers or render them with low contrast against custom dark themes (`#0c1220`), rendering keyboard navigation invisible to users tabbing through presentation slides.
**Action:** Always add explicit `:focus-visible` styles on interactive navigation links and collapsible summaries using CSS theme tokens (e.g. `outline: 2px solid var(--gold)`) in iframe-embedded explainers.
