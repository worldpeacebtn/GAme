# X42 One-Sheet Demo Game

Open `index.html` in a browser.

## What this demonstrates
- One master 2048×2048 visual sheet as the demo asset source.
- A semantic JSON manifest separating asset IDs from artwork.
- Automatic starter-game assembly.
- Mobile-first HUD with edge/app buttons.
- Scene/stage switching.
- Character quick-definition editor.
- Story/dialogue editor.
- Asset library.
- One-sheet import.
- Project JSON export.
- Playable movement, dialogue, attack and skill buttons.

## Intended next step
Replace the demo's simple character placeholder with a real transparent anime sprite atlas using the same semantic manifest. The editor can then render animation frames by coordinates and layer paper-doll parts.

## AI art workflow
Give another art model the `one_sheet.png` and `one_sheet_manifest.json` together and instruct it to preserve IDs, grid, frame order, pivots and transparent areas while restyling the artwork.

## Security
A production AI integration should use a backend/serverless proxy; never ship production provider API keys inside browser JavaScript.
