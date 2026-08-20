# Are You Ready for Beast Academy 1A?

A mobile-friendly, tap-to-answer version of the Art of Problem Solving
"Are you ready for Beast Academy 1A?" readiness check — for a parent to run
with a first grader on a phone.

**Live:** https://sorendeorlow.github.io/beast-academy-1a-check/

## What it does

- All 16 problems from the original placement check, made clickable:
  compare-more-dots, count the dots, connect-the-dots in order, fill number
  patterns, and "more/less than" word problems.
- Auto-scores and shows a parent report (score, per-question grid, and the
  12-of-16 "ready" verdict).
- Follows the original rules: 12/16 = ready, and problems 5–16 get a second
  try if the first answer is off.
- Read-aloud button (browser text-to-speech) on the word problems for
  beginner readers.

## Design

Styled in the [AoPS careers](https://artofproblemsolving.com/careers) brand:
warm off-white ground, forest-green primary, PT Serif headlines, and
hand-drawn line-art math doodles.

## Tech

A single self-contained `index.html` — no build step, no dependencies, no
external requests (PT Serif is embedded as a data URI). Works offline.

---

The underlying readiness check is © AoPS Incorporated. This is an unofficial
interactive adaptation.
