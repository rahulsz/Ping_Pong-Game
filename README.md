# Ping - Pong Game

This is a simple implementation of the classic game Pong using HTML5 canvas and JavaScript. The game allows two players to control paddles and compete against each other to score points by hitting the ball past their opponent's paddle.

## How to Play

- Player 1 controls the left paddle and uses the "W" key to move up and the "S" key to move down.
- Player 2 controls the right paddle and uses the arrow up key to move up and the arrow down key to move down.
- The objective is to hit the ball with your paddle in such a way that your opponent cannot return it.
- Each time the ball passes the opponent's paddle, a point is awarded to the player who successfully hit the ball.
- The game ends when a player reaches the specified score limit.
- To reset the game, click the "Reset" button.

## Game Features

- The game board is rendered on an HTML5 canvas element.
- The paddles are represented by colored rectangles, and the ball is represented by a yellow circle with a black border.
- The game board is cleared and repainted on each frame to create animation.
- The ball moves at a constant speed and changes direction when it collides with the top or bottom walls.
- When the ball collides with a paddle, its direction changes and its speed increases.
- The score is displayed at the top of the game board.
- The game can be reset at any time to start a new match.

## Technologies Used

- HTML5 Canvas: Used to render the game board and the game elements.
- JavaScript: Used to implement the game logic and handle user input.
- CSS: Used to style the game board and elements.

## Getting Started

To play the game locally, follow these steps:

1. Clone the repository or download the source code.
2. Open the `index.html` file in a web browser that supports HTML5 canvas.
3. Use the provided controls to play the game.

## Contributions

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, feel free to create a pull request or submit an issue in the GitHub repository.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code for your own purposes.

