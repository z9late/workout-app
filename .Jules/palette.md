## 2026-05-15 - ARIA Tab Patterns and Keyboard Navigation
**Learning:** Implementing the roving tabindex pattern (manual Arrow key management) alongside semantic ARIA roles is critical for complex tabbed interfaces like workout logs to ensure they are both screen-reader friendly and keyboard-efficient.
**Action:** Always implement a centralized `keydown` listener for collection elements (tabs, menus) to handle `ArrowRight`, `ArrowLeft`, `Home`, and `End` keys, while synchronizing `tabindex` and `aria-selected` states.
