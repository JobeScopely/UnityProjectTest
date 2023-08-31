# UnityProjectTest
Unity Project Take Home Test


# Submitting your work
Please commit each answer with comments on which question the commit addresses.  It is OK to go back and change previous answers if you jump around in the test, just note it in your commit.

# Other Tips
- The project is using Unity version 2022.3.8f1
- Please avoid adding 3rd party frameworks to the solution as much as you can.  If you feel one is necessary indicate why in your commit.  Please commit this as a separate commit from any of your code.
- Aim to complete the questions using the style or approach this solution uses
- Developer art is expected, do not waste time finding the perfect art
- You do not have to complete all the questions.
- If you partially complete a question it is OK submit that with a comment indicating that it is WIP (work in progress)


# Overview
You have been provided with a copy of the 2D Platformer Microgame project, a small project offered by Unity as part of their learning program.  This will be the basis for the test, all questions pertain to adding or changing this project.  In this test we will present a series of feature requests from a theoretical game designer.


## Question 1
The game designer would like to enable the use of health on the Player so that the player can survive more than one collision with an enemy.  The player already has a health script attached, but it is not being used properly.  Refactor the damage code to use the player health value and to cause X damage on a collision with an enemy that would cause damage, where X is specified on a per enemy basis.

## Question 2
Completing question 1 may cause an unintended issue for the designer, once the player collides they will likely collide again immediately.  Give the player 1 second of immunity after a collision with an enemy.

## Question 3
The game designer would like to create different game modes.  These modes would require a different configuration of game values like player health and starting position.  Implement the necessary changes to allow the game designer to be independent of a developer, add and run new game mode configurations.  It is expected the designer cab be working inside unity but will not write any code.

## Question 4
The game designer would like to add a player "gun" weapon.  On a keypress, the Player should fire a "bullet" in whatever direction they are facing.  The player can have unlimited bullets and fire as often as they like.  If the bullet collides with an enemy, it should do Y damage, where Y is set specific to the player.
