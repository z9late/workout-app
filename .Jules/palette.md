# Palette's Journal - Critical UX & Accessibility Learnings

## 2026-06-30 - Standardizing Accessible Tabs
**Learning:** Implementing the WAI-ARIA Tabs pattern requires synchronization of three states: `aria-selected` (tabs), `tabindex` (roving focus), and `hidden` (panels). Using only CSS classes like `.active` for visibility is insufficient for screen readers and keyboard-only users.
**Action:** Always implement a manual `keydown` listener for Arrow keys, Home, and End when using the WAI-ARIA tab pattern to provide a standard, expected user experience.
