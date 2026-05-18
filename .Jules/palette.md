# Palette's Journal - GRIND UX/Accessibility

## 2025-05-14 - Accessible Tabbed Interfaces
**Learning:** Standard HTML/CSS tab implementations often lack proper ARIA roles and keyboard navigation (roving tabindex), making them invisible or difficult to navigate for screen reader and keyboard users.
**Action:** Implement WAI-ARIA 'tablist', 'tab', and 'tabpanel' roles. Use `aria-selected` and `tabindex` to manage state. Add a keydown listener for arrow key navigation to support the 'single tab stop' pattern.

## 2025-05-14 - Minimal ARIA vs. Full Keyboard Nav
**Learning:** In constrained environments where line counts are limited, structural ARIA roles and state management (aria-selected) provide the highest baseline accessibility win. However, full keyboard navigation (arrows/Home/End) is required for a complete WAI-ARIA pattern.
**Action:** Prioritize roles and state in minimal patches, but document missing keyboard navigation as technical debt. Ensure no environment-specific test artifacts (like `test-results/`) are committed.
