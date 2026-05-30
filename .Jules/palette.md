## 2026-05-30 - Accessible Tabbed Interface Pattern
**Learning:** Implementing the roving tabindex pattern along with WAI-ARIA roles (tablist, tab, tabpanel) significantly improves the accessibility and keyboard navigability of static tab components.
**Action:** Use role="tablist", role="tab", and role="tabpanel" for all tabbed interfaces. Manage tabindex (0 for active, -1 for inactive) and aria-selected in the activation function. Add a keydown listener for ArrowLeft, ArrowRight, Home, and End keys to support standard keyboard interaction patterns.
