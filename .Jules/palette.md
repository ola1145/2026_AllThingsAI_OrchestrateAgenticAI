## 2025-05-18 - Keyboard Focus Indicators in Standalone Explainer HTML Files
**Learning:** Standalone interactive explainer pages embedded in slides often reset default focus styling or use custom buttons/links without specifying explicit `:focus-visible` outlines, rendering keyboard navigation invisible.
**Action:** When inspecting explainer HTML pages, ensure all interactive elements (`.toc a`, `details summary`, buttons) have high-contrast `:focus-visible` outline styles defined.
