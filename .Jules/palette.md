## 2026-09-15 - Native buttons for interactive controls
**Learning:** Using semantic `<button>` elements rather than `<div>` with `onclick` for interactive controls (like a hamburger menu) is crucial for keyboard operability. Furthermore, using `aria-expanded` is required to convey the open/closed state of the menu to screen readers.
**Action:** Always prefer native interactive elements (`<button>`, `<a>`) and implement visible focus states globally (e.g. `:focus-visible`). Keep attributes like `aria-expanded` in sync with the element's actual visual state in JavaScript.
