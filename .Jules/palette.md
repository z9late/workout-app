## 2026-06-16 - Accessible Tab Navigation Pattern
**Learning:** Implementing the roving tabindex pattern for collection elements (like tabs) in a vanilla JS environment requires manual synchronization of `aria-selected`, `tabindex`, and `hidden` attributes to ensure a consistent experience for screen reader and keyboard users.
**Action:** Always pair `tabindex="0"` on the active element with `tabindex="-1"` on inactive siblings, and use `e.preventDefault()` in keyboard listeners to suppress default browser behaviors.
