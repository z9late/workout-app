## 2026-06-04 - Accessible Tab Pattern
**Learning:** Implementing the roving tabindex pattern for collection elements (like tabs) requires a manual 'keydown' listener for arrow keys, Home, and End to ensure keyboard accessibility when inactive items are set to tabindex='-1'.
**Action:** Always include a 'keydown' listener and synchronize 'aria-selected' and 'tabindex' when creating or improving tabbed interfaces.

## 2026-06-04 - Visual Focus Indicators
**Learning:** Default browser focus outlines are often suppressed or inconsistent with dark-themed UIs. High-contrast focus rings using Tailwind's 'focus-visible:ring-2 focus-visible:ring-red-500' provide a clear and pleasant indicator for keyboard users.
**Action:** Apply consistent 'focus-visible' styles to all interactive elements, ensuring 'outline-none' is used only when a custom focus state is provided.
