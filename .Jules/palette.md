## 2026-06-10 - ARIA Tab Pattern & Focus States
**Learning:** Implementing the roving tabindex pattern for tabs requires a manual keydown listener and synchronization of `tabindex` and `aria-selected` attributes to provide a standard-compliant experience for screen readers and keyboard users.
**Action:** Use `role="tablist"`, `role="tab"`, and `role="tabpanel"` with appropriate IDs and ARIA relationships. Ensure only the active tab has `tabindex="0"` while others have `tabindex="-1"`.
