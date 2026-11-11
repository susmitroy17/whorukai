## 2024-05-16 - Hamburger Menu Accessibility
**Learning:** The application's custom navigation menu (`navbar__hamburger`) uses a non-semantic `div` with an `onclick` handler, which prevents keyboard navigation and lacks dynamic ARIA state (`aria-expanded`) for screen readers.
**Action:** Converted the menu toggle to a semantic `<button>`, stripped default button styles, added `:focus-visible` styling with `var(--accent)`, and implemented programmatic toggling of `aria-expanded` in the JavaScript menu handler.
