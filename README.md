# Fun Quest Station

A sleek collection of classic mini‑games with a modern dark UI. Play instantly, no setup. Built with plain HTML/CSS/JS.

## Live Structure

- Home: `funquest/index.html`
- Games:
  - 2048 — `funquest/2048.html` (existing)
  - Tower of Hanoi — `funquest/hanoi.html` (existing)
  - Memory Match — `funquest/card.html`
  - Minesweeper — `funquest/minesweeper.html` (existing)
  - Wordle — `funquest/wordle.html` (existing)
  - Tic Tac Toe — `funquest/tictactoe.html`
  - Flappy Bird — `funquest/flappybird.html`
  - Sudoku — `funquest/sudoku.html`

Icons are unified SVGs under `funquest/img/`.

## Features

- Modern dark theme with subtle animations.
- Icon grid on the homepage with live search.
- Fully client‑side: no frameworks, no bundlers.
- Mobile‑friendly layout.

## Getting Started

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
   ├─ slick/         # (if any legacy assets remain)
   ├─ 2048.html
   ├─ hanoi.html
   ├─ card.html
   ├─ minesweeper.html
   ├─ wordle.html
   ├─ tictactoe.html
   ├─ flappybird.html
   └─ sudoku.html
```

## Develop

- Edit `funquest/index.html` to add/remove game tiles.
- Use the SVG icon style as a template for new games.
- For quick local testing, you can use any static server or just open HTML files directly.

## Deploy (GitHub Pages)

1. Initialize Git and push to GitHub (see commands below).
2. On GitHub, go to Settings → Pages → Source = "Deploy from a branch".
3. Select `main` and `/ (root)` (or `/funquest` if you want to serve from that folder).
4. Save. GitHub Pages will publish your site in a few minutes.

## Git Commands

```powershell
# from the project root folder (FUN QUEST STATION)
 git init
 git add .
 git commit -m "Initial commit: Fun Quest Station"
 git branch -M main
 git remote add origin https://github.com/<your-username>/fun-quest-station.git
 git push -u origin main
```

## License

Specify a license if you want others to reuse the code (e.g., MIT). Create a `LICENSE` file with your chosen license text.
