# POV-WebGLRocketShadow

The challenge was to change the existing shadow of the rocket from the original color to another more realistic color. These are the steps followed:
  1.In order to do that, we've to create a new set of shaders. 
  2. Create all the variables required. We'll use it later along the codelines
  3. Once you have all variables, it's  time to create the actual shader. With a fsShadowSource we assign the color we feel looks realistic (0.7)
  4. Ensure that everything it's correctly named before proceed
  5. Update the gameloop with the new shadow fragment we have created on the previous step to be able to call and execute the shadow
  6. Then, it's time to render the shadow inside the draw task.
  7. Save the changes and build - if not errors...
  8. Run the program and visualize on the localhost
  9. Once you are happy with the shadow color, it's time to play!
