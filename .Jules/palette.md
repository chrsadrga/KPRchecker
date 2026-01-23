# PALETTE'S JOURNAL - CRITICAL LEARNINGS ONLY

## 2024-05-22 - Missing Label Associations in Raw HTML
**Learning:** Raw HTML forms often miss the `for` attribute on labels, breaking screen reader associations and click-to-focus behavior. This is common when not using a component library that handles it automatically.
**Action:** Always verify `label` tags have a `for` attribute matching the input's `id`.
