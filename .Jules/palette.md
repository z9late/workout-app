# Palette's Journal

## 2026-07-06 - Modal Dialog Escape Dismissal and Focus Return
**Learning:** Single-container modal architectures (like dynamic `#modalRoot`) that rely solely on backdrop clicks and close buttons leave keyboard users trapped or disoriented if the standard `Escape` key is not intercepted and the active trigger element is not restored upon closing.
**Action:** When creating dynamic dialogs in `#modalRoot`, record `document.activeElement` before mounting and restore focus to it on `closeModal()`, while listening for global `Escape` key events when an unlocked modal is active.
