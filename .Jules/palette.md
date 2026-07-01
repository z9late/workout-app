## 2026-03-24 - [Accessible Tabs Pattern]
**Learning:** Implementing the roving tabindex pattern for tabbed interfaces significantly improves keyboard accessibility by providing a single tab stop and intuitive arrow-key navigation, aligning with WAI-ARIA standards.
**Action:** Use `tabindex="0"` for the active tab and `tabindex="-1"` for inactive ones, synchronized with `aria-selected` and `keydown` event listeners for Arrow keys, Home, and End.

## 2026-03-24 - [Visible Focus Rings]
**Learning:** High-contrast elements (like red buttons) require specific focus ring offsets and colors (e.g., white ring on dark background) to remain visible when focused, as standard rings might blend into the element's primary color.
**Action:** Apply `focus-visible:ring-white focus-visible:ring-offset-2 focus-visible:ring-offset-slate-950` to high-contrast interactive elements.
