# Flappy Bird Clone

This repository contains a clone of the popular Flappy Bird game, built using Python and Pygame. This project is a fun way to practice and showcase python and pygame skills.

## Features

- **Interactive Gameplay**: Enjoy the classic Flappy Bird experience where players navigate the bird through obstacles by flapping its wings.
- **Responsive Controls**: Use the `Space` or `Up arrow` keys to flap the bird's wings and navigate through the game.
- **Score Display**: Keep track of your progress with a real-time score display as you navigate through the pipes.
- **Multiple Pipe Obstacles**: Face various challenges with randomly generated pipes in different positions.
- **Sound Effects**: Enhance your gameplay experience with engaging sound effects for wing flaps, points, and collisions.

## Prerequisites

- Python 3.x
- Pygame library

You can install Pygame using pip:

```bash
pip install pygame
```

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/Harshit77715/Flappy-Bird-Game.git
cd Flappy-Bird-Game
```

2. Run the game:
```bash
python main.py
```

## Files

- **flappybird.py**: The main game script.

- **gallery/sprites/**: Directory containing all the game sprites.

- **gallery/audio/**: Directory containing all the game sounds.

## Controls
- Press **Space** or **Up arrow** to flap the bird's wings.

- Press **Escape** to exit the game.

## Game Description

Welcome Screen : The game starts with a welcome screen where the player can see the bird and the background.

Main Game: The player controls the bird, trying to fly between pairs of pipes without hitting them. The game ends if the bird collides with a pipe or the ground.

Score: The score increases as the bird successfully passes through the pipes.
