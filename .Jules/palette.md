## 2026-05-18 - [Accessibility Audit: Tabs & Interactive States]
**Learning:** The custom tab implementation lacked semantic meaning and keyboard support, making it invisible to screen readers and difficult for keyboard-only users. Additionally, default focus states were suppressed, leading to poor visual feedback during navigation.
**Action:** Always implement the WAI-ARIA Tab Panel pattern (roles, aria-selected, roving tabindex) and provide explicit high-contrast focus indicators using `focus-visible` to ensure a truly accessible and intuitive "invisible UX".
