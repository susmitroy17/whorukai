## 2026-10-28 - Hamburger Menu Accessibility
**Learning:** When converting a `div` hamburger menu to a semantic `button`, explicitly stripping default button styles and managing `aria-expanded` with string values ('true'/'false') is required for screen readers, and a custom `:focus-visible` style must be provided if removing default outlines.
**Action:** Always use semantic `button` elements with proper ARIA state toggling and explicitly defined `:focus-visible` states for dynamic menus.
