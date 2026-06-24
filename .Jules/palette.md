## 2026-06-24 - Accessible Tab Pattern with Roving Tabindex
**Learning:** Implementing ARIA tabs requires synchronizing 'aria-selected', 'tabindex', and the 'hidden' attribute across buttons and panels to ensure a consistent experience for both screen readers and keyboard users.
**Action:** Use a unified 'openTab' function to manage all state attributes simultaneously and implement a 'keydown' listener on the 'tablist' to support standard arrow key navigation.

## 2026-06-24 - High-Contrast Focus Indicators in Dark Themes
**Learning:** For dark-themed UIs (e.g., slate-950), using 'focus-visible' with a bright ring (e.g., red-500) and an 'offset' that matches the background color creates a sharp, accessible focus state that feels integrated with the design.
**Action:** Always include 'focus-visible:ring-offset-2' with the background color to ensure the focus ring doesn't touch the element directly, improving visibility.
