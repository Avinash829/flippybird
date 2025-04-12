🐦 **Flippy Bird Game**
A lightweight and engaging browser-based game made with HTML, CSS, and JavaScript. Inspired by the popular Flappy Bird, your goal is to navigate the bird(looklike ball) through moving obstacles without crashing.

🎮 How to Play: 

->Click anywhere on the screen to make the bird(ball) flap upward.

->Steer the bird(ball) through the gaps in the orange blocks.

->The game ends if the bird(ball) touches any block or falls to the ground.

->Earn points by successfully passing through obstacles.

->Your best score is automatically saved in your browser using localStorage.

 **Logic Used**

**Jump Mechanics**:

->The ball character jumps upwards when the user clicks anywhere on the screen.

->Gravity pulls the character down over time.

**Obstacles (Blocks and Holes)**:

->The obstacles are created using a div element with animation that moves the blocks from right to left continuously.

->The holes within the blocks are randomly placed at varying vertical heights.

**Collision Detection**:

->The ball character is checked for collision against the blocks and holes. If the ball hits a block or falls below the screen, the game ends.

**Scoring**:

->Each time the ball successfully passes through a block (through the white hole), the score increments by one.

->The high score is saved using the browser's localStorage.

