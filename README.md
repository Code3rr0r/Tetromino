# Tetromino

Tetromino is a classic Tetris game built using HTML, CSS, and JavaScript. The game provides a smooth and responsive gaming experience with customizable controls and a modern feel.

## Features

- **Smooth animations**: The game uses `requestAnimationFrame` for smooth frame rendering.
- **Keyboard controls**: Play using the arrow keys or WASD keys to control the movement and rotation of tetrominoes.
- **Game Over Detection**: The game ends when a tetromino cannot be placed in the game area.
- **Responsive design**: The canvas adapts to the screen size while keeping the gameplay experience consistent.

## Controls

- **Arrow Keys / WASD**: Move the tetromino
  - `Arrow Left` / `A`: Move left
  - `Arrow Right` / `D`: Move right
  - `Arrow Down` / `S`: Move down
  - `Arrow Up` / `W`: Move up
- **Space**: Rotate the tetromino
- **Escape**: Restart the game

## How to Play

1. **Start the Game**: Once you open the game in a browser, a Tetris game area will appear.
2. **Move the Tetromino**: Use the arrow keys or WASD to move the falling tetromino around the screen.
3. **Rotate the Tetromino**: Press `Space` or `Arrow Up` to rotate the tetromino.
4. **Clear Lines**: When a line is fully filled, it disappears, and the player gains points.

The game continues until the tetrominoes stack up to the top of the game area.

## How to Run the Game Locally

To run this game on your local machine:

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/tetromino.git
    ```

2. Open the `index.html` file in your browser.

That's it! You can now play the game.

## Technology Stack

- **HTML**: For the structure of the game.
- **CSS**: For styling the game area and UI.
- **JavaScript**: For the logic of the game, including the tetromino movement, collision detection, and game-over functionality.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
