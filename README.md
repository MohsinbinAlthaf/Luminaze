# Luminaze

A 2D puzzle maze game built in Unity where you navigate a ball through
increasingly difficult levels. Each level introduces new mechanics — shrinking
to fit through tight gaps, avoiding moving enemies, collecting keys to unlock
doors, and reaching the exit.

## Gameplay

| Action | Key |
|---|---|
| Move Up | W / ↑ |
| Move Down | S / ↓ |
| Move Left | A / ← |
| Move Right | D / → |

## Features

- **Size transformation** — special boxes shrink or expand the ball to solve
  path puzzles
- **Enemies & obstacles** — moving monsters and interactive elements that block
  your way
- **Key-based progression** — collect a key to unlock the exit, finish a level
  to unlock the next
- **Pixel art UI** — fully custom assets with a consistent dungeon aesthetic
- **Sound & transitions** — audio feedback and smooth scene changes

## Structure

Main Menu → Level Select → Level → (repeat)

Completed levels unlock the next. Locked levels stay locked until you've
cleared the one before it.

## Getting Started
```bash
git clone https://github.com/MohsinbinAlthaf/Luminaze
```

Open the project in Unity, load the main scene, and hit Play.

## Built With

- Unity (2D)
- C#
- Custom pixel art assets

## Planned

- More levels with harder layouts
- Smarter enemy behavior
- Power-ups
- Mobile support
- Leaderboard

## License

Open-source — add your preferred license here (MIT, GPL, etc.)
