## 2026-03-31 - Explicit `:focus-visible` Styles for Embedded HTML Explainers

**Learning:** Interactive HTML explainer pages embedded via iframe in Reveal.js presentation slides require explicit `:focus-visible` styles on interactive components like TOC links and collapsible `<summary>` elements. Default browser outlines are faint or invisible against deep slate presentation themes when navigated via keyboard.

**Action:** Always provide explicit `:focus-visible` outline and ring styles matching the document's theme palette (e.g., gold `outline: 2px solid var(--gold)`) for all interactive links, buttons, and summary tags in HTML explainers.
