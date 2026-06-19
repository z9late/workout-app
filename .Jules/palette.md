## 2026-06-19 - Accessible Tab Component Pattern
**Learning:** In a static HTML environment using Tailwind CSS, implementing the WAI-ARIA Tabs pattern (roving tabindex) requires manual synchronization of `aria-selected`, `hidden`, and `tabindex` attributes. Without this, keyboard users and screen reader users lose context during navigation.
**Action:** Use a centralized JavaScript function to manage ARIA state for all tab components, ensuring that only the active tab is in the natural tab order (`tabindex="0"`).

## 2026-06-19 - High-Contrast Focus Indicators
**Learning:** Dark-themed UIs (like Slate-950) require high-contrast focus rings for accessibility. Standard browser outlines are often insufficient or inconsistent across elements.
**Action:** Apply `focus-visible:ring-2 focus-visible:ring-red-500 outline-none` to all interactive elements, and use `rounded` and `px-1` for inline links to prevent the ring from being clipped.
