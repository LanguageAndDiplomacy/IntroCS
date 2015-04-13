## Project 2: Bots

For this project, you will program a space bot that communicates with humans through written commands. When it receives a commad it knows, it
does some action. For example, when you say "hi", it will say hi back.

Below is a list of the commands and actions you need to program it to understand. We wrote some started code for your bots that you can download [here](https://github.com/LanguageAndDiplomacy/IntroCS/blob/master/projects/bot/bot_starter.sb2?raw=true).

### Bot Commands

1. When the bot receives the command **switch**, it will change costumes. If the bot receives "switch" again, it will change costumes back.


2. When the bot receives the command **date**, it will say the current date in for format "The current date is 10/20".


3. When the bot receives a number it likes, it will say "I like that number!". The bot likes whole numbers (e.g. 15 but not 15.8) that are between 100 and 200. (hint: there is one operator block that will be particularly useful when checking for whole numbers).


4. When the bot receives the command **game**, it will pick a random number between 1 and 100. It will continue to prompt the user to guess a number until
the user has guessed the correct number. If the user guesses the correct number, the bot should say "you win!". If the user guesses a number that is
too small, the bot should tell the user to pick a larger number. If the user guesses a number that is too large, the bot should tell the user to pick a
smaller number.

**Bonus** When the bot recieves the commands **decimal**, it will ask the user "What binary number should I convert to decimal?" The user then can enter binary number they wish, and the bot says what that binary number is in decimal. When receiving the command **binary**, it asks "What decimal number should I convert to binary". The user enters a decimal number and the both says the number converted to binary.

### Rubric (64 pts) 
1. **switch** (9 pts)
   - the costume switches when the user enters "switch" (3 pts)
   - there are only 2 costume (3 pts)
   - the costume continues to switch every time the user enters "switch" (3 pts)

2. **date** (13 pts)
   - the basic functionality works (8 pts)
   - the response is in the correct format (5 pts)

3. **numbers it likes** (16 pts)
   - the bot correctly identifies whole numbers (4 pts)
   - the bot correctly identifies numbers between 100 and 200 (4 pts)
   - the bot correctly identifies numbers it likes (4 pts)
   - the bot does not say "I like that number" for incorrect numbers (4 pts)

4. **game** (26 pts)
   - the bot starts the game on the "game" command (3 pts)
   - the bot picks a random number to guess between 1 and 100 (5 pts)
   - the bot prompts the user to guess a number after the game is started (3 pts)
   - The bot correctly tells the user if his or her guess is correct, too high or too low (10 pts)
   - The bot waits to end the game until the user guesses the correct number (5 pts)

5. **convert** (BONUS up to 20 pts)
    
