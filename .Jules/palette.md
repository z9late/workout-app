## 2026-06-13 - [WAI-ARIA Tab System with Roving Tabindex]
**Learning:** Standard tab interfaces often lack keyboard accessibility. Implementing the WAI-ARIA tab pattern (roles tablist/tab/tabpanel) combined with a roving tabindex (managing `tabindex` dynamically) allows for a "single tab stop" experience that is both screen-reader friendly and efficient for keyboard users.
**Action:** Always implement roving tabindex for collections of interactive elements like tabs or carousels to ensure users can navigate within the component using arrow keys without cluttering the global tab order.
