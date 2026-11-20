# Checkmate Academy

A free, mobile-friendly chess practice website.

## Publish the website for free

This repository contains a static `index.html` file in its root. Enable GitHub Pages once:

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Set **Branch** to `main` and folder to `/(root)`.
4. Click **Save**.

The website address will be:

**https://dl99rokar.github.io/checkmate-academy/**

No payment card or paid hosting account is needed.

## Included

- Legal chess moves using `chess.js` (loaded from esm.sh in the browser)
- Click-to-move and drag-and-drop
- Local two-player mode and a small browser-based practice bot
- Three adjustable practice levels
- Move history, undo, restart and board flip
- Basic chess lessons, hints and thinking checklist

## Honest limitations

The Academy Bot is a small local search opponent, not Stockfish or a grandmaster-level engine. The coach gives move-event notes and general thinking prompts; it does not yet provide engine-backed move grades, full game analysis, or tactic detection. The rules library is loaded from esm.sh, so the first game requires an internet connection. Games are kept in the browser and are not synchronized across devices.
