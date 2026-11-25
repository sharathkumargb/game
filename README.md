# Sharu City Stories

A small, original 3D open-city browser game inspired by the open-world city adventure genre. Explore a fictional coastal city, walk around, find your red car, and complete glowing delivery checkpoints for cash.

## Included files

- `index.html` — game page and user interface
- `style.css` — responsive menus and heads-up display
- `game.js` — full 3D city, player, car, controls, and mission code

The game uses low-poly shapes created in code; it does not use Vice City or other commercial game assets.

## Play it locally

You need an internet connection to load the Three.js library from jsDelivr. From this folder, start a local server:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000` in a desktop browser. Opening the HTML directly as a `file://` page may be blocked by some browsers because the game uses JavaScript modules.

## Publish with GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html`, `style.css`, and `game.js` to the repository root.
3. In the repository, open **Settings → Pages**.
4. Select **Deploy from a branch**, choose `main` and `/ (root)`, then save.
5. Open the Pages URL shown there after deployment finishes.

## Controls

- **W A S D** or arrow keys: walk or drive
- **Mouse:** orbit the third-person view
- **F:** enter or exit the car when nearby
- **Shift:** sprint on foot / boost while driving
- Drive or walk into the gold checkpoint to complete a delivery
- **Esc:** pause and release the mouse

## About this version

This is a single-player browser prototype. It has no accounts, network multiplayer, or server-side systems. Online multiplayer requires a backend, matchmaking, and authoritative game servers. The project is an original small-scale city adventure rather than a copy of Vice City.
