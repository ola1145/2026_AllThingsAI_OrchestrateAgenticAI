# Palette's Journal

## 2026-10-05 - Interactive Explainer Accessibility in Presentation IFrames
**Learning:** Embedded HTML interactive explainers used inside Reveal.js presentation slides often use custom `div` elements for expand/collapse cards and custom tab triggers without `tabindex="0"`, `role="button"`, `aria-expanded`, or keyboard event listeners (`Enter`/`Space`), rendering them inaccessible to keyboard and screen-reader users during live presentations.
**Action:** When building or updating interactive explainer cards and tabs, ensure `tabindex="0"`, `role="button"`, `role="tablist"`, `role="tab"`, `aria-expanded`, `aria-selected`, and `:focus-visible` styling with `onkeydown` triggers are explicitly implemented.
