
## 2024-05-24 - Hamburger Menu Accessibility Conversion
**Learning:** When converting custom `div` elements to `button` elements for accessibility, we must explicitly reset the browser default styles (`background: transparent; border: none; outline: none;`) to prevent visual regressions while retaining custom padding/width. Furthermore, semantic buttons with dynamic states must explicitly toggle `aria-expanded` (using strings 'true' and 'false') for screen readers to correctly interpret the state.
**Action:** Apply CSS resets consistently when converting non-semantic interactive elements to buttons, add focus-visible styles using existing tokens (like `var(--accent)`), and ensure JavaScript state toggles are reflected in ARIA attributes.
