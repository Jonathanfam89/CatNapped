# CatNapped!

A 2D pixel-art platformer set in the Wild West. Bandits have kidnapped Butter the cat, and you play a cowboy racing to save Butter before the timer runs out. Shoot bandits, dodge cacti and bombs, find the key, and use your lasso to pull crates and swing across gaps.

Team ByteSized made CatNapped! as a project at DigiPen Institute of Technology Singapore in 2024. It is written in C with the [CProcessing](https://github.com/DigiPen-Faculty/CProcessing) framework and uses FMOD for audio.

## Running the game
1. Clone or download this repository.
2. Run `CatNapped.exe`.

Leave `CatNapped.exe`, `CProcessing.dll`, `fmod.dll` and the `Assets/` folder together in the same directory. The game loads its images, sounds and fonts from `Assets/` at runtime and won't start correctly without them.

## Controls

| Action | Input |
| --- | --- |
| Move left / right | `A` / `D` |
| Jump | `Space` |
| Shoot | Left click (aim with the cursor) |
| Switch between gun and lasso | `Q` |
| Pull a brown box | Hold left click on the box with the lasso equipped |
| Hook onto an anchor point | Left click the anchor with the lasso equipped |
| Swing (build momentum) | `A` / `D` while hooked |
| Slow down the swing | `S` |
| Let go of the rope | `Space` |

The first level teaches each of these as you play.

## Gameplay

- **Save Butter in time.** A countdown runs for the whole level. If it hits zero, it's game over.
- **Watch your health.** Cacti and bandits hurt you.
- **Find the key.** You'll need it to get through the level.
- **Use the lasso.** Pull crates out of the way and swing across gaps between anchor points.

## Repository contents

```
CatNapped/
├── CatNapped.exe     # Game executable (Release, x64)
├── CatNapped.pdb     # Debug symbols
├── CProcessing.dll   # CProcessing graphics/input library
├── fmod.dll          # FMOD audio library
└── Assets/           # Sprites, tilesets, music, sound effects and fonts
    └── Fonts/
```

Sprite source files made in [Piskel](https://www.piskelapp.com/) (`*.piskel`) are in `Assets/` with the exported PNGs.

## Credits

**Team ByteSized**

- Caven Koh (Team Leader)
- Kimberly Charlotte
- Kerrin Khoo
- Jonathan Fam

**Instructors:** Ding Xiang Cheng, Gerald Wong

### Third-party assets and libraries

- [CProcessing](https://github.com/DigiPen-Faculty/CProcessing), DigiPen Institute of Technology
- [FMOD](https://www.fmod.com/), Firelight Technologies
- Tilesets from [Kenney's Pixel Platformer](https://kenney.nl/assets/pixel-platformer) (CC0)
- Fonts: ByteBounce, Digital Dream Fat (Jakob Fischer / [pizzadude.dk](https://www.pizzadude.dk), see `Assets/Fonts/pizzadude.dk License.txt`), and [Exo 2](https://fonts.google.com/specimen/Exo+2) (SIL Open Font License)

## License

All content © 2024 DigiPen Institute of Technology Singapore. All rights reserved.
