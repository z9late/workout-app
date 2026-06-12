## 2026-06-12 - [Workout Modules Accessibility Audit]
**Learning:** The workout tab system lacked ARIA roles and keyboard navigation, preventing users with assistive technologies from effectively switching between workout modules. Implementing the roving tabindex pattern with arrow key support significantly improves the UX for power users and meets W3C accessibility standards.
**Action:** Always implement role="tablist", role="tab", and role="tabpanel" for tabbed interfaces, and ensure the active tab is focusable while others are removed from the tab order (tabindex="-1").
