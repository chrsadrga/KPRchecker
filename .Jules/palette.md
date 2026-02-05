## 2024-05-22 - Financial Input Readability
**Learning:** Users struggle to read large financial numbers (e.g., 850000000) in standard input fields, leading to "zero errors".
**Action:** Always pair `input type='number'` for currency with a real-time formatted helper text (e.g., "Rp 850.000.000") linked via `aria-describedby`.
