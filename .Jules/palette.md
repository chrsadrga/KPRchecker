## 2025-02-18 - Calculator Accessibility and Focus
**Learning:** Single-page calculators often lack label associations and status announcements, confusing screen reader users. Explicitly linking labels with `for` and using `aria-live` on result containers is a critical pattern for "instant" calculators.
**Action:** Always audit form labels and dynamic result areas in calculator components.
