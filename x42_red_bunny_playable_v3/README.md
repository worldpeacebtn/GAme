# X42 Red Bunny — Playable One-Sheet Showcase v3

Open `index.html`.

## This version fixes the central problem
The master sheet is NOT swapped in and out as the character animation.

Instead:
1. C01 is sourced from the one-sheet.
2. It is normalized onto a fixed 260×360 transparent canvas.
3. Every animation has its own frame PNGs.
4. Every frame shares the same bottom-center pivot.
5. The game changes `C01_idle_00.png` → `C01_idle_01.png` etc. frame-by-frame.

Animations included:
- idle: 6 frames
- walk: 6 frames
- attack: 6 frames
- hit: 4 frames

## Playable showcase
- Mobile joystick + game buttons
- Keyboard arrows
- Map switching
- Upload your own background
- NPC meeting / dialogue
- Combat against NETWORK Hunter
- Attack + Network Jam
- Equipment switching
- Master sheet viewer
- Runtime animation atlas viewer
- Story editor

The other sheet-derived categories are surfaced through the in-game Assets tab.

## Important production principle
The visual master sheet is an art source, not a runtime sprite frame. Stable IDs and frame metadata belong in `manifest.json`.
