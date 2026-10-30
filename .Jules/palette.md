
## 2026-03-30 - Modal Dismissal & Escape Key Standard
**Learning:** Modals using generic container elements without keyboard event listeners isolate keyboard users. Storing modal options (such as `onClose` callbacks) in an `activeModalOpts` state variable allows global `Escape` key handlers to invoke modal teardown logic cleanly while preserving nested modal navigation flows.
**Action:** When implementing modal dialogs, ensure `activeModalOpts` or a modal manager captures `onClose` hooks and supports global `Escape` dismissal unless explicitly locked (`locked: true`).
