# Palette's Journal - Critical Learnings Only

## 2026-03-30 - Modal Keyboard Accessibility and Focus Restoration
**Learning:** In lightweight vanilla HTML/JS web applications that render modals dynamically into a root container (`#modalRoot`), closing modals without tracking the trigger element drops focus back to `document.body`. This breaks keyboard navigation flow for screen readers and power users. Adding an `Escape` key listener and caching `document.activeElement` upon opening provides immediate accessibility compliance and seamless focus restoration.
**Action:** When implementing modal/dialog dialog flows, always preserve the active triggering element before modal rendering and attach a clean `Escape` key handler that respects modal dismissibility (`opts.locked`).
