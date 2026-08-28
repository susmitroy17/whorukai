## 2026-08-28 - Interactive Div Accessibility
**Learning:** In static sites relying on raw HTML without a framework, interactive elements like custom navigation menus often use non-semantic tags (like `div`) without necessary accessibility scaffolding.
**Action:** Always ensure that non-semantic interactive elements receive a `role="button"`, `tabindex="0"`, and a keyboard event listener (handling both Space and Enter with `preventDefault` for Space to prevent scroll) alongside a clear `:focus-visible` style.
