## 2026-02-01 - Real-time Currency Formatting Helper
**Learning:** In financial inputs (like IDR), users struggle to count zeros in raw number fields (e.g., 850000000). Standard `input type="number"` removes formatting, creating high cognitive load.
**Action:** Always pair `input type="number"` with a real-time formatted helper text (e.g., "Rp 850.000.000") linked via `aria-describedby` to provide immediate confirmation without breaking mobile keyboard support.
