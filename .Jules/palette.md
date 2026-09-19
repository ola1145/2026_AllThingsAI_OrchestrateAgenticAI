## 2026-03-30 - Focus-visible styles for Reveal.js embedded HTML explainers

**Learning:** Interactive explainer HTML pages embedded inside Reveal.js slide decks as background iframes require explicit `:focus-visible` styles on custom interactive elements (links, summaries, buttons). Without explicit focus-visible indicators, keyboard users navigating through slides and iframe content lose visual focus context.

**Action:** Whenever creating or editing standalone HTML explainer components, ensure `:focus-visible` rules are defined with high contrast outline rings (`outline: 2px solid var(--gold)`) on all navigable elements (`<a>`, `<summary>`, `<button>`).
