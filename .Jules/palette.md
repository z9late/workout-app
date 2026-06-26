## 2026-02-10 - Roving Tabindex for Workout Modules
**Learning:** In a tabbed interface, the "Single Tab Stop" pattern (Roving Tabindex) provides a more streamlined keyboard experience than making every tab a separate tab stop. It follows the W3C WAI-ARIA Authoring Practices for Tabs.
**Action:** When implementing collection-based navigation (like tabs or menus), use `tabindex="0"` for the active item and `tabindex="-1"` for others, and handle arrow key navigation manually with `e.preventDefault()`.
