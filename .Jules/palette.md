## 2026-07-05 - ARIA Tab Patterns and Roving Tabindex
**Learning:** Implementing the WAI-ARIA tab pattern significantly improves keyboard accessibility for users. By synchronizing aria-selected, tabindex, and the hidden attribute, we ensure screen readers and keyboard users can navigate complex tabbed interfaces intuitively.
**Action:** Always implement roving tabindex (tabindex="0" for active, tabindex="-1" for inactive) and handle ArrowLeft/Right/Home/End keys for collection-based components like tabs or carousels.

## 2026-07-05 - Keyboard Focus Visibility
**Learning:** Dark-themed UIs often have poor focus visibility if default browser styles are used. Using Tailwind's focus-visible:ring with white rings and slate-950 offsets provides a high-contrast focus state that is aesthetically pleasing yet accessible.
**Action:** Use focus-visible:ring-white with ring-offset-2 and ring-offset-slate-950 for interactive elements on dark backgrounds to ensure they meet accessibility standards without impacting mouse users.
