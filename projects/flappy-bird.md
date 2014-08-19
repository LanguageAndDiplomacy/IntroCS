#Flappy Bird

![Flappy Bird](https://raw.githubusercontent.com/LanguageAndDiplomacy/IntroCS/master/projects/flappy.png)

## Overview
The most annoying game in the world. This game pits you, a bird, against a maze of pipes. How many pipes can fly through? How many times can you play before you smash your computer?

## Specifications and grading

### Detailed requirements

#### Variables
- You will display the current score, the high score, and the current speed.
- The score should increment every time you fly through an obstacle
- The speed should change incrementally with each obstacle.

#### Bird Sprite
- The bird is player controlled, and should jump with every spacebar input
- The bird will need to fall when not jumping
- When the bird collides with the ceiling or the ground, the game is over

#### Obstacles
- The obstacles will move across the screen
- When the bird collides with an obstacle, the player must lose.
- You will need to decide what the obstacles look like and how they are positioned

#### Losing the Game
- When the game ends, the obstacles must stop moving and control of the game must stop
- Losing the game should change the high score, if the high score has been beaten
- You should be able to restart the game (resetting your score) somehow

#### Additional extensions
- Once you complete the above, you can add features for extra credit
- Power-ups: items to collect that increase your points or otherwise influence the game
- Lives: instead of losing the game instantly, have a set number of lives that decreases on every collision
- Increasing difficulty: have the obstacles start with wide openings, but slowly decrease the size of the opening
- Pause: allow the player to pause and unpause the game

### Grading criteria
The detailed list for what we will use to grade your projects is below. Please review your projects before submitting to be sure you meet all of them. If you have any questions on whether you meet a requirement, please ask us!!


| Requirement                                                      | Points |
|------------------------------------------------------------------|-------:|
| *Variables*                                                      |        |
| Current score, high score, and current speed displayed           | 5      |
| Player score increments every time she flies through an obstacle | 10     |
| Speed should increases after obstacle                            | 10     |
| *Bird*                                                           |        |
| The bird jumps when spacebar is pressed                          | 5      |
| The bird falls                                                   | 10     |
| Game is over when bird collides with ceiling or floor            | 10     |
| *Obstacles*                                                      |        |
| Obstacles move across the screen while game is playing           | 5      |
| Bird colliding with obstacle ends the game                       | 10     |
| Obstacles vary in positioning                                    | 10     |
| *Game*                                                           |        |
| When the game is lost, the obstacles and bird stop moving        | 10     |
| Losing the game adjusts the high score                           | 5      |
| Player can start a new game after losing                         | 10     |
|                                                                  |        |
| Total                                                            | 100    |

Each extra credit item is worth 10 points.

