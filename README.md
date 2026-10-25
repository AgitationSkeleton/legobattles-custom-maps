# LEGO Battles custom maps

Maps for the LEGO Battles PC port (a recompiled build of the Nintendo DS game), curated by the port project. Each pack is a zip in the shape the port's Maps browser reads: `<pack>/<map folder>/<files>`. A map folder holds the `.map`, its four minimap files (`mini.NCGR`, `mini.NCBR`, `miniNT.NCGR`, `miniNT.NCBR`), optionally a `DetailTiles_<name>.tbp`, a reference `.png` and a short `.txt` saying what the map is and what was invented.

## Packs

### Mars beta maps
Six cut campaign maps (Mars 1-2, Mars 1-5, Mars 2-4, Mars 3-3, Human 1-4, Human 2-2). Only their minimap pictures survive, in the LEGO Castle prototype. The terrain was reconstructed from those pictures on the Mars tileset; start positions, units, gold bricks, mines and AI markers are invented (each map's `.txt` lists exactly what). All six are 96x96, 3 to 4 players, and playable in Free Play.

### Prototype Free Play maps
Free Play maps from the LEGO Castle and LEGO Pirates prototypes that differ from the final game's map in the same slot. The two prototypes ship identical Free Play maps, so each appears once, named `<final name> (Proto)`. Maps that match the final game apart from a handful of trees are left out (Entrenched, King's Landing, The Divide, The Junction, Crossover, Tri-Star, Dryside, Dark Waters, Lost Lagoon, Pulsar, Devil's Horn, Crossed Island, Proving Grounds, Ruthless).

| Map | Slot | Differences from the final game |
|---|---|---|
| The Pond (Proto) | 1 | terrain: 13 ground-type cells and 28 tile cells differ; trees: 4 cells differ (touch-ups only); no gold bricks (retail adds 10) |
| Avast (Proto) | 3 | terrain: 64 ground-type cells and 67 tile cells differ; trees: 4 cells differ (touch-ups only); no gold bricks (retail adds 10) |
| River Crossing (Proto) | 4 | a different map from the retail one in this slot (64x64 here, 96x96 in retail) |
| Exile (Proto) | 5 | terrain: 0 ground-type cells and 1 tile cells differ; trees: 110 cells differ; no gold bricks (retail adds 10) |
| Alpha Sector (Proto) | 6 | trees: 14 cells differ; no gold bricks (retail adds 10) |
| Enclave (Proto) | 7 | terrain: 1 ground-type cells and 9 tile cells differ; trees: 3 cells differ (touch-ups only); no gold bricks (retail adds 10) |
| The Black Seas (Proto) | 8 | terrain: 6 ground-type cells and 25 tile cells differ; trees: 4 cells differ (touch-ups only); AI markers differ; no gold bricks (retail adds 10) |
| Omega Quadrant (Proto) | 9 | terrain: 3 ground-type cells and 41 tile cells differ; trees: 8 cells differ (touch-ups only); no gold bricks (retail adds 10) |
| The Bayou (Proto) | 11 | terrain: 23 ground-type cells and 25 tile cells differ; trees: 4 cells differ (touch-ups only); start bases and units are placed differently; AI markers differ; no gold bricks (retail adds 10) |
| Dead End (Proto) | 12 | terrain: 3 ground-type cells and 27 tile cells differ; trees: 3 cells differ (touch-ups only); no gold bricks (retail adds 10) |
| The Groves (Proto) | 13 | trees: 3 cells differ (touch-ups only); start bases and units are placed differently; no gold bricks (retail adds 10) |
| Le Poisson (Proto) | 14 | terrain: 3 ground-type cells and 27 tile cells differ; trees: 4 cells differ (touch-ups only); no gold bricks (retail adds 10) |
| The North Lands (Proto) | 16 | terrain: 134 ground-type cells and 245 tile cells differ; trees: 77 cells differ; start bases and units are placed differently; no gold bricks (retail adds 10) |
| Outbreak (Proto) | 18 | terrain: 237 ground-type cells and 701 tile cells differ; trees: 8 cells differ (touch-ups only); mines: 5 here, 3 in retail; AI markers differ; no gold bricks (retail adds 10) |
| Kahuka's Strait (Proto) | 26 | terrain: 54 ground-type cells and 162 tile cells differ; trees: 5 cells differ (touch-ups only); no gold bricks (retail adds 10) |
| The Dead Marsh (Proto) | 29 | terrain: 28 ground-type cells and 41 tile cells differ; no gold bricks (retail adds 10) |

The prototype's maps are unchanged apart from format: its marker records are one byte narrower than the final game's, so each marker gained the trailing byte. The prototype has no gold-brick event; none was added.

### Ninjago Free Play maps
The 22 Free Play ("Battle Mode") maps of LEGO Battles: Ninjago that fit the format (Battle Mode Map 08 is a 48x48 map and is left out), converted to the retail format. Ninjago draws its tiles in a different isometric view, so the tile layer is rebuilt from the maps' own terrain pictures on the retail Pirate (jungle), King (snow) and Mars (volcano, underworld, cave) tilesets. Starts, mines and decorations follow the Ninjago maps; each map's `.txt` says what was invented. All are 96x96 and 2 players: the stock game lists only maps with 3 or more starts, so these need the port's 2-player map list.

## Using the maps

- **By hand.** Extract a pack and put the map folders under `mods/maps/` next to the game. They show in the Free Play map list after the stock maps (at most 30 mod maps are listed).
- **Through the port.** Open Tools > Maps and pick a map from the list; the port downloads it into `mods/maps/`.

## Sources and credit

- The prototype maps and the cut-map minimap pictures come from the LEGO Castle and LEGO Pirates prototype builds; the Ninjago maps from LEGO Battles: Ninjago.
- The map format and minimap rules were worked out by the LEGO Battles modding community and the port project.

## More to come

Battle Mode Map 08 and Ninjago's story maps may follow.
