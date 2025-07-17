# Alien Invasion Game
A thrilling 2D space shooter built with Python and Pygame. Pilot your ship, fend off alien waves, rack up points—and survive as long as you can!

## 🚀 Table of Contents
- [Game Overview](#game-overview)
- [Features](#features)
- [Screenshots](#screenshots)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Game](#running-the-game)
- [Controls](#controls)
- [Code Structure](#code-structure)
- [How It Works](#how-it-works)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)

## Game Overview
Welcome to *Alien Invasion Game*—a classic arcade-style shooter inspired by the *Python Crash Course*. Fight off endless waves of aliens, level up, and defend your spaceship!

## Features
- **Dynamic difficulty**: Each level increases alien speed and count
- **Scoring system**: Track current score, high score, and level
- **Lives system**: Start with multiple ships; game ends after losing all
- **Clean graphics**: Simple sprites for smooth gameplay
- **Designed with OOP**: Modular code for ship, bullets, aliens, etc.

## Screenshots
*You can insert gameplay screenshots here to showcase combat, scoreboards, and visuals.*

## Getting Started

### Prerequisites
- Python 3.6+
- Pygame (`pip install pygame`)

### Installation
```bash
git clone https://github.com/Adheesh49/Alien-Invasion-Game.git
cd Alien-Invasion-Game
pip install pygame

Running the Game
bash




python alien_invasion.py
Controls

Action	Keys
Move Left	← (Left Arrow)
Move Right	→ (Right Arrow)
Shoot Bullet	Spacebar
Quit Game	Q
Code Structure
text


Alien-Invasion-Game/
├── alien.py          # Alien class & behavior
├── ship.py           # Player ship with movement & collision
├── bullet.py         # Bullet creation and movement
├── game_stats.py     # Tracks scores, levels, lives
├── scoreboard.py     # Displays game info on screen
├── settings.py       # Screen, speed, and color settings
├── button.py         # Start/play button functionality
└── alien_invasion.py # Main game loop & event handling
How It Works
Initialization: Load game settings, window, sprites
Main loop:
Handle player input
Update positions: ship, bullets, aliens
Detect collisions: bullet-alien, alien-ship, alien-bottom
Refresh screen & display stats
Progression: Clear wave ➝ next level spawns faster aliens
Game Over: Lose all lives ➝ stop & optionally restart
Future Enhancements
🎁 Power-ups: Shields, rapid-fire, multi-bullets
🌟 Boss levels: Introduce enemy types with unique behaviors
👥 Multiplayer mode: Co-op or competitive play
🎨 UI polish: Menus, sound FX, and animations
Contributing
Love the game? Want to help?

Fork the repo
Create a feature branch (git checkout -b feature-awesome)
Commit your enhancements
Push to your fork
Open a Pull Request
License
License details to be added.