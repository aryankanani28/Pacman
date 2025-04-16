# Pacman in Python with PyGame

A minimal implementation of the classic **Pacman** game using **Python** and **PyGame**. This version includes a single level with pre-programmed ghost paths and basic gameplay mechanics.

![Pacman Screenshot](images/screenshot.png)

## Features

- Single-level gameplay
- Predefined ghost movements (no AI)
- Basic collision detection
- Background music and sound effects
- Simple and clean codebase for learning purposes

## Getting Started

### Prerequisites

- Python 3.2 (32-bit)
- PyGame 1.9

> **Note:** This project was tested with Python 3.2 (32-bit) and PyGame 1.9. Compatibility with newer versions may vary.

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/hbokmann/Pacman.git
   cd Pacman
   ```

2. **Install PyGame:**

   ```bash
   pip install pygame
   ```

3. **Run the game:**

   ```bash
   python pacman.py
   ```

Alternatively, you can download the Windows executable:

- [Download pacman.exe](https://github.com/hbokmann/Pacman/blob/master/pacman.exe)

## Controls

- **Arrow Keys**: Move Pacman
- **ESC**: Exit the game

## Project Structure

```
Pacman/
├── images/             # Game assets (sprites, icons)
├── pacman.py           # Main game script
├── pacman.mp3          # Background music
├── pacman.ico          # Game icon
├── pacman.exe          # Windows executable
├── freesansbold.ttf    # Font file
└── README.md           # Project documentation
```

## Future Development

- Implement AI for ghost movements
- Add multiple levels
- Enhance game design and graphics
- Improve wall collision algorithms

## License

This project is open-source and available under the [MIT License](LICENSE).

## Acknowledgments

- Inspired by the classic Pacman arcade game
- Developed by [Hans Bokmann](https://github.com/hbokmann)

---

Feel free to fork the project, contribute, or modify it for learning purposes!
