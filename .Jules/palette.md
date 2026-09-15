## 2026-09-15 - Focus Ring Visibility in Dark-Themed Standalone Explainer Pages
**Learning:** Standalone interactive HTML explainers (embedded via iframe or loaded directly) often lack default focus outlines on custom styled navigation links and summary components when default browser focus styles blend into dark background themes.
**Action:** Always provide explicit `:focus-visible` styles using theme accent variables (e.g. `outline: 2px solid var(--gold)`) for interactive elements like `.toc a` and `summary` in dark-themed explainer pages.
