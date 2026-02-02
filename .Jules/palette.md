## 2024-05-22 - Formatted Helpers for Financial Inputs
**Learning:** Users struggle to read large financial numbers (millions/billions) in raw input fields. Native number inputs often hide separators or show unwanted spinners.
**Action:** Always pair `input type="number"` for currency with a real-time formatted helper text element linked via `aria-describedby` to confirm the value (e.g., "Rp 850.000.000").
