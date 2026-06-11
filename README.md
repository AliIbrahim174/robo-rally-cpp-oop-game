# Robo Rally — C++ OOP Strategy Game

A C++ strategy-based grid game developed using **Object-Oriented Programming**, custom game logic, and GUI-based interaction.

The project was built as part of the **CMPS102 Programming Techniques** course at Cairo University and focuses on applying OOP concepts in a complete interactive game system.

---

## Overview

Robo Rally is a two-player strategy game where robots move across a grid filled with objects, obstacles, power-ups, and danger zones.

Players use movement commands, interact with grid elements, manage health, and compete to reach the flag before the opponent.

The project demonstrates practical application of:

- C++ programming
- Object-Oriented Programming
- Game logic design
- Grid-based movement systems
- Player interaction mechanics
- GUI-based user interaction
- Modular project structure

---

## My Role

I contributed as part of a 4-member team.

My responsibilities included:

- Implementing core C++ game logic
- Applying object-oriented design principles
- Working on player movement and interaction logic
- Supporting integration between game objects and gameplay flow
- Testing and debugging gameplay behavior
- Collaborating with team members on final project delivery

---

## Key Features

- Two-player robot strategy gameplay
- Grid-based game board
- Design Mode for creating and editing the board
- Play Mode for running the actual game
- Player health system
- Command-based movement system
- Strategic shooting phase
- Workshop upgrades and consumables
- Multiple grid objects and obstacles
- GUI-based interaction

---

## Game Modes

### Design Mode

Design Mode allows users to customize the game grid by adding, editing, or removing game objects.

Supported grid objects include:

- Flag
- Belts
- Water pits
- Danger zones
- Workshops
- Antennas
- Rotating gears

### Play Mode

Play Mode allows two players to compete by controlling robots across the grid.

Players can:

- Move forward
- Move backward
- Rotate left
- Rotate right
- Use commands based on health level
- Interact with board objects
- Use workshops and upgrades
- Fire lasers during the shooting phase
- Try to reach the flag before the opponent

---

## Game Mechanics

| Mechanic | Description |
|---|---|
| Grid System | The game uses a cell-based board for robot movement and object placement |
| Health-Based Commands | Player health affects the number of commands available per turn |
| Obstacles | Objects such as water pits and danger zones affect movement and survival |
| Workshops | Players can repair robots or purchase upgrades |
| Shooting Phase | Robots can shoot lasers when aligned in the same row or column |
| Flag Objective | The first player to reach the flag wins |

---

## Tech Stack

| Category | Tools |
|---|---|
| Programming Language | C++ |
| Main Concept | Object-Oriented Programming |
| Application Type | Strategy Game |
| Interface | GUI-based interaction |
| Course | CMPS102 Programming Techniques |
| Institution | Cairo University |

---

## Project Structure

Update this section according to the final repository files.

Recommended structure:

```text
robo-rally-cpp-oop-game/
  README.md
  src/
    main.cpp
    Game.cpp
    Player.cpp
    Robot.cpp
    Grid.cpp
    Cell.cpp
    GameObject.cpp
  include/
    Game.h
    Player.h
    Robot.h
    Grid.h
    Cell.h
    GameObject.h
  assets/
    images/
  docs/
    project-report.pdf
```

---

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/AliIbrahim174/robo-rally-cpp-oop-game.git
cd robo-rally-cpp-oop-game
```

### 2. Open the project

Open the project using a C++ IDE such as:

- Visual Studio
- Code::Blocks
- CLion
- VS Code with C++ extensions

### 3. Build the project

Build the project from your IDE.

If the project is organized with source files under `src/`, you can compile with:

```bash
g++ src/*.cpp -o robo_rally
```

### 4. Run the game

```bash
./robo_rally
```

On Windows:

```bash
robo_rally.exe
```

---

## Screenshots

Add gameplay screenshots here after uploading them to the repository.

Recommended screenshots:

```text
assets/screenshots/design-mode.png
assets/screenshots/play-mode.png
assets/screenshots/game-board.png
assets/screenshots/player-turn.png
```

Example Markdown:

```md
![Design Mode](assets/screenshots/design-mode.png)
![Play Mode](assets/screenshots/play-mode.png)
```

---

## Course Context

This project was developed for the **CMPS102 Programming Techniques** course at **Cairo University**.

The objective was to build a complete C++ application that applies object-oriented programming concepts in a larger project, rather than using isolated small exercises.

---

## Learning Outcomes

This project helped strengthen my understanding of:

- C++ class design
- Object-oriented programming
- Encapsulation and inheritance
- Game state management
- Debugging larger C++ projects
- Team-based code integration
- Turning requirements into working gameplay logic

---

## Future Improvements

- Add more levels and board layouts
- Improve GUI design
- Add single-player mode
- Add AI opponent logic
- Add save/load game progress
- Improve build documentation
- Add unit tests for core game logic

---

## License

This repository is currently shared for academic and portfolio purposes.

If this project is extended for public reuse, a formal open-source license such as MIT or BSD-3-Clause should be added.
