# Vikings Stat Book

Live season stats for the Vikings (Universe Football).

## Add a game
1. After a game, export the stats CSV.
2. Rename it `YYYY-MM-DD vs Opponent.csv` (example: `2026-10-02 vs Colts.csv`).
3. On GitHub, open the `games` folder → **Add file → Upload files** → drop the CSV → **Commit changes**.
4. The site updates within a minute or two.

## Roster / exceptions
Edit `config.json`:
- `roster` — usernames, display names and jersey numbers. Roster players count as Vikings automatically.
- `games` — per-file exceptions, e.g. `"notVikings": ["username"]` when a roster player was on the other team that game.
