## 2026-10-02 - Converting Hamburger Menus to Semantic Buttons

**Learning:** When converting a dynamic hamburger menu from a `<div>` to a semantic `<button>` for accessibility, you need to explicitly remove the browser's default button styling (`background: transparent; border: none; outline: none;`) to prevent visual regressions while keeping custom padding/width. Furthermore, maintaining the exact string representation of `aria-expanded` (e.g. `'true'` or `'false'`) dynamically via JavaScript ensures screen readers announce the exact real-time state of the menu.

**Action:** Whenever converting div-based toggles to buttons, always strip default styling and implement `aria-expanded` toggling in JavaScript to ensure true semantic accessibility.
