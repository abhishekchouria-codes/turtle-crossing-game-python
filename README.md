# Turtle Crossing Game

A Python arcade‑style game built with the `turtle` graphics library. The player controls a turtle attempting to cross a busy road filled with cars. Each successful crossing increases the level, speeds up the cars, and raises the challenge. The game ends when the turtle collides with a car.

---

##  Features
- **Player Controls**: Move the turtle upward using the keyboard.  
- **Car Spawning**: Cars appear randomly with different colors and positions.  
- **Collision Detection**: Game ends when the turtle collides with a car.  
- **Level Progression**: Each successful crossing increases difficulty by speeding up cars.  
- **Scoreboard**: Displays the current level and shows “Game Over” when the player loses.  

---

##  Technologies Used
- **Python 3**  
- **Turtle Graphics Library** (for visuals and movement)  
- **Object‑Oriented Programming** (modular classes: `Player`, `CarManager`, `Scoreboard`)  

---

##  Project Structure
turtle-crossing-game-python/
│
├── main.py          # Game loop and setup
├── player.py        # Player class (movement, finish line detection)
├── car_manager.py   # CarManager class (car creation, movement, speed control)
└── scoreboard.py    # Scoreboard class (level display, game over message)
