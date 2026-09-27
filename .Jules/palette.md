# Palette's Journal - Critical Learnings

## 2025-05-15 - Focus-visible Indicators in Embedded Reveal.js Explainer IFrames
**Learning:** Embedded interactive HTML explainers often reset standard browser focus styles with CSS resets (like `outline: none`). When loaded in iframe slides within Reveal.js, keyboard users lose track of focus on navigation links (`.toc a`) and interactive summary headers (`details summary`).
**Action:** Always provide explicit `:focus-visible` styles with sufficient outline thickness and high contrast (using local CSS variables like `var(--gold)` or standard contrast outlines) on custom styled links and `<summary>` elements in explainer components.
