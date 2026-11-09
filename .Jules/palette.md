## 2024-11-09 - Accessible Hamburger Menu Button
**Learning:** When custom interactive elements (like a hamburger menu) are implemented as `div` tags, they lack native keyboard accessibility and proper screen reader context, failing WCAG compliance.
**Action:** Always convert custom interactive `div` elements to semantic `<button>` elements, reset default button styles, add appropriate `aria-expanded` attributes that are dynamically toggled via JavaScript, and implement a custom `:focus-visible` outline for keyboard accessibility.
