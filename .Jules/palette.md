## 2025-05-18 - Visible Focus Outlines in Explainer IFrames
**Learning:** Standalone interactive HTML explainers often strip or omit browser-default focus rings for custom summary/collapsible and navigation links, making keyboard navigation invisible.
**Action:** Ensure custom interactive elements (`summary`, `.toc a`) define explicit `:focus-visible` rules using the design system's theme variables (`var(--gold)`).
