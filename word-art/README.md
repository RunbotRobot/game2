# word-art

Optional per-word illustrations for LEXIQUEST (`../index.html`).

The game works fully without anything in this folder — every word falls
back to a generic, part-of-speech-colored "spirit" sprite that's baked
into `index.html` itself. Files placed here are progressively layered on
top of that fallback, lazy-loaded one at a time only when a word is
actually shown (an encounter, or its entry in the Worddex), never
bundled or preloaded in bulk.

## Convention

- Filename: the word in **uppercase**, exactly as it appears in
  `WORD_BANK` in `index.html`, plus `.png`.
  Example: the word `GLIMMER` → `word-art/GLIMMER.png`.
- Format: PNG with a transparent background, square-ish framing,
  centered subject, similar crop/margins to the existing generic
  spirit art so it drops in at the same size. Transparent PNG only
  (no JPG) since it's composited over colored UI panels.
- Keep the file reasonably small (a few hundred KB at most) — this
  folder is served to every player's browser on demand.

## Hosting

Served directly from this GitHub repo via the jsDelivr CDN:

```
https://cdn.jsdelivr.net/gh/RunbotRobot/game2@claude/word-learning-rpg-sghck9/word-art/<WORD>.png
```

No separate image host or account needed — pushing a file here to that
branch is enough to make it live at that URL. `index.html` reads this
same base URL from the `WORD_ART_BASE` constant — **keep them in sync**.
If/when this branch merges into `main`, switch both to
`@main` for a stable long-term URL (branch refs work but are more
fragile if the branch is ever renamed or deleted).

jsDelivr caches successful responses for a while (so an *update* to an
existing file can take up to ~24h to show everywhere; a *new* file at a
previously-404 path shows up within moments). To force-refresh a stale
file, hit:
`https://purge.jsdelivr.net/gh/RunbotRobot/game2@claude/word-learning-rpg-sghck9/word-art/<WORD>.png`

## Adding a batch

1. Generate/obtain the art (e.g. via Gemini).
2. Crop/matte it to match the existing sprite style, save as
   `word-art/<WORD>.png`.
3. Commit and push to this branch (see `WORD_ART_BASE` above for which
   one is current). That's it — no other code changes needed,
   `loadWordArtInto()` in `index.html` picks it up automatically the
   next time that word is encountered.
