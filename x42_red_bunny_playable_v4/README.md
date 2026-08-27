# X42 Red Bunny — One-Sheet Handheld Demo v4

This version changes the core behavior:

- Starter menu is fullscreen.
- Gameplay is a contained handheld-style viewport with a fixed 320×180 logical design.
- The master one-sheet is the source of truth.
- Red Bunny runtime animation samples the individual C01 cells directly from the main-character strip and uses fixed transparent frames with a common pivot.
- The whole sheet is never swapped in as the Bunny sprite.
- Idle / Walk / Run / Attack 1 / Attack 2 / Dash / Hit / Death are distinct frame sequences.
- Scene changes happen by running to the edge or choosing a map.
- Mika, the NETWORK Hunter, weapons, skill effects, objects, items and vehicles are all unpacked from the same sheet and exposed in the demo.
- Equipment can be changed while playing.
- Combat buttons trigger actual attack animation sequences.
- The ALL tab shows sheet-derived runtime assets.
