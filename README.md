# 🎮 Tetris Game in C++

A simple **console-based Tetris game built using C++**. The game features randomly generated Tetris pieces, piece rotation, collision detection, automatic falling, line clearing, and score tracking.

## 📌 Features

- **Seven Classic Tetris Shapes:** I, O, T, S, Z, J, and L.
- **Real-Time Controls:** Move and rotate pieces while playing.
- **Automatic Falling:** Pieces move downward automatically.
- **Collision Detection:** Prevents pieces from moving through walls or locked blocks.
- **Line Clearing:** Completed rows are removed from the board.
- **Score System:** Earn 100 points for each completed row.
- **Game Over Detection:** The game ends when a new piece cannot be placed.
- **Cross-Platform Support:** Includes separate input and console-handling code for Windows and Unix-like systems.

## 🛠️ Technologies Used

- **Language:** C++
- **Libraries:** `iostream`, `cstdlib`, `ctime`
- **Platform-Specific Libraries:**
  - Windows: `conio.h`, `windows.h`
  - Linux/macOS: `termios.h`, `unistd.h`, `sys/select.h`

## 🎮 Controls

| Key | Action |
|---|---|
| `A` | Move piece left |
| `D` | Move piece right |
| `W` | Rotate piece |
| `S` | Move piece down faster |
| `Esc` | Quit the game |

## ⚙️ Requirements

- A C++ compiler supporting modern C++.
- A terminal or command-line interface.
- Windows, Linux, or macOS with the appropriate terminal support.

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone <your-repository-url>
cd <your-project-folder>
```

Replace the placeholders with your actual repository URL and project folder name.

### 2. Compile the Code

**Using g++ on Windows:
