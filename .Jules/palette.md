## 2024-05-01 - Hamburger Menu Accessibility
**Learning:** In this application, dynamic menu states implemented as custom elements (like the hamburger menu) lack native keyboard and screen reader support, requiring explicit conversion to semantic buttons, stripping of default styles, custom `:focus-visible` outlines, and programmatic `aria-expanded` toggling.
**Action:** Always convert custom interactive `div` elements to semantic `<button>` elements, provide explicit focus styles using `var(--accent)`, and manage ARIA states programmatically.
