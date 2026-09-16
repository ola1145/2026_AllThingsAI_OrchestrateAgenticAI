## 2025-05-18 - Focus Indicators on Embedded Explainer Summaries and Navigation Links
**Learning:** Interactive `<summary>` collapsible triggers and Table of Contents links inside standalone dark-themed HTML explainers often lack explicit `:focus-visible` ring styling, rendering keyboard focus invisible against custom dark backgrounds.
**Action:** Always add explicit `:focus-visible` outline styles with appropriate `outline-offset` to interactive controls (`.toc a`, `details summary`) matching the theme primary or highlight color (`var(--gold)`).
