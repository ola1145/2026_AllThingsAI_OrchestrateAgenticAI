## 2026-03-31 - Focus Visible Styles on Embedded HTML Explainer Pages
**Learning:** Interactive explainer HTML pages hosted inside Reveal.js slide iframes lack distinct default focus outlines in custom themes unless explicitly styled with `:focus-visible`.
**Action:** Always add theme-matched `:focus-visible` outlines to `.toc a` navigation links and `details summary` elements in standalone explainer pages.
