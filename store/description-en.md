# Word Gallows — Store Submission Materials

## Short description (CrazyGames / GameDistribution / itch.io)

Guess the hidden word before the chalk figure is finished. 400 words in
three difficulties, chalkboard art, streak multiplier, hand-drawn hangman.
A classic word puzzle, redrawn in chalk.

## Details

- Genre: Puzzle / Word / Casual
- Controls: On-screen keyboard (touch) or physical A-Z keys; Enter
  continues after each round.
- Features: 400 words in 3 difficulties (Easy 4–5 letters, Medium 6–8,
  Hard 9–12), category hint chip (Animal / Food / Place / Object / Action
  and more), 6 chances with animated chalk-stroke figure drawing, scoring
  by chances left × 100 + length × 20, ×1.5 streak multiplier at 3+ wins,
  best-run and longest-streak saving, word + definition reveal on every
  round end, mute toggle, guessed-letter keyboard graying.
- Tech: Vanilla JavaScript, Canvas (procedural chalkboard & chalk strokes),
  WebAudio (synthesized sounds). Single-file HTML5, no external assets,
  works offline once loaded. No frameworks, no tracking.

## Tags
hangman, word, guess, puzzle, vocabulary, casual, chalk, letters, brain, single-file

## CrazyGames submission checklist
- [x] Self-contained index.html (SDK loads only on crazygames domains)
- [x] gameplayStart / gameplayStop / loadingStart / loadingStop / happytime events wired
- [x] Responsive (canvas scales to viewport, portrait-friendly)
- [x] No external links inside gameplay, no analytics
- [ ] Cover: 16:9 capture of the blackboard mid-round (1280×720)
- [ ] Screenshots: gameplay capture with figure half-drawn (1280×800)

## itch.io
- Upload zip (rename to hangman.zip or use hangman-itch.zip), mark
  "This file is playable in browser", entry file: index.html,
  viewport 480×800, kind: html
- Pricing: $0 (donations optional)
