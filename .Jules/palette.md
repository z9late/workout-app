# Palette's Journal - Critical UX/Accessibility Learnings

## 2026-03-01 - Comprehensive ARIA Tab Patterns
**Learning:** Implementing a full WAI-ARIA tab pattern requires synchronized management of `aria-selected`, `tabindex`, and `hidden` attributes across both tab buttons and panels. Roving tabindex (handling ArrowLeft/Right/Home/End) is essential for a native-feeling keyboard experience in collection components.
**Action:** Always use a centralized update function (like `openTab`) to keep accessibility state in sync with visual state, and ensure the first tab is explicitly set to `tabindex="0"` in static HTML.
