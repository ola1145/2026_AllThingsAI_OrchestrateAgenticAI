## 2026-03-04 - Focus Rings in Dark-Themed Standalone HTML Explainers
**Learning:** Standalone HTML explainers embedded in slides using custom dark themes (like blueprint dark slate) often lack high-contrast focus ring styles on interactive element states (`:focus-visible`). Standard browser focus outlines can blend into dark backgrounds or get clipped by container borders.
**Action:** Always provide explicit `:focus-visible` outline styles (`outline: 2px solid var(--gold); outline-offset: 2px;`) using theme tokens for TOC navigation links and collapsible summary headers.
