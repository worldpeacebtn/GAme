# X42 Red Bunny — One-Sheet Playtest

This version is intentionally small and usable.

Open `index.html` in a browser.

## What works
- A Red Bunny character rendered from a frame extracted from the supplied one-sheet.
- Three idle frames cycle automatically.
- Walk around with the on-screen D-pad or keyboard arrows.
- Upload any image as the stage background.
- Edit the dialogue directly in the in-game editor.
- Browse the one-sheet and semantic asset IDs.
- Simple attack/skill/story actions.
- Mobile-friendly edge buttons.

## Design rule
The master visual sheet and the manifest are separate:
- `assets/one_sheet.png` = artwork/source atlas
- `manifest.json` = stable semantic IDs and game relationships

This is the intended foundation for the full engine: artwork can be replaced or redesigned without rewriting the game's story and logic.

## Note
The current bunny frames are extracted from the supplied demo sheet and have been lightly background-separated. A final art pack should use clean transparent anime frames produced specifically for the atlas, with exact pivots and frame boundaries.
