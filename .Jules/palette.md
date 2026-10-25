## 2026-10-25 - Modal Dialog Escape Dismissal and Focus Management

**Learning:** Modal dialogs rendered dynamically (`role="dialog" aria-modal="true"`) require active option tracking (`activeModalOpts`) to support standard WCAG `Escape` key dismissal and custom `onClose` callbacks when returning to parent modal views (e.g., from sub-modals like the exercise library).

**Action:** Whenever implementing single-container modal systems (`#modalRoot`), track active options to enable global `Escape` key listeners and auto-focus primary modal inputs upon opening.
