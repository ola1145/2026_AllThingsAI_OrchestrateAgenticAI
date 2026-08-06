# Palette's Journal - Critical UX/a11y Learnings Only

## 2026-08-06 - Interactive Explainer Keyboard Navigation & Focus Visible States
**Learning:** Embeds or interactive explainers in presentation decks are loaded in `<iframe>` tags or viewed standalone. If interactive cards (like div-based details cards) or custom tabs lack proper focus outline and keyboard accessibility (like custom `tabindex="0"`, `role="button"`, and handling `Enter`/`Space`), they become completely inaccessible to keyboard-only users. Explicit `:focus-visible` outlines ensure keyboard-only users can navigate the deck seamlessly.
**Action:** Always add `tabindex="0"`, custom keydown/keypress handlers, appropriate ARIA roles/states (like `aria-expanded` and `role="button"`), and prominent focus outlines via `:focus-visible` to custom interactive div-based elements.
