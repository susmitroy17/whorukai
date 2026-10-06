## 2024-05-20 - Semantic conversion of dynamic menu triggers
**Learning:** Using `div`s for hamburger menus breaks keyboard navigation and prevents screen readers from understanding the menu state, even if `aria-label` is present.
**Action:** Always convert custom menu triggers to semantic `<button>` elements. Strip default button styles to prevent visual regressions, implement `:focus-visible` with `outline-offset` for keyboard users, and programmatically toggle `aria-expanded` between `"true"` and `"false"` as strings to properly announce dynamic state.
