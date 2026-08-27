## 2026-03-31 - Keyboard Accessibility & ARIA States on Interactive Explainer Cards
**Learning:** Custom interactive div elements in standalone explainer pages (like `.issue-card`) lack keyboard accessibility and screen reader feedback unless explicitly assigned `role="button"`, `tabindex="0"`, `aria-expanded`, and an `onkeydown` handler for Enter/Space.
**Action:** Always include keyboard listeners, focus-visible outline indicators, and dynamic `aria-expanded` attributes on custom clickable card components.
