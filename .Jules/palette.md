
## 2023-10-12 - Semantic HTML Overlays Need Explicit Button State Management
**Learning:** When converting generic block elements (`<div>`) to semantic interactive elements (`<button>`) for dynamic overlays like a hamburger menu, it's not enough to just change the tag. The `aria-expanded` state must be programmatically managed via JavaScript (toggling between `"true"` and `"false"`) to properly inform screen readers of the menu's open/close status.
**Action:** Always verify that dynamic interactive states introduced by tag changes are hooked into the application's JavaScript to actively manage ARIA attributes.
