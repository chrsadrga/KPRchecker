## 2024-05-22 - Static Form Accessibility Gaps
**Learning:** The static HTML forms in this codebase consistently lacked explicit `label-for` associations and custom focus states, relying on defaults which may be insufficient for accessibility.
**Action:** Always check `label` tags for `for` attributes and ensure interactive elements have visible focus indicators (like `focus:ring`) in future static HTML pages.
