## 2024-05-23 - Interactive elements using div tags lack accessibility

**Learning:** When using `div` elements for custom interactive controls like a hamburger menu button, they natively lack keyboard navigation support (Space/Enter keys) and focus indicator states. This creates accessibility issues for keyboard and screen reader users.

**Action:** Convert `div` based buttons to native `<button>` elements, reset default button styling with `background: transparent; border: none;`, and add clear `:focus-visible` outlines. Additionally, for toggle buttons, ensure the `aria-expanded` state is dynamically managed via JavaScript to accurately convey state to screen readers.
