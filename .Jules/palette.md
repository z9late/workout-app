## 2026-05-31 - [Tab Accessibility and Roving Tabindex]
**Learning:** Implementing the 'single tab stop' pattern (roving tabindex) significantly improves keyboard navigation efficiency for tabbed interfaces. Synchronizing 'aria-selected' with 'tabindex' ensures screen readers and keyboard users stay in sync with the visual state.
**Action:** For all collection-based components (tabs, carousels, menus), implement manual arrow key navigation and manage tabindex dynamically to maintain a clean tab order.
