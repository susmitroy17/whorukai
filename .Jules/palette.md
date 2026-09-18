## 2026-09-18 - Hamburger Menu Accessibility
**Learning:** Custom interactive elements like hamburger menus should use semantic `<button>` tags instead of `<div>`s to inherit native keyboard accessibility (focusability and Enter/Space activation) and avoid building manual event listeners.
**Action:** Use native `<button>` tags with reset CSS (`background: transparent; border: none;`) for interactive controls, and dynamically bind `aria-expanded` attributes to match the menu state.
