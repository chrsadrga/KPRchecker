## 2026-01-18 - Accessibility in Simple Forms
**Learning:** Even in simple single-page apps, missing `for` attributes on labels breaks accessibility for screen reader users. Small text (<12px) often fails contrast checks even with "standard" gray colors like `text-slate-400`.
**Action:** Always check `label` association with inputs and verify contrast for small text sizes, upgrading to darker shades (e.g., `text-slate-500`) when necessary.
