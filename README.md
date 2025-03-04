# Word Guessing Game

## Description
This is a simple word guessing game implemented in Python. The program randomly selects a word from a predefined list, and the player must guess the word one letter at a time. The player has a limited number of attempts to guess the correct word before the game ends.

## Features
- Randomly selects a word from a predefined list
- Displays the current guessed state of the word
- Allows the player to input single-letter guesses
- Tracks remaining attempts
- Ends the game when the word is guessed or attempts run out

## How to Play
1. Run the script in a Python environment.
2. The game will display the word with blanks (_ _ _ _ _).
3. Enter a letter to guess.
4. If the letter is in the word, it will be revealed.
5. If the letter is incorrect, the number of attempts will decrease.
6. Continue guessing until you find the complete word or run out of attempts.

## Requirements
- Python 3.x

## Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/your-username/your-repository.git
   ```
2. Navigate to the project directory:
   ```sh
   cd your-repository
   ```
3. Run the script:
   ```sh
   python word_guessing_game.py
   ```

## Example Output
```
Current word: _ _ _ _ _
Guess a letter: o
Great guess!

Current word: _ _ o _ _
Guess a letter: x
Wrong guess! Attempts left: 9
...
```

## Contribution
Feel free to contribute by submitting issues or pull requests.

## License
This project is open-source. You can modify and distribute it as per your requirements.
