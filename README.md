


# 👾 Alien Invasion Game 👾

## 🛠️ Platforms & Tools Used
- Developed on Windows using Jupyter Lab for code editing and testing
- Python 3.x
- Pygame library


Welcome to Alien Invasion—a fast-paced, retro arcade shooter built with Python and Pygame! Pilot your ship, blast through waves of aliens, and chase the highest score. Can you save Earth from the pixelated invaders?

---

## 🚀 Features
- Smooth ship controls and satisfying bullet action
- Dynamic alien fleet that gets tougher as you progress
- Scoreboard and persistent high score tracking (`high_score.json`)
- Game over, restart, and a Play button for instant action
- Customizable settings for speed, screen size, and more


## 🌟 Coming Soon
- Minor bug fixes and gameplay tweaks
- Improved alien movement and challenge
- More sound effects

# 👾 Alien Invasion Game

Alien Invasion is a classic arcade-style shooter built in Python using the Pygame library. Pilot your ship, blast through waves of aliens, and aim for the highest score! This project demonstrates object-oriented programming, event-driven logic, and basic game design principles.

---

## �️ Platforms & Tools Used
- Developed on Windows
- Jupyter Lab for code editing and testing
- Python 3.x
- Pygame library

## 🚀 Features
- Smooth ship controls and bullet firing
- Alien fleet that moves and increases challenge
- Scoreboard and persistent high score tracking (`high_score.json`)
- Game over, restart, and Play button
- Customizable settings for speed, screen size, and more

## 🌟 Coming Soon
- Minor bug fixes and gameplay tweaks
- Improved alien movement
- More sound effects
- Small UI enhancements

## 🧩 Code Structure & Logic
- The game is organized using object-oriented principles:
  - `Ship`, `Alien`, and `Bullet` classes encapsulate movement, drawing, and collision logic.
  - `Settings` class centralizes all game configuration (speed, screen size, bullet limits, etc.).
  - `GameStats` and `Scoreboard` manage game state, scoring, and display.
  - `Button` class handles UI interactions for starting/restarting the game.
- The main loop in `alien_invasion.py` handles event processing, updates game objects, checks for collisions, and redraws the screen each frame.
- High scores are saved and loaded from `high_score.json` for persistent tracking.
- Sprites for the ship and aliens are stored in the `images/` folder and loaded at runtime.

## 🗂️ Key Files
- `alien_invasion.py`: Main game loop and entry point
- `settings.py`: Game configuration
- `ship.py`, `alien.py`, `bullet.py`: Core gameplay classes
- `button.py`: UI button logic
- `game_stats.py`, `scoreboard.py`: Game state and score display
- `high_score.json`: Persistent high score
- `images/`: Sprites for ship and aliens

## 🎮 How to Play
1. Install Python 3.x and Pygame:
   ```powershell
   pip install pygame
   ```
2. Launch the game:
   ```powershell
   python alien_invasion.py
   ```

## 🕹️ Controls
- **Left/Right Arrow Keys**: Move your ship
- **Spacebar**: Fire bullets
- **Q**: Quit the game

## 🎨 Customization
- Edit `settings.py` for speed, screen size, and more
- Replace images in `images/` for your own style

## 🏆 High Score
- Your best score is saved in `high_score.json`—try to beat it!

---

Made for fun, learning, and endless replay value. Stay tuned for small updates and improvements!
