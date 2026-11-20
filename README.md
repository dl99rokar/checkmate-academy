# Checkmate Academy

A free, mobile-friendly chess practice website.

## Open the website

After GitHub Pages finishes its first deployment, visit:

**https://dl99rokar.github.io/checkmate-academy/**

## Deploy

This public repository includes a GitHub Actions workflow at `.github/workflows/deploy-pages.yml`. It publishes `index.html` to GitHub Pages on every push to `main`. The workflow also enables Pages for the repository. No Render account or payment card is needed.

## Included

- Legal chess moves using `chess.js` (loaded from esm.sh in the browser)
- Click-to-move and drag-and-drop
- Local two-player mode and a small browser-based practice bot
- Three adjustable practice levels
- Move history, undo, restart and board flip
- Basic chess lessons, hints and thinking checklist

## Honest limitations

The Academy Bot is a small local search opponent, not Stockfish or a grandmaster-level engine. The coach gives move-event notes and general thinking prompts; it does not yet provide engine-backed move grades, full game analysis, or tactic detection. The rules library is loaded from esm.sh, so the first game requires an internet connection. Games are kept in the browser and are not synchronized across devices.
