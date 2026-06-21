# Palette's Journal - Critical UX/Accessibility Learnings

This journal documents critical UX and accessibility insights discovered during the development of GRIND.

<!--
Format:
## YYYY-MM-DD - [Title]
**Learning:** [UX/a11y insight]
**Action:** [How to apply next time]
-->

## 2026-05-18 - Accessible Tabs with Roving Tabindex
**Learning:** Standard static tab implementations often lack keyboard support and ARIA state. Using a "roving tabindex" pattern (tabindex="0" for active, "-1" for inactive) combined with Arrow key listeners provides a professional, "app-like" feel that is fully accessible to screen readers and keyboard users.
**Action:** Always implement the roving tabindex pattern for tabbed interfaces and ensure focus-visible rings are high-contrast (e.g., focus-visible:ring-red-500) against dark backgrounds.
