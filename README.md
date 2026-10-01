# 🥷 Naruto Dojo Typing

**Jutsu Typing Dojo** is a browser-based anime-inspired typing game where you defeat approaching ninja enemies by accurately typing their jutsu names before they cross the danger line.

> A lightweight front-end project built with vanilla HTML, CSS, and JavaScript — no frameworks, build tools, or dependencies required.

## ✨ Features

- 🥷 Five-lane ninja battlefield
- ⚡ Difficulty increases as your rank improves
- 🏆 Rank progression: **Genin → Chunin → Jonin → Kage**
- 🔥 Combo multiplier for consecutive hits
- ❤️ Three-life system
- 💥 Screen shake feedback for mistakes and missed enemies
- 💾 Best score and recent fight history stored with `localStorage`
- 🌓 Light/dark theme based on the system preference
- ⌨️ Keyboard-focused gameplay
- 📦 Single-file application with zero external runtime dependencies

## 🎮 How to Play

1. Open the game and press **Begin** or `Enter`.
2. Type the first letter of an enemy's jutsu to target that ninja.
3. Finish typing the complete jutsu name to defeat the target.
4. Press `Esc` to drop the current target.
5. Wrong keys reset the combo.
6. If an enemy reaches the red line, you lose a life.

**Tip:** Accuracy and maintaining your combo are key to reaching the higher ranks.

## 🚀 Run Locally

No installation is required. Simply open `index.html` in a modern browser.

For a local development server:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## 🌐 Deploy with GitHub Pages

1. Open the repository **Settings**.
2. Select **Pages**.
3. Choose **Deploy from a branch**.
4. Select the `main` branch and `/ (root)`.
5. Save and wait for GitHub Pages to publish the site.

## 🛠️ Tech Stack

- **HTML5** — page structure
- **CSS3** — responsive anime-inspired interface and animations
- **Vanilla JavaScript** — game engine, keyboard input, scoring, ranks, and persistence
- **Web Storage API** — local score/history persistence

## 🔮 Future Scope

- Sound effects and background music
- More jutsu and enemy types
- Naruto-inspired boss battles
- Difficulty selection
- Online leaderboard
- Player profiles and achievements
- Mobile/touch-friendly input mode
- Separate frontend/backend architecture for persistent accounts

## 📁 Project Structure

```text
NARUTO-DOJO-typing/
├── index.html
├── README.md
├── LICENSE
└── .gitignore
```

## ⚠️ Disclaimer

This is a fan-made educational/portfolio project inspired by the Naruto universe. It is not affiliated with or endorsed by the copyright/trademark owners of Naruto.

## 📄 License

Released under the [MIT License](LICENSE).
