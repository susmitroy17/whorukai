## 2024-05-18 - Hamburger Menu Accessibility
**Learning:** Interactive elements like the hamburger menu were built using `<div>`s instead of semantic `<button>`s, breaking keyboard accessibility (cannot be focused or activated via Space/Enter).
**Action:** Replaced `<div>` with `<button>`, reset default button styles, and added `:focus-visible` states to restore keyboard navigation.
