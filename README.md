#CSS Project- Box bouncing
Here's a breakdown of what each part of the code does:

1. Global Resets and Variables:

   > The _, _::after, \*::before rule resets margin, padding, and sets box-sizing: border-box for all elements to ensure consistent sizing.
   > The :root rule defines CSS variables for box color, rotation speed, and bounce speed.

2. Body Styling:
   
   > Sets a black background and ensures the minimum height is 100% of the viewport height.
   > Uses flexbox to center content horizontally and vertically.
   > Adds a 3D perspective effect.

3. Scene Setup:

   > .scene class creates a 3D container that rotates continuously using the sceneRotate animation.

4. Bouncing Ball:

   > .ball class styles a circular, light blue ball with a gradient.
   > Positioned absolutely to allow for precise control of its placement.
   > Animates vertically to simulate bouncing with the ballBounce keyframes.
   > Also rotates in the opposite direction of the scene with the sceneRotate animation.

5. Ball Shadow:

   > .ballshadow class adds a shadow effect beneath the ball.
   > Animates scaling and opacity to match the bounce of the ball.

6. Cube:

   > .cube class creates a 3D cube.
   > Contains six faces (.front, .back, .left, .right, .top, .bottom) each positioned to form a cube.
   > Faces have a box shadow for a 3D effect.
   > Animates height to simulate bouncing with the cubeHeight keyframes.

7. Floor:
   > .floor class styles a checkered floor using a combination of radial and conic gradients.
   > Positioned and rotated to appear as the floor in the 3D scene.

8. Animations:
   > sceneRotate: Rotates the .scene container continuously.
   > ballBounce: Moves the .ball up and down to create a bouncing effect.
   > ballShadow: Scales and changes the opacity of the .ballshadow to match the ball's bounce.
   > cubeHeight: Adjusts the height of the .cube to simulate a bouncing effect.
   
   

Overall, the code creates a visually dynamic 3D animation with a bouncing ball and a rotating cube on a patterned floor.

## Demo
![Recording2024-05-15191548-ezgif com-video-to-gif-converter](https://github.com/aakashjhav/BouncyBox/assets/68254095/bcf248e3-7c55-4358-b632-1c44bb0608c2)
