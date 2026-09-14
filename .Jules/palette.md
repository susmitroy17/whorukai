## 2026-09-14 - Interactive Elements as Native Buttons
**Learning:** In vanilla HTML portfolios, custom UI components like hamburger menus are often implemented as `<div>` tags with `onclick` handlers, breaking keyboard navigation and screen reader support since they lack implicit roles and focusability.
**Action:** Always convert custom interactive `<div>` components to native `<button>` elements to inherit keyboard support (Enter/Space) and focusability natively, and manage `aria-expanded` for stateful menus.
