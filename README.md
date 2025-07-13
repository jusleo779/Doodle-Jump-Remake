Disclaimer: The code I created was limited to the knowledge from a Java course and the time constraint I had. It doesn't look the best because I'm not familiar with all the fancy methods that could make it easier.

**Game Explanation**:

- Player can move left and right with the a or d key
- Platforms spawn at random, and the screen moves up after the character jumps onto a higher platform than the one above
- The player dies if they fall off the platform
- Springs give you a small jump boost
- Rockets that give you a big boost
- fake platforms that break 

**Class Explanations**:

**GameManager Class**

- a general class that manages all the actions in the game
    - Moves all the platforms/items up
    - places spring and rocket randomly
    - checks if the player is touching something to cause a reaction

**Random Class**

- a method that randomizes the placement of the platforms in the game
- a method that randomizes the placement of springs and rockets
 
**Other Classes** (Player, bar, rocket, weakbar, spring)

- All have similar methods of movement when the player jumps on them

**Challenges in the Project**:

- Registering the player is above/ touching the bar, and moving the screen up when the player touching/above the bar
- had to create methods to check that the player was really on top of the bar and that the screen seemed to move up
- multiple problems of everything not moving up and not being random, so I created a new class and methods that would update the game
- The graphics in the game were a problem (everything was glitchy on the screen)

**Relations to EE**:

- Debugging and Testing
   - requires a lot of testing for bugs that cause the program to fail
   - ex. screen not showing updates/bars not moving
- Time/Resource Management
   - Under a time constraint, and managed to get the basic idea of the game down
   - managed resources well by using the knowledge I already had from the Java course to create my first creative Java project
  
  
