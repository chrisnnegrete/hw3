# hw3
Includes Line/Waterpipe programs with changes to code, and the changes to the Grass program.

1) The code that draws the blades of grass is on line 11:
    line(x, height-10, x+random(-10, 10), height-10-random(h));
 
2) The code that makes the lawnmower come by is on lines 21-25:
   if (random(100) > 99.9) {
    fill(255);
    rect(0, 0, width, height-15);
    h = 10;
   }
   
   The lawnmower comes by every time the grass reaches a height of 99.9 pixels.

3) The "h" variable determines the initial height of the blades of grass and is the multiplier in the function. If it were changed to be greater than 10, the grass would grow taller faster, and if it were less than 10, the grass would grow much slower and be shorter.

4) The 10 in the second argument "height-10-random(h)" changes the starting height of the grass. For instance, if 10 were changed to be 50, the grass would start 50 pixels above the dirt.
