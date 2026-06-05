## 2026-02-12 - [Accessible Roving Tabindex Pattern]
**Learning:** Implementing the roving tabindex pattern for tabbed interfaces requires synchronizing `aria-selected` and `tabindex` attributes on both buttons and panels to ensure screen readers and keyboard-only users can navigate effectively.
**Action:** Always include a `keydown` listener for arrow keys (and Home/End) to allow continuous cycling through the tab collection, and ensure inactive tabs/panels are set to `tabindex="-1"`.
