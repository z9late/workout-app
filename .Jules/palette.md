## 2025-05-14 - Accessible Tab Navigation Pattern
**Learning:** Generic tab implementations often miss critical keyboard accessibility features like roving tabindex and arrow-key navigation, making them difficult for screen reader and keyboard-only users.
**Action:** When encountering tabbed interfaces, implement the full WAI-ARIA tab pattern: use `role="tablist"`, `role="tab"`, and `role="tabpanel"`, manage `aria-selected` and `tabindex` dynamically, and provide a keyboard listener for arrow key navigation.
