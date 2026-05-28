# Palette's Journal - GRIND

## 2025-05-15 - Improving Tab Accessibility
**Learning:** The initial tab implementation was purely visual and lacked keyboard navigation support and ARIA roles. Implementing the roving tabindex pattern and proper ARIA roles significantly improves the experience for screen reader and keyboard-only users.
**Action:** Always use WAI-ARIA patterns for tabs (role="tablist", "tab", "tabpanel") and ensure keyboard navigation (arrows, home, end) is supported.
