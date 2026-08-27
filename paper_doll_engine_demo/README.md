# Paper Doll Engine — Red Bunny / St Paulianisches Bermuda-Dreieck demo

Open `index.html` locally in a browser.

## Included
- `index.html` — standalone editor prototype
- `assets/red_bunny_atlas.svg` — editable vector demo atlas
- `assets/atlas.json` — atlas + semantic asset IDs
- `assets/character_C001.json` — complete one-page character data
- `assets/project.json` — project/preset example

## Core design
The engine treats art as an atlas plus metadata. The editor, command pad, presets and future AI assistant all modify the same data model.

## AI integration
The UI includes an OpenAI / Google Gemini provider selector and an API-key field as a prototype interface. The demo intentionally does NOT transmit keys. For production, put provider calls behind a backend/serverless function and return structured JSON commands.

## AI/design workflow
Because the demo atlas is SVG, another AI/design tool can edit the source vector asset and keep the same semantic IDs/grid. The long-term engine should export/import PNG + JSON, SVG + JSON, and engine-specific formats.

## Fiction
Red Bunny is a fictional cyber-expert whistleblower hiding in the fictional "St Paulianisches Bermuda-Dreieck" while being hunted by the NETWORKS. The visual language uses a red/black/white underground Hamburg-inspired poster aesthetic without relying on official club logos.
