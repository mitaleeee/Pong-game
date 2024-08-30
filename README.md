# Pong Game

This project is a Java Swing implementation of the classic Pong game, created to understand and practice the fundamentals of game development in Java. Inspired by various tutorials, this version of Pong includes additional features and enhancements that provide a more dynamic and enjoyable experience for players. 

Pong is a simple yet addictive arcade game that simulates a table tennis match. Two players control paddles on opposite sides of the screen, aiming to score points by hitting a moving ball past their opponent. This project not only recreates the nostalgic charm of the original game but also introduces new features such as dynamic difficulty adjustment, customizable settings, and a user-friendly interface, making it engaging for both beginners and experienced players.

## Key Technological Features

### 1. Java and Swing

- **Java**: A versatile, object-oriented programming language used to implement the game logic, manage game objects, and handle user inputs.
- **Swing**: A part of Java's standard library that provides a rich set of GUI components. It is used here to create the game's window, buttons, and other visual elements.

### 2. Core Game Components

- **GameFrame.java**: Sets up the main game window using Java Swing, defining the frame size, title, and exit operations. It acts as the container for all other game components.
- **GamePanel.java**: Handles the rendering of game elements (ball, paddles, and score) and manages the game loop. This class is responsible for updating the game state, detecting collisions, and repainting the screen.
- **Ball.java**: Manages the properties and behavior of the ball, including its speed, direction, and collision detection with paddles and walls. It controls the ball's movement and bounce mechanics.
- **Paddle.java**: Defines the paddles' properties and behavior, including movement based on player input, collision detection with the ball, and boundary checks.
- **Score.java**: Keeps track of the score for both players, updating and displaying the scores in real-time on the game screen.

### 3. Added Features

- **StartupWindow.java**: Provides an introductory window or main menu, allowing players to start the game, view instructions, or exit. This creates a user-friendly entry point to the game.
- **Dynamic Difficulty Adjustment**: The ball's speed increases gradually with each successful hit, making the game progressively more challenging.
- **Customizable Game Settings**: Added the ability to customize certain game settings like paddle speed, ball speed, and winning score.
- **Enhanced Score Display**: Real-time score updates and display during gameplay, with improved UI elements for clarity and feedback.

### 4. Game Logic and Mechanics

- **Collision Detection**: Utilizes mathematical calculations to detect collisions between the ball and paddles, and the walls. The collision logic ensures a realistic bounce effect.
- **Keyboard Input Handling**: Captures player inputs using Java's KeyListener interface, enabling smooth and responsive paddle movement.
- **Game Loop**: Manages the continuous update and rendering cycle of the game. Ensures smooth gameplay by updating the game state and repainting the screen at regular intervals.

## Main Features

- **Single-Player and Two-Player Modes**: Allows for both single-player (against a computer) and two-player gameplay on the same machine.
- **Customizable Settings**: Players can adjust difficulty levels, paddle speed, and set the winning score limit.
- **Simple and Intuitive UI**: A clean, minimalist design makes the game easy to understand and play for users of all ages.
- **Sound Effects**: Added basic sound effects for collisions and scoring to make the game more engaging.

## Acknowledgments

This project was developed as a learning exercise, inspired by various tutorials and resources on Java and Swing game development, with a few features added for an enhanced experience.

## Contact

For any questions or feedback, please reach out to mitalee18p@gmail.com.

