## 2025-05-14 - Accessible Tab Pattern Implementation
**Learning:** For a fully accessible tabbed interface (WAI-ARIA), it's not enough to just add roles and `aria-selected`. To provide a streamlined keyboard experience, only the active tab should have `tabindex="0"`, while all other tabs should have `tabindex="-1"`. This allows the user to enter the tab list with one Tab press and then navigate between tabs using arrow keys, rather than tabbing through every single tab.
**Action:** Always manage `tabindex` dynamically when implementing tabbed components or similar grouped controls.
