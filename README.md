# Assembly Game: Word Matching

This assembly program is a simple word matching game. The player needs to input four characters, and the program checks if the input matches any of the predefined words. The game includes a score system and life count. The goal is to match words and achieve a high score.

## How to Run

To assemble and run the program:

1. Use an x86 assembly language compiler (e.g., NASM).
2. Assemble the code: `nasm -f bin game.asm -o game.com`.
3. Run the compiled program: `game.com`.

## Gameplay

- The game will display a grid of boxes containing predefined words.
- Enter four characters when prompted.
- The program will check if the input matches any of the words.
- If a match is found, the player's score increases, and a success message is displayed.
- If no match is found, the player loses a life, and a failure message is displayed.
- The game continues until the player reaches a certain score or presses the Esc key.
- 
## How to Play

1. Use the keyboard to input four characters when prompted.
2. Press Enter to submit the input.
3. Repeat the process until the game ends.

## Winning Condition

The player wins by achieving a certain score (e.g., 200 points).

## Ending the Game

Press the Esc key to end the game at any time.

## Notes

- The game includes a scoring system, life count, and predefined words.
- The program uses x86 assembly language.

## Author

AbdurRehman Haroon
