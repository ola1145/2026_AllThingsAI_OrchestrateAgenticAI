## 2025-05-18 - Embedded Explainer Keyboard Focus Indicators
**Learning:** Standalone HTML explainer pages embedded in slides/iframes often lack explicit `:focus-visible` styling on links (`.toc a`) and interactive summary elements (`details summary`), leaving keyboard users without visual focus context.
**Action:** Always inspect embedded explainer pages for missing `:focus-visible` outlines on navigation links and summary components and add explicit high-contrast focus rings matching the theme palette.
