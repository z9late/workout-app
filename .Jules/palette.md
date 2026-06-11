## 2026-06-11 - Accessible Roving Tabindex Pattern
**Learning:** Implementing a roving tabindex for tabbed interfaces significantly improves the experience for keyboard and screen reader users by creating a single tab stop for the collection and allowing specialized navigation (arrows, Home, End).
**Action:** Use `role="tablist"`, `role="tab"`, and `role="tabpanel"` with a centralized `keydown` listener to manage focus and ARIA states (`aria-selected`, `tabindex`) whenever implementing collection-based navigation.
