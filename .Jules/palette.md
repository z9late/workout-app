## 2025-05-15 - [Tab Accessibility]
**Learning:** Interactive elements like tabs require WAI-ARIA roles (tablist, tab, tabpanel) and keyboard navigation (arrow keys) to be fully accessible to screen readers and keyboard users.
**Action:** Always implement `role="tablist"`, `role="tab"`, and `role="tabpanel"` with appropriate `aria-selected` and `aria-controls` attributes when creating tabbed interfaces.
