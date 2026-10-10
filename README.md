# rocketmq-dashboard date picker bug — screenshots

Assets for the bug report and the fix PR (referenced from the issue / PR body).

- `picker-before-after.png` — side-by-side: official 2.1.0 image vs the fixed build
- `picker-before.png` — official image: all 42 calendar cells selected, panel shows **Feb 2029** for a `2026-10-10` value
- `picker-after.png` — with fix: only the current value selected, panel opens on **Oct 2026**

Captured with headless Chromium against the same dashboard instance, only the frontend bundle differs.
