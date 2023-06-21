# ProjectGame
WELCOME TO PROJECT "SNAKE GAME" THIS IS MY FIRST PROJECT USING JAVA LANGUAGE

 -> INTRO <-
 
1. This game is all about controlling the snake using key buttons, making it eat food, increasing the snake's size and scores, and ending the 
game when the snake collides with obstacles.
2. SNAKE GAME INCLUDES THREE DOTS which is 

RED DOT -> HEAD OF THE SNAKE.
GREEN DOT's -> BODY OF THE SNAKE.
APPLE PICTURED GREEN DOT -> FOOD FOR THE SNAKE.

 -> FUNCTIONALTIES <-
 
 1. BASIC UI // which includes the frames, content, content pane, dimensions, and color of the background.
 2. GRAPHICS // which involves loading images and drawing components on the right position.
 3. LOCATING THE APPLE // which includes randomizing the Apple's position
 4. CONTROLLOING // which includes controlling the snake using arrow keys and checking for collisions with the border and the body.
 5. MECHANICS & DYNAMICS // which covers its movement and how it eats food.
 6. CONCLUDING // which covers displaying the score and game over message when the game ends.
 
 -> DETAILED IMPLEMENTATION OF FUNCTIONALTIES <-
 
 *BASIC UI 
 1. The components of the game are the board, the snake, and the app, each with their own properties that need to be initialized.
 2. The board is a rectangular box with a height and width that contains the game.
 3. The snake is a bunch of dots with a size and dot size, and the apple is a single size called torque size.
 4. The maximum number of dots that can fit in the board is calculated as 400/10 multiplied by 400/10, which equals 1600.
 5. The positions of the snake are defined by two arrays for the X and Y coordinates on the Java Swing application.

 *GRAPHICS 
 1. First we need to prepare resources and draw images at specified positions.
 2. Create new folder called resources inside src folder.
 3. Mark Resources folder as a resources folder.
 4. Download provided images from GitHub repository and save in Resources folder(IF YOU NEED).
 5. Load images inside Image class by creating Image objects for each image needed (body, head, apple).

 *LOCATING THE APPLE 
 1. Intially the position of the apple is fixed.
 2. As the game progress we need to randomize the apple's position each and everytime.
 3. To achieve this, the position of the apple will be randomized every time the application restarts using MATH CLASS.
 4. Apple size is 10.
 5. Values for the apple's position should be a multiple of 10.
 6. Using IN-Built JAVA FUNCTION MATH.RANDOM we can achieve this.

 *CONTROLLING THE SNAKE
 1. First step is to implement controls using a Key Adapter Class.
 2. Key Adapter Class will be customized by extending its properties and overriding its key pressed method.
 3. Key events will be generated whenever arrow keys or other keys are clicked.
 4. The key code for the clicked key will be obtained using get key code.
 5. The direction of the snake will be determined based on the clicked key.
 6. If the snake is already moving in a certain direction, clicking the opposite direction will be considered an INVALID MOVE.
 7. The snake's direction will be updated accordingly based on the clicked key and the current direction of the snake.
 8. All other directions will be set to false when a certain direction is true.

 *MECHANICS & DYNAMICS OF THE GAME
 1. The snake's movement is dependent on a timer class that triggers a move operation.
 2. There are FOUR POSSIBLE DIRECTIONS for the snake to move: RIGHT, LEFT, UP, DOWN.
 3. The coordinates of the snake's body are determined by its dot size and its initial position.
 4. When the snake moves in a particular direction, only the head's X-coordinate changes, while the other dots follow their 
    previous position.
 5. The X-coordinate of each dot in the snake's body decrements by its slot size if it is moving in the left direction and increments if it 
    is moving in the right direction.
 6. The Y-coordinate of each dot in the snake's body decrements if it is moving in the upward direction and increments if it is moving in 
    the downward direction.
 7. The head's position is determined by subtracting the dot size from its X-coordinate if it is moving in the left direction.
 8. The position of each subsequent dot in the snake's body is determined by subtracting 1 from its X-coordinate if it is moving in 
    the left direction.
    
 *CONCLUDING THE GAME
 1. When the game ends we need to display "Game Over" message and SCORE of the game.
 2. Game over message should be displayed in the center of the screen.
 3. Score should be displayed below the game over message.
 4. The HEIGHT OF THE SCREEN SHOULD BE DIVIDED INTO FOUR PARTS.
 5. "GAME OVER" message should be displayed at H/4 and SCORE should be displayed at 3H/4.
 6. X coordinate for the game over message should depend on the width of the message.
 7. Point size of 14 can be used for height.
 8. We need a Graphics object to draw a STRING.
 9. Calculate the score by subtracting 3 from the number of dots and multiplying it by 100.
 10. Use the INTEGER CLASS to CONVERT THE SCORE to a STRING.
 11. Create a small point with bold font and size of 14.
 12. Get the font metrics of the small point.

 -> TECHNOLOGIES USED <-
 
 *PROGRAMMING LANGAUAGE USED TO DEVELOP THE SNAKE GAME 
 1. USED JAVA AND JAVA ALONE.
 2. AND USED JAVASCRIPT LIBRARY WHILE USING JAVA SWING.

 *PLATFORM USED TO DEVELOP THE SNAKE GAME 
 
 1. The only technology used for making the Snake game is JAVA SWING LIBRARY, which provides lightweight components for making 
    WINDOW BASED APPLICATIONS.
 
 *CLASSES USED TO DEVELOP THE SNAKE GAME
 
 1. Classes used in the game include's J Button, J check boxes, combo box, J File Chooser, and J Frame.

 *STYLING OF THE SNAKE GAME
 
 1. The styling of the project includes a window with a container for the game.

 -> IMAGES FROM THE DEVELOPED SNAKE GAME <-
 
![Screenshot_20230621-202923](https://github.com/prasgrex/ProjectGame/assets/137268247/7aa8ca07-2d17-42af-ad8e-ff682002350c)
![Screenshot_20230621-203021](https://github.com/prasgrex/ProjectGame/assets/137268247/f7fb7f8a-72a9-45dd-ace9-b1b12329151a)
![Screenshot_20230621-203059](https://github.com/prasgrex/ProjectGame/assets/137268247/1a606ef2-743b-490e-915a-db79e8834d91)


 
 






