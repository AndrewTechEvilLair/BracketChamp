# 🏆 BracketChamp

A lightweight, single-file tournament bracket generator built for race events and competitions. No installation, no backend, no build step — just open the HTML file and run your tournament.

https://andrewtechevillair.github.io/BracketChamp/

---

## Features

- **Single & Double Elimination** — run a standard bracket or include a full losers bracket with automatic routing
- **Up to 32 participants** — supports any number from 2 to 32, with BYE slots automatically assigned for uneven fields
- **Custom blank brackets** — generate a blank bracket for any size from 2 to 64 for manual fill-in
- **Random or ranked seeding** — shuffle participants randomly or keep your entered order
- **Grand Final support** — in double elimination, the winners and losers bracket champions automatically meet in a Grand Final
- **Final Standings** — once the tournament is complete, a ranked standings table is generated with 🥇🥈🥉 medals and tied placements (e.g. T-3)
- **Undo** — step back through any match result, one action at a time
- **Export results** — download results as `.txt` (with ASCII bracket diagram), `.csv`, or `.json`
- **Print-ready** — clean print layout with header controls hidden
- **Auto-save** — participant names, tournament name, and settings are saved to local browser storage automatically
- **Dark mode** — toggle between light and dark themes
- **Works offline** — no internet connection required after the page loads (aside from the Buy Me a Coffee button image)
- **Mobile friendly** — touch-optimized buttons with haptic feedback on supported devices

---

## Getting Started

### GitHub Pages / Web Hosting

1. Download `BracketChamp_V1.4.html`
2. Rename it to `index.html`
3. Upload it to your GitHub Pages repository (or any static web host)
4. Done — navigate to your site URL and it's live

### Local Use

Just double-click the `.html` file to open it in any browser. No server needed.

---

## How to Run a Tournament

1. **Enter a tournament name** at the top
2. **Choose your settings:**
   - *Random Seeding* — participants are shuffled before bracket generation
   - *Ranked Seeding* — participants are placed in the bracket in the order you entered them
   - *Include Losers Bracket* — enables double elimination
3. **Add participants** — type each name into the list (up to 32), or click **Test Data** to load sample names
4. **Click Generate Bracket**
5. **Click a participant's name** to declare them the winner of that match — the bracket advances automatically
6. When the final match is reached, a confirmation dialog appears before the result is committed
7. In double elimination, the Grand Final triggers automatically once both bracket champions are decided
8. When the tournament ends, the **Final Standings** modal appears — you can reopen it anytime with the 🏆 Standings button

---

## Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| `Ctrl + Z` | Undo last action |
| `Ctrl + P` | Print bracket |
| `Ctrl + E` | Export results as text |
| `Esc` | Close open modals / dropdowns |

---

## Exporting Results

Click **Export ▾** in the bracket header to download:

- **Text (.txt)** — human-readable summary including final standings, an ASCII bracket diagram, and a match-by-match breakdown per participant
- **CSV (.csv)** — spreadsheet-compatible format with final standings and all race results
- **JSON (.json)** — full bracket data structure, useful for archiving or further processing

---

## Browser Support

Works in all modern browsers — Chrome, Firefox, Safari, Edge. No plugins or extensions required.

---

## Files

| File | Purpose |
|---|---|
| `BracketChamp_V1.4.html` | Self-contained app — rename to `index.html` for deployment |
| `BracketChamp_V1.4.tsx` | React/TypeScript source for development builds |

---

## License

Free to use and share. If BracketChamp saves you time at your event, consider buying me a coffee ☕

[buymeacoffee.com/AndrewTech](https://www.buymeacoffee.com/AndrewTech)
