## 2025-05-17 - [Accessible Tab Pattern]
**Learning:** Implementing WAI-ARIA `role="tab"` with a roving `tabindex` (where inactive tabs are `tabindex="-1"`) requires a manual `keydown` listener for arrow keys. Without this, keyboard users can only access the currently active tab, effectively breaking navigation.
**Action:** Always pair `tabindex="-1"` on collection elements with a keyboard navigation handler for arrow keys, Home, and End.
