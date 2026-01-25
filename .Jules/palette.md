## 2024-10-24 - Form Accessibility Gaps
**Learning:** Initial form implementation used explicit label elements but missed `for` attributes connecting them to inputs, hindering screen readers and click-to-focus behavior.
**Action:** Always check `label` tags for `for` attributes matching input `id`s, especially in simple HTML forms.
