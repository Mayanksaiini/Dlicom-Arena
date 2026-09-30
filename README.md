# Colosseum Rift

A browser-based 3D third-person shooter built with three.js (r128, loaded from cdnjs).
Everything (models, textures, sound, music) is generated in code, so the whole game is one file: `index.html`.

## Controls
- WASD move, Shift sprint, Space jump
- Mouse aim, click fire, right-click scope
- R reload, B fire mode (auto/single)
- P or Esc pause, M mute

## Run locally
Open `index.html` in a browser, or serve the folder:

    npx serve .

## Deploy on Vercel
1. Push this folder to a GitHub repository.
2. In Vercel choose "Add New Project", import the repo.
3. Framework preset: "Other". No build command, no output directory.
4. Deploy. Every push to `main` redeploys automatically.
