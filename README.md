# Number Adventure

A fun, very interactive math adventure for a 2nd grader — built to take her to expert: every concept is taught with pictures and models first, and any concept she misses is taught again and practised with freshly generated problems until she masters it.

## Play
- Open https://virvkh-ux.github.io/number-adventure/ on any device (phone, tablet, desktop — Safari, Chrome or Edge), then use Share -> "Add to Home Screen" to install it.
- Works offline after the first visit. Progress saves on the device and can carry the same state across devices: Grown-ups corner -> "Turn on sync" on the first device, then join with the sync code (or the ?sync= link) on the others. Sync uses the family's existing Firebase project, the same setup as Math Quest, and merges progress without overwriting.
- No accounts for the child, no ads, no external links in the game.

## Worlds
Story Lab (sentence / word problems, taught step by step with bar models) plus worlds covering number bonds and make-a-10, addition & subtraction to 20 / 100 / 1000 with carrying and borrowing, place value, skip counting and rounding, fact families and X equations, multiplication foundations with equal groups, arrays and sharing, money, time, fractions, shapes, perimeter, measurement and graphs.

## Fun built in
Animated pet that hatches and grows, points and player levels with ranks, missions and badges, Tricky Bits trophies for conquered misconceptions, boss battles and Expert Trials, light music and a fun natural voice with read-aloud, and a work-it-out toolbox (drawing pad, counters, ten-frames, number line, base-ten blocks, bar-model builder, coins, clock and more).

## Layout
- `src/index.html` — the whole game in one self-contained file (vanilla HTML/CSS/JS, no build step, no external assets)
- `index.html` (root) redirects to `src/` for GitHub Pages
- Progress format: localStorage on each device, synced via Firebase Firestore (REST) when sync is turned on
