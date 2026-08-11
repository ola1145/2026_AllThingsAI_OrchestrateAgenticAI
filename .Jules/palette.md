# Palette Journal - Critical UX & Accessibility Learnings

## 2026-03-05 - Presentation Iframes & Dark Theme Keyboard Navigation
**Learning:** In slide presentations (e.g. Reveal.js) utilizing embedded web interactive explainers inside iframes, default browser focus outlines are often low-contrast, completely invisible, or fail to render cleanly due to custom styling. Custom HTML-div components that mimic buttons are completely inaccessible to screen reader and keyboard-only users without explicit accessibility semantics and key listeners.
**Action:** Always ensure that iframes and standalone presentation pages have explicit high-contrast `:focus-visible` styles matching the dark/light palette theme. Every custom interactive element (like collapsible div cards) must be declared with `tabindex="0"`, `role="button"`, and handle both click and Enter/Space keyboard events, updating `aria-expanded` attributes statefully.
