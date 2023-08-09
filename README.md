# Space Shooter Game

Space Shooter is an arcade-style game where players navigate a spacecraft, shooting down waves of incoming enemy ships. The game is set against the backdrop of the vastness of space, and players must evade enemies and their projectiles while trying to eliminate them. As the game progresses, the intensity and number of enemies increase, challenging the player's skills and reflexes.

This game is developed using the `pygame` library. `pygame` is a cross-platform set of Python modules designed for writing video games. It provides functionalities like creating windows, drawing shapes, capturing mouse events, and playing sounds. With `pygame`, building games in Python becomes a straightforward task.

## Source Code Files

### ships.py

This file contains all the classes related to different types of ships and lasers in the game:

> **Laser**: Represents the laser beam/projectile shot by the ships. <br>
> **Ship**: A general representation of a ship. This class is used as a base for the player and enemy ship classes.<br>
> **Player**: Represents the player's ship. It inherits from the Ship class and has additional functionalities like displaying health bars.<br>
> **Enemy**: Represents the enemy ships. Like the Player class, it also inherits from the Ship class and has its own unique behaviors.<br>

### utilities.py

This file contains utility functions that aid in various operations throughout the game:

> **collide(obj1, obj2)**: A function that checks if two objects (like ships or lasers) collide or overlap.

### constants.py

This file defines several constants and loads assets (images and fonts) for the game:

> Defines **WIDTH** and **HEIGHT** as the game window dimensions.<br>
> Initializes the game window and sets its caption.<br>
> Loads images for different ships and lasers from the assets folder.<br>

### main.py

This is the main driver of the game. It contains the game's main loop and the main menu:

> **main()**: This function contains the primary game loop where events are checked, game entities are updated, and the screen is redrawn.<br>
> **main_menu()**: A function to display the starting screen of the game and to initiate the main game loop when required.<br>

To play the game, simply run the `main.py` file. Navigate your ship, dodge incoming enemy ships, and shoot them down before they get to you. How long can you survive in this interstellar battlefield?
