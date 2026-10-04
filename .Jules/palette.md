## 2026-10-04 - Screen Reader Compatibility for Dynamic Menus
**Learning:** When a custom animated hamburger menu relies on CSS transforms within a non-semantic container (like a div), it is completely invisible to screen readers and lacks native keyboard interactibility.
**Action:** Always convert custom interactive components to semantic elements (like button) with appropriate ARIA states (aria-expanded) managed programmatically to bridge visual and assistive technologies, taking care to reset native styling to preserve the custom design.
