# Palette's Journal — Critical UX/Accessibility Learnings

This journal tracks critical UX and accessibility insights discovered during the enhancement process.

## 2026-08-11 - [Focus Indicators and Keyboard Navigation in Interactive Slide Embeds]
**Learning:** Interactive explainers embedded inside Reveal.js presentation slides as iframe elements require explicit, high-contrast `:focus-visible` styles on navigable elements (such as links, summary elements, and button components). When embedded, default browser outline/focus rings can become invisible or inconsistent. Furthermore, custom div-based interactive elements (like accordions or tab-like headers) must have appropriate keyboard event handlers (`Enter` and `Space`), proper ARIA attributes (`role="button"`, `aria-expanded`), and explicit `tabindex` to ensure fully accessible keyboard-navigable experiences.
**Action:** Always verify keyboard navigation inside iframes, ensure focus indicators are prominent and high-contrast, and check that custom clickables are backed by native keyboard events and ARIA attributes.
