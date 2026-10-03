## 2026-03-30 - Focus Indicators on Embedded Explainer HTML
**Learning:** HTML explainer pages embedded in slide decks often reset or omit focus states on links and summaries, rendering keyboard navigation invisible when embedded in iframes or dark-themed presentation slides.
**Action:** Always provide explicit `:focus-visible` styling matching the design tokens (`var(--gold)`) for `.toc a` and `summary` elements in stand-alone explainer pages.
