# Checkmate Academy

A free browser-based chess practice website.

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/dl99rokar/checkmate-academy)

Click the button above, review the static-site service, and approve deployment in Render. Render will publish the root `index.html` and assign the public site URL.

## What is included

- Legal chess moves via `chess.js` (loaded from esm.sh in the browser)
- Click-to-move and drag-and-drop
- Local two-player mode and a small browser-based practice bot
- Adjustable bot search depth, move history, undo, board flip and new games
- Basic chess habits and beginner lessons

## Honest limitations

The Academy Bot is a small local search opponent, not Stockfish and not a grandmaster-strength engine. The coaching panel gives factual move-event notes and general thinking prompts; it does not provide engine-backed best-move grades. The website needs an internet connection to load the chess-rules library from esm.sh. Games are played in the browser and are not synchronized between devices.

## Render configuration

This repository includes `render.yaml` for a static site. It needs no build step; Render publishes the repository root.
