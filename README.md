# Build Pong


The logic of the game is based on the movement of a ball and two paddles, one controlled by the player using the Up and Down arrow keys and the other by another player using the W and S keys. The game is set in a window with the dimensions of 800x600 pixels and has a black background. The game is designed to be a two player game, where each player controls a paddle and tries to hit the ball in order to score points.

The game starts by displaying the score of each player. The ball starts at the center of the screen and moves randomly in the x and y direction. The ball bounces off the walls if it hits them and changes direction. The ball also bounces off the paddles if it comes into contact with them and changes direction and moves faster.

Each time the ball passes the left or right side of the screen, the corresponding player earns a point and the score gets updated. The game is over when one of the players reaches the set high score and the game will display the winner.



## Language and Modules
- <b> Python </b>
- <b> Turtle </b>
- <b> Random </b>

## Files

- <b> `main.py` - is the entry point of the program. It creates instances of the `Paddle`, `Ball` and `Scoreboard` classes and uses their methods to handle user interactions and game logic, such as detecting collisions between the ball and the paddles, and updating the scoreboard. </b>

- <b> `paddle.py` - defines the Paddle class, which is used to create the paddles that the players control. It has methods to move the paddle up and down. </b>

- <b> `ball.py` - defines the `Ball` class, which is used to create the ball that the players hit back and forth. It has methods to move the ball, detect collisions with the wall and paddles, and change the direction of the ball's movement. </b>

- <b> `scoreboard.py` - defines the `Scoreboard` class, which is used to keep track of the score and display it on the screen. It has methods to update the scoreboard and increase the score for either player.
</b>

## Program
This project demonstrates object-oriented programming concepts and the use of classes and objects to model real-world entities. It also involves input validation, error handling, and file I/O.


<p align="center">
Launch <br/>
<img src="https://imgur.com/P2Db78z.png" height="80%" width="80%"/>
<img src="https://imgur.com/fFsEVpy.png" height="80%" width="80%"/>
<br />
