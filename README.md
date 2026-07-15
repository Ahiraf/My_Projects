<div align="center">

# 🎮 Game 2048

**A console-based implementation of the classic 2048 game, built in C++.**

Tile merging, random tile spawns, and win/lose detection — the full 2048 core
in a single, well-structured C++ file.

[![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)](https://isocpp.org)
[![Platform](https://img.shields.io/badge/Platform-Console-546E7A?style=for-the-badge)](#-getting-started)

![winning-2048](https://github.com/user-attachments/assets/38ad33ca-a3e2-480e-bec8-f06687c0c1c0)

</div>

---

## 🎥 Gameplay Demo

**[▶️ Watch the 2048 gameplay in action](https://youtu.be/GRJFz3mAGac)**

---

## ✨ Features

![2048 Mechanics](https://img.shields.io/badge/2048_Mechanics-EDC22E?style=flat-square) &nbsp; Tile merging, random population, and boundary checks.

![Win / Loss](https://img.shields.io/badge/Win_/_Loss_Detection-0F9D58?style=flat-square) &nbsp; Detects a win at 2048 and a game-over when no moves remain.

![Random Tiles](https://img.shields.io/badge/Random_Tiles-4C78A8?style=flat-square) &nbsp; Spawns a 2 or 4 in an empty cell after each valid move.

![Interactive](https://img.shields.io/badge/User_Interaction-546E7A?style=flat-square) &nbsp; Reads moves from input and gives feedback on invalid moves.

---

## 🕹️ How to Play

The game starts with a **4×4 board** and two random tiles (2 or 4). Move tiles with:

| Key | Move |
| --- | ---- |
| `U` | Up |
| `D` | Down |
| `L` | Left |
| `R` | Right |

Tiles with the same value merge and double when pushed together. The game ends when:

- A **2048** tile is reached → **You Win! 🎉**
- No valid moves remain → **Game Over 😢**

---

## 🚀 Getting Started

**Prerequisites** — a C++ compiler (macOS: `xcode-select --install`; Windows:
MinGW-w64 / MSYS2 / Visual Studio).

```bash
# 1. Clone
git clone https://github.com/Ahiraf/Game_2048.git
cd Game_2048

# 2. Compile
g++ -std=c++17 -o game2048 Game_2048.cpp

# 3. Run
./game2048            # Windows: game2048.exe
```

---

## 🛠️ Code Structure

Everything lives in a single `Game2048` structure:

- **Setup** — `init()`, `random_populate()`, `printboard()`
- **Moves** — `up()`, `down()`, `left()`, `right()`
- **Game logic** — `has_game_ended()`, `has_won()`, `move_end()`

---

## ❤️ Acknowledgements

Inspired by the original [2048 game](https://2048game.com/). Enjoy! 🚀
