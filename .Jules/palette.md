# Palette's Journal

## 2026-11-01 - Modal Keyboard Dismissal & Focus Restoration Pattern
**Learning:** Single-file static web apps with dynamic modal layers often trap or drop keyboard focus when modals open and close. Providing global `Escape` key listeners on `#modalRoot` paired with caching `document.activeElement` before mounting allows modal interactions to seamlessly support keyboard navigation without dropping focus to the top of the body upon dismissal.
**Action:** Always store the triggering element (`document.activeElement`) prior to mounting dynamic modal overlays and restore focus on dismissal unless the trigger element was removed from the DOM.
