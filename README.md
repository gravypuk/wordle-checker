# Word Game Checker 🟩

Single-page web app for checking Wordle, Parkrundle, and other word game feedback — accurately.

Born from too many mistyped `b`/`y`/`g` shorthand entries killing Eli's Wordle games.

## Features

- **Tap-to-cycle tiles** — tap each letter to cycle ⬛ → 🟨 → 🟩 (no more typos)
- **Text shorthand mode** — type `bbgyg` if you prefer
- **1–12 letter support** — Wordle (5), Parkrundle (any length), whatever
- **Auto letter count** — adjusts when you type a longer guess
- **Copy shorthand** — one tap to copy `bbgyg` for chat
- **Copy emoji grid** — copy all rows as emoji blocks
- **Delete rows** — remove mistakes
- **Zero dependencies** — single HTML file, works offline

## Deploy

Upload `index.html` to any static host. That's it.

For Cloudflare Pages:
1. Push to GitHub
2. Connect repo in Cloudflare Pages
3. Build command: (none needed)
4. Output directory: `/`

## Usage

1. Pick letter count (or just start typing — it auto-adjusts)
2. Type your guess word
3. Tap tiles to set feedback colours, or switch to text mode and type `bbgyg`
4. Hit "Add row"
5. Copy shorthand to send to your opponent

## Why

Because Graham kept accidentally eliminating letters that were actually in the answer, and it was costing Eli games. The Wordle Commission demanded better tooling. 🐑🧹

## License

MIT
