## 2025-02-19 - Focus-Visible Outlines for Standalone HTML Explainers
**Learning:** Standalone HTML explainer pages in `explainers/` embedded in presentation slides can lose focus visibility on custom interactive elements (`.toc a`, `details summary`) during keyboard navigation if explicit `:focus-visible` CSS rules are missing.
**Action:** Always include explicit `:focus-visible` rules with themed outline rings (`var(--gold)`) on interactive TOC links and collapsible summaries in standalone explainer pages.
