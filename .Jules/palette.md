## 2026-10-06 - Accessible Custom Card Buttons in Embedded Explainers
**Learning:** In standalone HTML/JS explainers loaded inside Reveal.js slides, custom clickable `<div>` components lack keyboard focus and screen reader semantics unless explicitly declared with `role="button"`, `tabindex="0"`, `aria-expanded`, and keydown event handlers (`Enter`/`Space`).
**Action:** When making custom cards or containers interactive, always bind keyboard listeners, manage `aria-expanded`, and ensure focus indicators are styled using `:focus-visible`.
