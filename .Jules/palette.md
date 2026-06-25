## 2026-02-11 - Accessible Tabbed Interface Pattern
**Learning:** Standard tabbed interfaces often lack proper keyboard navigation (roving tabindex) and screen reader context (ARIA roles), making them difficult for non-mouse users to navigate.
**Action:** Always implement `role="tablist"`, `role="tab"`, and `role="tabpanel"` with appropriate `aria-selected` and `tabindex` management. Use Arrow keys, Home, and End for continuous keyboard navigation.
