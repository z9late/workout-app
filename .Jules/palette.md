# Palette's Journal - GRIND

## 2025-05-14 - Tab Interface Accessibility
**Learning:** Static HTML implementations often overlook the WAI-ARIA Authoring Practices for complex widgets like tabs. Simply toggling a 'hidden' class is insufficient for screen readers and keyboard-only users.
**Action:** Always implement the 'roving tabindex' pattern and appropriate ARIA roles (`tablist`, `tab`, `tabpanel`) for tabbed interfaces to ensure they are fully accessible and feel "native" to power users.
