## 2026-09-02 - Custom Clickable Div Cards Accessibility Pattern
**Learning:** Custom clickable `<div>` elements in embedded explainer widgets lack keyboard interaction, screen reader roles, and focus indicators by default.
**Action:** Always complement `onclick` on `<div>` cards with `tabindex="0"`, `role="button"`, `aria-expanded`, an `onkeydown` handler for Enter/Space, and `:focus-visible` CSS rules.
