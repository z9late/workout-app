# Palette's Journal - GRIND

## 2025-05-14 - Tab Accessibility & Keyboard Navigation
**Learning:** Standard HTML/JS tab implementations often neglect screen reader users and keyboard-only users. Implementing the WAI-ARIA Tabs pattern (role="tablist", role="tab", role="tabpanel") with a roving tabindex and arrow key navigation significantly improves the "feel" and accessibility of the interface.
**Action:** Always use ARIA roles and manage `aria-selected` and `tabindex` when building tabbed interfaces.
