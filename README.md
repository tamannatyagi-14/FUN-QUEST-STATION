# Fun Quest Station

A sleek collection of classic mini‑games with a modern dark UI. 100% static, built with plain HTML/CSS/JS.

## Live Demo

 - Live URL: https://tamannatyagi-14.github.io/FUN-QUEST-STATION/
 - Play Now: https://tamannatyagi-14.github.io/FUN-QUEST-STATION/
- Local homepage path: `funquest/index.html`
- When deployed (GitHub Pages via `docs/`), the homepage is served at `/index.html` on the live URL above.

## Games

- 2048 — `funquest/2048.html`
- Tower of Hanoi — `funquest/hanoi.html`
- Memory Match — `funquest/card.html`
- Minesweeper — `funquest/minesweeper.html`
- Wordle — `funquest/wordle.html`
- Tic Tac Toe — `funquest/tictactoe.html`
- Flappy Bird — `funquest/flappybird.html`
- Sudoku — `funquest/sudoku.html`

Icons and images live under `funquest/img/`.

## Features

- Modern dark theme with subtle animations.
- Simple home grid linking to each game.
- Fully client‑side: no frameworks, no bundlers.
- Mobile‑friendly layout.

## Quick Start

1. Clone the repository.
2. Open `funquest/index.html` in your browser.

No build step is required.

## Folder Structure

```
FUN QUEST STATION/
└─ funquest/
   ├─ index.html
   ├─ css/
   ├─ js/
   ├─ img/           # SVG icons and game assets
   ├─ 2048.html
   ├─ hanoi.html
   ├─ card.html
   ├─ minesweeper.html
   ├─ wordle.html
   ├─ tictactoe.html
   ├─ flappybird.html
   └─ sudoku.html
```

## Development

- Edit `funquest/index.html` to add/remove game tiles.
- Use the same CSS classes/components to keep the UI consistent.
- For quick local testing, you can use any static server or just open HTML files directly.

## Deploy

### Option A: GitHub Pages (free)

GitHub Pages can publish only from the repository root (`/`) or a `docs/` folder.

Pick one of these approaches:

1) Serve from root
   - Move everything inside `funquest/` to the repository root so that `index.html` sits at `/index.html`.
   - On GitHub: Settings → Pages → Source = Deploy from a branch → Branch = `main`, Folder = `/ (root)`.

2) Serve from `docs/`
   - Rename or move the `funquest/` folder to `docs/` so that `docs/index.html` exists.
   - On GitHub: Settings → Pages → Source = Deploy from a branch → Branch = `main`, Folder = `/docs`.

Wait 1–2 minutes and your site will be live at:
`https://<your-username>.github.io/FUN-QUEST-STATION/`

### Option B: Netlify (very simple)

- Create a Netlify account → Add new site → Import from Git → pick this repo.
- Build command: none
- Publish directory: `funquest/` (or `docs/` if you used the GitHub Pages approach above)
- Deploy → Netlify will give you a public URL you can share.

## Git Commands

```powershell
# from the project root folder (FUN QUEST STATION)
git init
git add .
git commit -m "feat: initial commit – Fun Quest Station"
git branch -M main
git remote add origin https://github.com/<your-username>/FUN-QUEST-STATION.git
git push -u origin main
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

Choose a license if you want others to reuse the code (e.g., MIT). Create a `LICENSE` file with your chosen license text.
