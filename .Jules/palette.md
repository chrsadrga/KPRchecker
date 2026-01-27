## 2024-05-22 - [Accessibility] Dynamic Content & Focus Indicators
**Learning:** Single-page calculators updating via JS often miss screen reader announcements. Adding `aria-live="polite"` is critical for "invisible" updates. Also, default browser focus rings are often suppressed by reset stylesheets; explicit `focus:ring` is needed for keyboard navigation.
**Action:** Always verify dynamic result containers have live regions and inputs have visible focus states.
