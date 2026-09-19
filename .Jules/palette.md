## 2026-09-19 - Added keyboard focus visibility and changed hamburger to a button
**Learning:** The static HTML project had no visible focus states (`:focus-visible`) for interactive elements, making it difficult for keyboard users to navigate. The hamburger menu was also a `<div>` instead of a semantic `<button>`.
**Action:** Applied a global `:focus-visible` style using the existing theme variable `var(--accent)` and changed the hamburger menu to a native `<button>` to improve semantic HTML and keyboard accessibility.
