# Jumpseat

Flashcard training for new flight attendants. Pick your airline, then learn its airport codes and its aircraft.

## What's inside

- **Airport codes:** your airline's stations, with spaced daily review, pairings practice and a mastery map.
- **Aircraft:** seat counts, premium cabins, exits, FAA crew minimums, Spot the Plane drawings, engines, and Find the Exits on top-down cabin plans built from each airline's configurations.
- **Levels:** Standard, Advanced (tighter decoys) and Expert (type the answer).

## Running it

Jumpseat is a single self-contained file, `index.html`. Open it in any modern browser, or host it with GitHub Pages:

1. Push this repository to GitHub.
2. In the repository, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, and save.
4. After a minute the site is live at `https://<your-username>.github.io/<repo-name>/`.

Progress (streaks, reviews, mastery) is saved in each player's browser with `localStorage`, so it stays on that device.

## Data

Fleet, seat and exit data is compiled from airline websites, airline fleet fact sheets, Wikipedia fleet pages, AeroLOPA and FAA/EASA type certificate data, as of October 2026. Aircraft outlines were measured from published side-view references and drawn by Jumpseat's own generator.

This is general familiarization, not training of record. Exit operation, crew positions and procedures come from each carrier's FAA-approved manuals.
