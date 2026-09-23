## 2026-03-30 - Interactive Explainers Focus States and Syntactic HTML Injection
**Learning:** Standalone HTML explainers loaded into presentation decks often omit `:focus-visible` states on custom TOC links and collapsibles, rendering them non-accessible to keyboard users. Additionally, stray inline HTML inside `<style>` blocks silent-fails or corrupts CSS specificity without throw errors.
**Action:** When auditing embedded HTML explainers, check for `:focus-visible` rings matching theme colors (e.g. `--gold`) and validate `<style>` blocks for syntax errors.
