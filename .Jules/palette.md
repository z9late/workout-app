## 2026-05-20 - Navigation Accessibility & Context
**Learning:** In Single Page Applications (SPAs) or apps mimicking them, users lose vital context when the document title and ARIA states (like aria-current) don't update upon navigation. Screen reader users especially rely on these updates to know where they are. Additionally, skip links are essential for keyboard users to bypass repetitive header navigation, especially when it's sticky and covers large areas.

**Action:** Always update `document.title` and manage `aria-current="page"` within the central navigation function. Implement a "Skip to content" link at the start of the body for all web interfaces. Ensure interactive logos maintain their semantic role (e.g., wrap button in an <h1>).
