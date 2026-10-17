
## 2025-02-18 - Semantic Navigation Toggles
**Learning:** Converting interactive `div` elements to `button` elements is an easy accessibility win, but requires specific handling for dynamic states. Screen readers expect dynamic attributes like `aria-expanded` to be updated via JavaScript (as strings `'true'` or `'false'`), and visual focus states must be explicitly provided if default outlines are overridden.
**Action:** Always map visual interactive states (like open menus) to their corresponding ARIA attributes programmatically to ensure assistive technologies stay in sync with the UI.
