## 2025-05-14 - Accessible Tab Pattern with Roving Tabindex
**Learning:** The initial tab implementation lacked ARIA roles and keyboard support beyond basic clicking. Implementing the roving tabindex pattern (where only the active tab is focusable and arrow keys move focus/selection) significantly improves accessibility for keyboard and screen reader users in static HTML/Tailwind environments.
**Action:** Always implement `role="tablist"`, `role="tab"`, and `role="tabpanel"` for tabbed interfaces, and use a centralized keyboard event listener to handle navigation for consistency.
