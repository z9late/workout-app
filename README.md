# GRIND — Workout Tracker

A single-file, offline-first workout tracker with a dark athletic aesthetic. No build step, no backend — everything lives in `index.html` and persists to `localStorage`.

## Run it

Serve the folder with any static server, e.g.:

```
npx serve . -l 3000
```

Then open http://localhost:3000.

## Features

- **Dashboard** — week strip, weekly volume/sets, PR count, streak, and a "Next up" card that rotates through the Upper/Lower split.
- **Live workout logging** — previous session's weights auto-filled per set (Hevy-style), Enter or ✓ completes a set.
- **Automatic rest timer** — starts when a set is completed, per-exercise durations, ±15s / skip, beep + vibration when done.
- **PR detection** — estimated 1RM (Epley) compared against all history; PRs badge live and in the finish summary.
- **Routines** — the GRIND Upper A / Lower A / Upper B / Lower B templates are seeded; build, edit, and delete your own from a 36-exercise library.
- **History** — every workout with duration, volume, sets, and expandable set-by-set detail.
- **Progress** — weekly volume chart, per-exercise strength curve, 30-day muscle split, and a personal records table (Chart.js).
- **Resilient sessions** — an in-progress workout survives a page refresh.

First run shows an empty state with a "Load 8 weeks of sample data" option so charts and history can be explored immediately.

## Data

All data is stored in `localStorage` under `grind.v1` (history + routines) and `grind.session.v1` (active session). Clear those keys to reset.
