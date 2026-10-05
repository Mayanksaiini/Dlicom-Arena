# Dlicom Arena

A browser-based 3D third-person arena shooter built with three.js (r128, loaded from cdnjs).
Models, textures, sound and music are all generated in code, so the whole game is one file: `index.html`.

## Features
- Home screen: username, Play, Game Modes (Survival / Boss Rush), Leaderboard, Settings, Controls, How to Play
- Round-based difficulty (Easy, Medium, Harder, Very Hard, Boss Fury, then Nightmare), enemy types that unlock over time
- Multi-phase giant boss with a flamethrower every 5 seconds
- Ammo system (250 reserve, 30-round mag, ammo crates)
- Boss jumps in over the enemy gate with a landing shockwave
- Fire show: torches, flames and smoke on the outer rim
- Enemy pavilion (fortress gatehouse): enemies march out of its gate, the boss leaps from its roof
- Soldier ally pickup from Round 6
- Larger night colosseum with a cheering audience, banners, light beams and an open centre (no logo wall)
- Desktop and mobile (landscape) controls, local leaderboard (localStorage)

## Controls
- WASD move, Shift sprint, Space jump, Q quick 180 turn
- Mouse aim, click fire, right-click scope
- R reload, B fire mode, P pause, M mute
- Touch: left joystick, drag the right side (or drag while holding FIRE) to aim, SCOPE / RELOAD / JUMP / 180 buttons. Landscape only.
- V (or the VIEW button on touch) switches first-person / third-person
- Customize Controls (touch only, in Settings and the pause menu): drag buttons, size sliders, opacity, Save/Reset/Cancel, saved on the device

## Run locally
    npx serve .

## Deploy on Vercel
Import the repo, framework preset "Other", no build command, no output directory.
