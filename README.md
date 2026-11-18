# SquGameGodot

SquGameGodot is a 2D platform game created with **Godot 4.5**. This is a personal first-game project featuring coin collection, platforming, moving platforms, enemies, and character movement.

## Features

- Character movement, jumping, and dashing
- Animated player and slime enemies
- Coin collection and score tracking
- Static and animated platforms
- Kill zones and scene restart behavior
- Pixel-art assets and ambient music

## Controls

| Action | Keyboard | Gamepad |
|---|---|---|
| Move left | A / Left Arrow | D-pad Left / Left Stick |
| Move right | D / Right Arrow | D-pad Right / Left Stick |
| Jump | Space | South Button |
| Dash | — | Right Trigger |

## Requirements

- [Godot Engine 4.5](https://godotengine.org/download/) or a compatible newer 4.x release

## Run the game

1. Clone the repository:

   ```bash
   git clone https://github.com/jvarshini99/SquGameGodot.git
   cd SquGameGodot
   ```

2. Open Godot Engine.
3. Select **Import** and choose `project.godot`.
4. Open the project and press **F6** or use **Run Current Scene**.

The main scene is configured in `project.godot` as `scenes/game.tscn`.

## Project structure

```text
assets/       Sprites, fonts, music, and other game assets
scenes/       Godot scenes for the player, enemies, level, and objects
scripts/      GDScript gameplay logic
project.godot Godot project configuration
```

## Main gameplay scripts

- `scripts/player.gd` — player movement, jumping, dashing, and animations
- `scripts/killzone.gd` — death behavior and level restarting
- `scripts/slime.gd` — basic enemy patrol movement
- `scripts/game_manager.gd` — coin score tracking

## Contributing

Issues and pull requests are welcome. Please create a focused branch for each change and test the game in the Godot editor before submitting.

## License

No license is currently specified. Add a `LICENSE` file if you want to define how others may use or contribute to this project.
