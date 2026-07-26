# Palette Journal

## 2026-07-26 - Keyboard navigation & ARIA roles on dynamically-generated iframe content
**Learning:** Embedded web explainers or iframes inside Reveal.js presentations often rely on simplified HTML (like `div` blocks with `onclick` actions for custom components) which entirely locks out screen readers and keyboard-only navigators. Dynamic interactive elements MUST have explicit ARIA button roles, tab index, and keydown handlers so they are keyboard navigable and readable.
**Action:** When auditing presentations or embedded interactives, check if any `div` has `onclick`. If so, immediately add `role="button"`, `tabindex="0"`, `aria-expanded` (if collapsible), and an inline or attached keydown handler for `Enter` or `Space` key triggers, as well as focus-visible outline states.
