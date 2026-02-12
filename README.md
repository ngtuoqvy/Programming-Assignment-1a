# Programming-Assignment-1a

## Chosen Project Idea
I chose the 2D game idea from the discussion board (originally made in Python using Pygame). (this is the Sudeep Biswa's python project)  
The game includes a character with attacks, hitboxes, coin collection, and a save system.

## Planned Java Version
I will recreate a simplified version as a standalone Java program.  
The focus will be on core gameplay logic rather than complex graphics.

Core features:
- Player movement
- Basic attack with a hitbox
- Falling coins that the player can collect
- Coin counter
- Save/load coin count using a text file

## Simplifications
To match our course level:

- No advanced animations (use simple shapes or static images)
- Only one main attack at first (melee hitbox)
- Simple 2D rendering using Java Swing
- Simplified collision detection using rectangles
- Basic coin rain system for testing

## Possible Enhancements
If time allows:
- Add projectile slash attack
- Add simple enemy/dummy target
- Increase coin spawn rate over time
- Add high score saving

## Save System
A text file will store the player's coin count.  
The program reads it on start and writes it on exit.

## How to Run (Planned)
Compile and run using Java:

javac *.java  
java Main
