## 2026-03-31 - Keyboard Accessibility in Standalone Reveal.js Explainer IFrames
**Learning:** Embedded interactive HTML explainers in presentation slides often use non-semantic `<div>` elements for accordion cards and tab lists, omitting keyboard triggers and focus indicators.
**Action:** Always add `role="button"`, `tabindex="0"`, `aria-expanded`, and `onkeydown` (Enter/Space) handlers to interactive divs, along with `:focus-visible` CSS rules for clear focus outlines.
