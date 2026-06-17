## 2026-06-17 - Roving Tabindex for Workout Modules
**Learning:** Implementing the 'roving tabindex' pattern on tab interfaces significantly improves keyboard accessibility by allowing users to navigate through tab options with arrow keys while maintaining a single tab stop for the collection.
**Action:** Always pair `role="tablist"` with a keyboard event listener for arrow keys, and synchronize `aria-selected` and `tabindex` attributes during tab transitions.
