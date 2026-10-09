# Memory Dojo

A daily memory training game that runs in the browser and installs on your phone.

Five daily quests:
- Kim's Game: memorize a grid of objects, then pick them out of a mixed set
- Number Drill: recall digit strings that get longer as you improve
- Memory Palace: place words along your own route, then recall them by location
- Flashcards: Leitner system with 5 boxes (1, 2, 4, 8, 16 day intervals)
- Evening Recall: replay and write down your day

Complete 3 of 5 each day to keep your streak. Difficulty adjusts automatically. Progress is stored on the device (use Stats > Export backup).

## Deploy on GitHub Pages

1. Create a new public repo on GitHub, e.g. `memory-dojo`.
2. Upload all files in this folder to the repo root (Add file > Upload files).
3. Go to Settings > Pages. Under "Build and deployment", set Source to "Deploy from a branch", branch `main`, folder `/ (root)`. Save.
4. After a minute the site is live at `https://<your-username>.github.io/memory-dojo/`.

## Install on your phone

- iPhone: open the link in Safari, tap Share, then Add to Home Screen.
- Android: open the link in Chrome, tap the menu, then Install app (or Add to Home screen).

It works offline after the first visit.

## Updating

Edit and commit files as usual. If the phone keeps showing an old version, bump `CACHE` in `sw.js` (e.g. `memory-dojo-v2`).
