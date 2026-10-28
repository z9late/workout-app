## 2026-10-28 - Global Keyboard Modal Dismissal & Navigation Context

**Learning:** Single-page web apps without routing frameworks often miss screen-reader location context (`aria-current="page"`) and global keyboard escape handlers for modal dialogs.
**Action:** Always maintain an active modal options state to support `Escape` key dismissal while preserving locked modals, and ensure routing state functions (`navTo`) dynamically synchronize `aria-current="page"` across primary navigation elements.
