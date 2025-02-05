# Snake Game

![image alt](https://github.com/WWasilew/Snake/blob/84b7d01d4cff8cb228624600332067f8357bded2/snake/images/Snake_logo.png)

## Overview
This is a classic Snake game implemented in Java using the Swing framework. The game features a growing snake that moves around the screen, consuming apples to increase in length. The game ends when the snake collides with itself or the screen borders. A restart button is available upon game over or victory.

## Features
- Classic Snake gameplay with smooth movement
- Apple spawning at random locations
- Increasing difficulty as the snake grows
- Victory condition when all grid spaces are filled
- Game over screen with a restart button
- Simple and intuitive controls

## Blink of gameplay
![image alt](https://github.com/WWasilew/Snake/blob/84b7d01d4cff8cb228624600332067f8357bded2/snake/images/snake_gameplay.png)

## Project Structure
```
SnakeGame/
│── GameFrame.java    # Main game window
│── GamePanel.java    # Core game logic and rendering
│── SnakeGame.java    # Entry point of the application
```

## Installation
1. Clone this repository or download the source files.
2. Ensure you have Java installed (Java 8 or higher recommended).
3. Compile and run the game using the following commands:
   ```sh
   javac SnakeGame.java GameFrame.java GamePanel.java
   java SnakeGame
   ```

## How to Play
- Use the arrow keys to control the snake's movement:
  - **Up Arrow**: Move up
  - **Down Arrow**: Move down
  - **Left Arrow**: Move left
  - **Right Arrow**: Move right
- Eat apples to grow longer.
- Avoid colliding with the screen borders or yourself.
- Fill the entire screen with the snake to win.
- If you lose, press the **Restart** button to play again.

## Future Improvements
- Add sound effects and background music.
- Implement difficulty levels.
- Save high scores.
- Add custom skins for the snake and apple.

## License
This project is open-source and can be modified or distributed freely.

## Contact
Created by [WWasilew](https://github.com/WWasilew). If you have any questions or feedback, feel free to reach out!
