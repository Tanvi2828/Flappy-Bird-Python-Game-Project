# Flappy-Bird-Python-Game-Project

#### **Project Description**:
This project is a recreation of the classic Flappy Bird game using Python and the Pygame library. The game features a bird that the player controls by clicking to make it "flap" and avoid pipes that come towards it. The objective is to score points by successfully passing through the pipes without hitting them or the ground. 

The game includes simple mechanics such as gravity, collision detection, and score tracking. Additionally, it features a game-over screen with a restart button to allow players to reset the game and try again.

#### **Features**:
- **Flappy Bird Game**: Fly the bird through the pipes and avoid collisions with them or the ground.
- **Collision Detection**: Checks if the bird collides with pipes or the ground and ends the game.
- **Score System**: Track the score based on the number of pipes successfully passed.
- **Gravity and Flap Mechanism**: The bird falls due to gravity and flaps when the player clicks on the screen.
- **Restart Button**: A button appears when the game is over to restart the game.
- **Pipe Generation**: Pipes are generated at random intervals, with a gap between the top and bottom pipes.

#### **Technologies Used**:
- **Python**: Programming language used for the game logic.
- **Pygame**: A Python library used for creating video games. It handles the game window, graphics, and animations.
- **Basic Game Development Concepts**: Includes sprite handling, gravity, collision detection, and user input management.

#### **How to Play**:
1. Press the mouse button to make the bird flap and fly.
2. Avoid the pipes as they come towards you.
3. Try to score as many points as possible by passing through the pipes.
4. If you hit a pipe or the ground, the game will end, and you can restart it by clicking the restart button.

#### **Setup Instructions**:
1. Ensure Python 3.x and Pygame are installed on your machine. If Pygame is not installed, you can install it by running the following command:
   ```bash
   pip install pygame
   ```
2. Download or clone this repository to your local machine.
3. Place the necessary image files (`bg.png`, `ground.png`, `restart.png`, and `bird1.png`, `bird2.png`, `bird3.png`, `pipe.png`) in the same directory as the Python script.
4. Run the script:
   ```bash
   python flappy_bird.py
   ```
5. The game will open in a window, and you can start playing!

#### **Game Controls**:
- **Click on the screen** to make the bird flap and avoid the pipes.
