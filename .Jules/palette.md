## 2026-06-03 - Accessible Tab Navigation Pattern
**Learning:** Implementing the WAI-ARIA Tab pattern with a "roving tabindex" is essential for keyboard accessibility in static interfaces. Combining it with Tailwind's `focus-visible` utility ensures high-contrast focus indicators for keyboard users without affecting the visual experience for mouse users.
**Action:** Always use `role="tablist"`, `role="tab"`, and `role="tabpanel"` for tabbed interfaces. Implement Arrow key navigation and manage `tabindex` dynamically to provide a single tab stop for the collection.
