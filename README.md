##BallMovement

In simulation ball movement a ball in made to move in vertical direction in fixed velocity.The ball moves in top to botton  and wise vera which refers to bouncing
The ball is made to move in X and Y axis

Steps to run the project 

 step 1
   - The <div> element with the ID "ball" represents the green ball.
   - It's styled with CSS attributes for its appearance, including its color, size, and position.

 step 2
     - The JavaScript code controls the animation of the ball:
     - velocity: Determines the speed of the ball in pixels per animation frame.
     - positionX and positionY: Store the current X and Y positions of the ball.
     - ball: Retrieves the ball element from the HTML document.
     - reverse: A boolean variable used to control the ball's direction.

step 3
   - The moveball function is called repeatedly by setInterval to create the animation effect.
   - If reverse is true, it moves the ball left and up by decrementing positionX and positionY.
   - If reverse is false, it moves the ball right and down by incrementing positionX and positionY.
   - The ball.style.left and ball.style.top properties are used to update the ball's position on the webpage.
   - When the ball reaches specified boundaries (Xmax or Ymin), the reverse variable is toggled to change its direction.

 step 4
   - The setInterval function calls the moveball function every 100 milliseconds, creating the animation effect.
    
Future implementations of Code

This code creates a simple, interactive animation where a green ball moves horizontally and vertically within defined boundaries, changing direction when it reaches those boundaries. The animation speed can be adjusted by changing the velocity variable. This code could serve as a basic example for understanding how to animate elements using JavaScript in a webpage.
