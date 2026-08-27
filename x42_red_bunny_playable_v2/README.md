# X42 Red Bunny — Playable One-Sheet Demo v2

Open `index.html` in a browser.

## Fixed
The Bunny animation frames are normalized to the same transparent canvas and bottom-center anchor. This prevents the previous double/ghosting/sideways-shift effect when frames change.

## Playable
- Walk with on-screen D-pad or arrow keys.
- Meet Mika and advance dialogue.
- Fight the NETWORK Hunter with Attack and Skill.
- Reset the encounter.
- Switch between all six stage/background presets shown on the master sheet.
- Upload a custom background.
- Edit the story/dialogue.
- Browse every major section of the master sheet.

## One-sheet coverage
The editor exposes: characters, enemies, equipment, accessories, skills/effects, stages, objects, UI/elements, tiles/props, NPCs, vehicles/drones and item icons. Representative gameplay assets are extracted from the sheet for the fight/NPC/stage demo.

## Important architecture
`one_sheet.png` is artwork/source; `manifest.json` is stable semantic data. A future production engine should preserve IDs/anchors when AI redesigns the art.
