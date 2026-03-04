# Scrabble_Tracker_For_Mum_and_Dad
# Scrabble Score Tracker

A retro, elegant, and *offline-first* web app for tracking Scrabble (or any word game) scores across multiple games and teams — **all in a single, portable HTML file**.

![App Screenshot](./screenshot.png) <!-- *(Optional: Add screenshot!)* -->

---

## ✨ Features

- **Cozy Board-Game Aesthetic:**  
  Warm cream parchment, wood grains, deep greens, display serif fonts — for a classic tabletop vibe.
- **Local Persistence:**  
  All data saved in your browser. No server needed — works offline and fully private.
- **Multi-Team Support:**  
  Track 1–4 teams per game. Edit scores round-by-round.
- **Easy Navigation:**  
  - Start new game (with unique date)
  - Add scores to existing, active games
  - End any incomplete game and see final rankings
  - Browse all past results with winner highlights
- **Smart UI:**  
  - Responsive, mobile-friendly design
  - Animated Scrabble tile bar for extra charm
  - All validation and errors shown inline (no popups!)

---

## 📝 Data Storage

- All games and scores saved in **localStorage** under the key `scrabbleGames`.
- Data persists between browser sessions and works *completely offline*.
- No data leaves your computer.  
  (To migrate or backup scores, copy `localStorage["scrabbleGames"]`.)

---

## 🚀 How To Use

1. **Download the `index.html` file** and double-click to open in your browser.  
   Or host it anywhere as a static file.
2. **Use the big clear buttons** to start games, add scores, finish games, or review results.
3. **No installation, no login.** All you need is a browser.

---

## 🖥️ Screens

- **Home:**  
  Animated retro Scrabble tile bar, big buttons for all operations.
- **Start Game:**  
  Pick date, enter up to 4 team names, add as needed. Prevents duplicate dates/names.
- **Add Score:**  
  Choose game & team, enter points, and scores will accumulate.
- **End Game:**  
  Mark any open game as "ended" — instantly see final, sorted results with a gold-highlighted winner.
- **Past Results:**  
  Browse results for all completed games, latest first, with ranks and winner badge.

---

## 🎨 Design Choices

- **Fonts:**  
  [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) for headings, [Lora](https://fonts.google.com/specimen/Lora) for body
- **Color palette:**  
  Cream background, wood browns, deep forest green, warm tile yellows/golds.
- **Aesthetic:**  
  Evokes classic board game nights — cozy, tactile, old-school.

---

## ⚙️ Tech

- **Vanilla HTML, CSS, JS**  
  - No frameworks, toolchains, or dependencies.
  - All views are single-page (show/hide logic, CSS transitions).
- **Offline/Local Only**  
  - Compatible with modern browsers on desktop & mobile.

---

## 🛟 FAQ / Tips

- **Q:** *How do I clear all games and scores?*  
  **A:** Open browser dev tools, type: `localStorage.removeItem('scrabbleGames')`, then refresh.
- **Q:** *How do I export/migrate my data?*  
  **A:** Copy-paste value of `localStorage["scrabbleGames"]` to save elsewhere.
- **Q:** *Can I use this for other games?*  
  **A:** Yes! You can track scores for any team/round-based game.

---

## 📜 License

MIT — use, remix, or adapt as you wish.

---

### Made for lovers of tactile game nights, friendly rivalry, and great words.  
Enjoy!
