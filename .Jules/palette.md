## 2026-01-24 - Accessible Tab Implementation
**Learning:** Implementing the roving tabindex pattern for tabs requires not only role and aria-selected management but also a manual keydown listener for arrow keys to ensure a seamless keyboard-only experience.
**Action:** Always use role="tablist", role="tab", and role="tabpanel" together with a centralized tab switching function that updates both visual and accessibility states (aria-selected, tabindex).
