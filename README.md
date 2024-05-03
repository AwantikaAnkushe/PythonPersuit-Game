SOURCE FILE :

1. Object-Oriented Programming (OOP): The game is organized using classes and objects. For instance, the `Game` class encapsulates the game logic and user interface components.

2. Swing GUI Components: Swing components such as `JPanel`, `Graphics`, `Font`, `Timer`, `KeyListener`, etc., are used to create the graphical user interface for the game.

3. Event Handling: Event handling is implemented using `ActionListener` and `KeyEvent` to respond to user input (arrow key presses) and timer events for game updates.

4. Randomization: The `Random` class is used to generate random positions for the apples within the game grid.

5. Game Loop: The game operates on a continuous loop controlled by a timer. This loop manages the game's logic, including moving the snake, checking for collisions, and updating the display.

6. State Management: The game maintains different states such as running, game over, and the initial start state, which are managed by boolean flags and conditional statements.

7. Drawing/Graphics: Graphics methods are used to draw components such as the snake, apples, score, and game over screen onto the JPanel.

8. Conditional Statements: Conditional statements (`if`, `switch`) are used for controlling game behavior, such as checking for collisions, changing direction based on user input, and handling game over conditions.

9. Looping Constructs: Looping constructs (`for`) are used for iterating over snake body parts, drawing grid lines (commented out), and managing game logic.

10. Constants and Variables: Constants (`static final`) are defined for screen dimensions, unit size, delay, and game units. Variables are used to store game state, snake position, direction, etc.

11. Encapsulation: Methods are encapsulated within the `Game` class to organize and encapsulate game functionality, promoting code modularity and readability.
------------------------------------------------------------------------------------------------------------------------------------------

LAUNCH FILE : 

1. Swing JFrame:   An instance of `JFrame` is created to represent the main window of the game.

2. Game Initialization: An instance of the `Game` class (the Snake game itself) is created.

3. Adding Components to JFrame:  The `Game` instance is added to the `JFrame` using the `add()` method. This places the game panel inside the window.

4. Window Configuration:
   - The title of the window is set to "Snake" using `setTitle()`.
   - The default close operation is set to `EXIT_ON_CLOSE`, ensuring the application terminates when the window is closed.
   - The window's resizability is disabled with `setResizable(false)` to maintain a fixed game layout.
   - The `pack()` method is called to resize the window to fit its components snugly.
   - Finally, `setVisible(true)` makes the window visible to the user.

5. Window Positioning: "setLocationRelativeTo(null)" centers the window on the screen by setting its location relative to `null`.
