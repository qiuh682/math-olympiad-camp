# Math Olympiad Camp

Daily one-hour math olympiad training, built for a fifth grader working toward
MOEMS, AMC 8, Math Kangaroo and eventually MATHCOUNTS.

Open `index.html`. Everything runs in the browser: no account, no network calls,
no ads, no tracking. Progress is stored on the device in localStorage.

## Put it on an iPad

1. Open the published URL in **Safari** (it must be Safari — Chrome on iOS cannot install web apps).
2. Tap **Share** → **Add to Home Screen**.
3. It launches full screen, with no browser bars, and works offline after the first visit.

## Files

| File | What it is |
|---|---|
| `index.html` | Home screen — lists the days, shows stars earned |
| `day01_game.html` | Day 1: order of operations, compensation, splitting |
| `day02_game.html` | Day 2: place value, estimation, pairing |
| `sw.js` | Service worker — offline caching |
| `manifest.webmanifest` | Web app manifest — icon, name, standalone display |
| `icon-*.png`, `apple-touch-icon.png` | App icons |

## Each day contains

Warm-up, three concept levels with a handbook, Spot the Mistake, Number Forge
(make-the-target with four cards), Countdown Duel (buzzer race against a rival),
and a Boss Battle of contest problems. Plus collectible trick cards, an error
book with a rematch mode, and a printable end-of-session summary.

Practice problems are generated, so they never run out. Every generated problem
derives its answer from the same expression it displays, so the two cannot disagree.

## Publishing

Settings → Pages → Source: *Deploy from a branch* → `main` / `/ (root)`.
After editing any file, bump `CACHE` in `sw.js` so installed copies pick up the change.
