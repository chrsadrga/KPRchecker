## 2026-01-22 - Missing Label Associations in Vanilla HTML
**Learning:** Even in simple static HTML pages with Tailwind, forgetting `for` attributes on labels significantly hurts accessibility and usability (click targets).
**Action:** Always verify form inputs by clicking their labels. Use `for="id"` matching the input's `id`. For number inputs, adding `onfocus="this.select()"` is a high-value micro-interaction.
