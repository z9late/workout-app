# Palette's Journal - GRIND

This journal tracks critical UX and accessibility learnings.

## 2026-02-12 - Initial Accessibility Audit
**Learning:** The workout-app uses a custom tab implementation that lacks ARIA roles and keyboard navigation (arrow keys), which is a common barrier for screen reader and keyboard-only users.
**Action:** Implement the WAI-ARIA Tab Panel pattern to ensure the core workout modules are fully accessible.

## 2026-02-12 - Accessible Tab Pattern with Roving Tabindex
**Learning:** Implementing the roving tabindex pattern for tabs requires synchronized management of 'tabindex', 'aria-selected', and the 'hidden' attribute to ensure both visual and screen-reader consistency. Automatic activation (clicking on focus) is efficient for simple tabbed interfaces.
**Action:** Use a centralized 'openTab' function to manage all state attributes and a 'keydown' listener on the 'tablist' to handle arrow navigation.
