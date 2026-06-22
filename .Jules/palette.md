## 2026-05-15 - Accessible Tab Navigation with Roving Tabindex
**Learning:** For tabbed interfaces, implementing the WAI-ARIA tab pattern (role="tablist", "tab", "tabpanel") along with a roving tabindex ensures that screen reader users understand the structure and keyboard users can navigate efficiently using arrow keys. Using `:focus-visible` ensures that focus rings only appear for keyboard users, maintaining a clean aesthetic for mouse users.

**Action:** Always implement roving tabindex for collections like tabs or carousels where only one item should be a tab stop. Use `e.preventDefault()` on arrow keys to prevent page scrolling while navigating.
