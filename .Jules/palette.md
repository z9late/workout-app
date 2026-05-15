## 2025-05-14 - Accessible Workout Tabs
**Learning:** Implementing WAI-ARIA tab patterns significantly improves accessibility for screen readers and keyboard-only users. Using the 'single tab stop' pattern with arrow key navigation is the standard for tabbed interfaces.
**Action:** Always use `role="tablist"`, `role="tab"`, and `role="tabpanel"` for tabbed interfaces. Implement arrow key navigation and manage `tabindex` and `aria-selected` state.
