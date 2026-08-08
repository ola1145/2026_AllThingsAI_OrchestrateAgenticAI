# Palette's UX Journal

## 2026-02-14 - Iframe Embedded Slides and Focus Ring Visibility
**Learning:** When interactive web explainers are embedded inside Presentation slides (Reveal.js) using iframes, standard browser focus indicators fail to be highly visible, resulting in invisible focus when navigating via keyboard. Furthermore, custom clickable div components (such as interactive cards and accordions in the RFP explainer) are completely inaccessible to screen readers and keyboard users as they lack tabindex, role, aria-expanded, and keyboard event triggers.
**Action:** Always pair custom click events with keydown handlers (for Enter/Space), appropriate ARIA role/state attributes, and explicit, high-contrast CSS `:focus-visible` outline definitions to ensure keyboard navigability across iframes.
