# Palette's Journal - Critical UX/Accessibility Learnings

## 2026-03-05 - Fixing CSS Pollution and iframe focus-visible states
**Learning:** Malformed HTML/CSS injections (like a duplicate `<td>` tag inside a style block) can silently corrupt the CSS parser, breaking critical layout styles (such as `.type-badge` rendering) without throwing obvious developer console errors. Additionally, interactive explainers loaded inside presentation iframes (like Reveal.js background-iframes) frequently lack visible keyboard focus indicators, making keyboard/screen-reader navigation impossible.
**Action:** Always validate CSS definitions for syntax contamination. Implement explicit `:focus-visible` outline rings for `a`, `summary`, and `button` in embedded iframe applications to preserve keyboard accessibility boundaries. Set `aria-hidden="true"` on decorative inline SVGs to avoid reading noise.
