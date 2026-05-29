# Palette's Journal - UX & Accessibility Learnings

## 2025-05-14 - ARIA Tabs Pattern and Roving Tabindex
**Learning:** Implementing the WAI-ARIA Tabs pattern significantly improves accessibility but requires careful synchronization between the `aria-selected`, `tabindex` attributes, and visual focus. A "single tab stop" (roving tabindex) pattern is preferred for tab collections, where only the active tab is in the tab order (`tabindex="0"`) and inactive tabs are removed (`tabindex="-1"`).
**Action:** Always include a `keydown` listener for Arrow keys, Home, and End when implementing tabs to match user expectations for keyboard navigation.

## 2025-05-14 - Keyboard Visibility in Dark Themes
**Learning:** In dark-themed UIs (like Slate-950), default browser focus outlines can be hard to see or inconsistent.
**Action:** Use high-contrast focus indicators like Tailwind's `focus-visible:ring-2 focus-visible:ring-red-500` to ensure keyboard users can easily track their position. Combined with `outline-none` to suppress the default browser outline for a cleaner look.
