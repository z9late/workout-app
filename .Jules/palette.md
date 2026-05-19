## 2025-05-14 - [Accessible Tabs Pattern]
**Learning:** Standard static HTML/JS tab patterns often neglect accessibility. Implementing the WAI-ARIA Tabs pattern requires a combination of ARIA roles (`tablist`, `tab`, `tabpanel`), state management (`aria-selected`), and roving `tabindex` with keyboard listeners for a truly inclusive experience.
**Action:** Always implement the "single tab stop" pattern for collections by using `tabindex="0"` for the active item and `tabindex="-1"` for inactive ones, coupled with arrow key navigation.
