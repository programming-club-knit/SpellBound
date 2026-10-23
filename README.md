# Spellbound — The Hollow Archive

An atmospheric, browser-based mystery adventure built with React, Vite, and CSS. Explore a forgotten mansion, inspect curious objects, solve four puzzles, and discover what happened to its missing inhabitants.

## Run locally

```bash
npm install
npm run dev
```

Open the local URL printed by Vite. Create a production build with `npm run build`.

## How to play

- Choose rooms from the left navigation or follow the paths beneath each scene.
- Click objects in a room to inspect them and uncover clues.
- Use the **Satchel** and **Clue Journal** to review what you have found.
- Solve the cabinet combination (314), brew the star potion (silverleaf, rainwater, emberroot), decode the library cipher (NORTH), and repeat the chimes (moon, sun, moon, star).
- Once all four trials are solved, enter the Sealed Observatory and inspect the last letter.
- Press **I** for your satchel, **J** for the journal, or **Escape** to close an object.

## Built with

React functional components and hooks, Vite, JavaScript, CSS Grid/Flexbox, and Lucide React icons. The room illustrations are composed from CSS, gradients, and emoji; no remote artwork is required.

## Architecture

- `src/App.jsx` — game shell, room navigation, inventory, journal, puzzles, progress, and object inspection.
- `src/index.css` — responsive dark-fantasy visual system, room illustrations, and reduced-motion support.
- `src/main.jsx` — React entry point.
- `index.html` / `vite.config.js` — Vite setup.

## Contributing — Hack the Web

Pick one of the six published GitHub issues, read its acceptance criteria, and submit a focused pull request. Do not combine unrelated challenges. Run `npm run build` before opening a PR and explain how you tested your change.

Browse the [repository issues](https://github.com/prathmyx/SpellBound/issues) for the live challenge list. Each challenge has a point value; the six challenges total 135 points. See [CONTRIBUTING.md](CONTRIBUTING.md) for workflow and scoring details.

## License

No license has been selected yet. Please open an issue before reusing this project outside the repository.
