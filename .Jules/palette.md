## 2026-05-15 - ARIA Tabs Accessibility Audit
**Learning:** Standardizing tabbed interfaces using the WAI-ARIA Tabs pattern (role="tablist", role="tab", role="tabpanel") with a roving tabindex significantly improves the "invisible UX" for keyboard and screen reader users in static HTML dashboards.
**Action:** When implementing collection-based navigation (tabs, lists), ensure the active element has tabindex="0" and aria-selected="true", while inactive elements use tabindex="-1", and always provide manual keyboard event listeners for Arrows, Home, and End keys.
