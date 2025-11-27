# 🐬 SoLong Project
*And thanks for all the fish!*

## 📝 Overview
Create a small 2D game in C using **MiniLibX**. The project teaches handling textures, sprites, windows, and basic gameplay logic.

## 📖 Project Description
- Program: `so_long`
- A 2D game where the player collects items and escapes the map.
- Map input is a `.ber` file with:
  - `0`: empty space
  - `1`: wall
  - `C`: collectible
  - `E`: exit
  - `P`: player start
- Player moves: **W, A, S, D**
- Game ends after collecting all collectibles and reaching the exit.
- Constraints:
  - Map must be rectangular and enclosed by walls.
  - Must handle invalid maps with proper error messages.
  - Window must respond to ESC key or red cross to exit cleanly.

### Example Map
```
1111111111111
10010000000C1
1000011111001
1P0011E000001
1111111111111
```

## 💡 Key Concepts Learned
- Graphics with MiniLibX (textures, sprites, windows).
- Event handling (keyboard and window events).
- 2D array map parsing and validation.
- Game logic: collectibles, movement tracking, win conditions.
- Memory management and error handling.

## 🛠️ Compilation and Usage
```
make
./so_long map.ber
```
- Bonus ideas:
  - Enemy patrols.
  - Sprite animation.
  - On-screen movement count.
