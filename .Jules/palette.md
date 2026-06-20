# 🎨 Palette Journal: UX & Accessibility Learnings

This journal documents critical UX and accessibility insights discovered during the development of GRIND.

## 2026-02-11 - Accessible Tabbed Interfaces
**Learning:** Implementing WAI-ARIA tabs (role="tablist", role="tab", role="tabpanel") with a roving tabindex pattern significantly improves the experience for keyboard and screen reader users by providing clear context and reducing the number of tab stops.
**Action:** Always include keyboard listeners for arrow key navigation (Home, End, Left, Right) when using the tab pattern to follow user expectations for "single tab stop" collections.
