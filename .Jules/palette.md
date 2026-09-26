## 2026-09-26 - Keyboard Accessibility for Dynamic JS Card Components
**Learning:** Custom interactive div-based cards created dynamically via JS `innerHTML` in standalone explainer pages often lack native keyboard focus and activation states, making them invisible and inaccessible to keyboard and screen reader users.
**Action:** When creating or editing clickable cards/divs in explainer components, always add `tabindex="0"`, `role="button"`, `aria-expanded`, keydown event listener for Enter/Space, and `:focus-visible` styles.
