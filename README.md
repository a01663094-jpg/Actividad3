# Modified Pacman Game - Python Project

## General Description

This project consists of modifying the Pacman game from the Python freegames package. The main objective was to understand the original code and implement new required features related to board design, ghost speed, and smarter ghost movement.

The game was tested and modified using Python, Turtle Graphics, Git, GitHub, and WSL Ubuntu.

---

# Original Game

The original Pacman game was copied using the following command:

freegames copy pacman

---

# Required Modifications

The activity required the following changes:

1. The ghosts must be smarter.
2. The game board must be changed.
3. The ghosts must move faster.

---

# Changes Made

The following modifications were implemented:

- The original board layout was changed by modifying the `tiles` list.
- The new board creates a different path structure and changes the gameplay experience.
- The ghosts movement speed was increased by modifying the internal game timer and movement refresh rate, making the gameplay more dynamic and challenging for the player during longer matches.
- A smarter ghost movement system was implemented.
- The ghosts now analyze valid movements and try to move closer to Pacman.
- The code was documented with comments and function descriptions.

---

# Smart Ghost System

A new function called `move_ghost_smart()` was implemented.

This function checks the valid directions available for each ghost and chooses the movement that reduces the distance between the ghost and Pacman. This makes the ghosts behave more intelligently compared to the original version.

---

# Controls

- Right arrow = move right
- Left arrow = move left
- Up arrow = move up
- Down arrow = move down

---

# Technologies Used

- Python 3
- Turtle Graphics
- Freegames
- Git
- GitHub
- WSL Ubuntu
- Nano Editor

---

# Commands Used

Copy the original game:

freegames copy pacman

Run the game:

python3 pacman.py

Git commands:

git add .
git commit -m "Modified pacman game"
git push

---

# Conclusion

The Pacman game was successfully modified according to the required specifications. The board was changed, the ghosts now move faster, and a smarter movement system was implemented so the ghosts can follow Pacman more effectively. The final version was documented and uploaded to GitHub with commit history.

---
## Collaboration Update

Minor documentation improvements and repository review performed from collaborator account.

# Author

Ivan Hernandez
