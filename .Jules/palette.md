## 2026-05-15 - Accessible Tabbed Interface with Keyboard Navigation

**Learning:** Implementing the roving tabindex pattern for tabbed interfaces significantly enhances accessibility for keyboard and screen reader users. Simply toggling classes is insufficient; managing `aria-selected`, `tabindex`, and the `hidden` attribute on panels is critical for a standard-compliant experience.

**Action:** For all collection-based components (tabs, menus, grids), prioritize the roving tabindex pattern. Use `aria-selected` for state, `tabindex="0"` only for the active element, and handle `ArrowLeft`, `ArrowRight`, `Home`, and `End` keys explicitly.
