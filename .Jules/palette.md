## 2026-11-05 - Modal Escape Dismissal and Focus Restoration
**Learning:** In a single-file, dialog-overlay web application where modals are rendered directly into a root container (`#modalRoot`), omitting global `Escape` key handling and focus restoration leaves keyboard and screen reader users trapped or disoriented when closing dialogs.
**Action:** When creating modal systems, always track the invoking trigger element (`document.activeElement`) upon opening and restore focus to it in `closeModal()`, while listening for `Escape` to allow effortless dismissal unless explicitly locked.
