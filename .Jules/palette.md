## 2026-03-30 - Focus Indicators and CSS Syntax Integrity in HTML Explainers
**Learning:** HTML explainer pages embedded in slides need explicit `:focus-visible` outlines on navigation links and summary components to maintain high contrast keyboard navigation in dark themes. Also, stray HTML tags inside `<style>` blocks silently break CSS selectors like `.type-badge`.
**Action:** Always check both screen-reader accessibility (`aria-label`) and explicit keyboard focus states (`:focus-visible`) when refining standalone HTML explainers, and audit `<style>` tags for syntax errors.
