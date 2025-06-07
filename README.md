# Number Guessing Game

A simple command-line number guessing game written in Python. This interactive game allows users to guess a randomly generated number within a user-defined range, tracking the number of attempts and offering the option to play multiple rounds.

## Features

- User selects the minimum and maximum numbers for the guessing range.
- Random number generation within the selected range.
- Input validation for all user entries.
- Feedback after each guess: informs if the guess was too high or too low.
- Counts and displays the number of guesses per round.
- Option to play again after each successful round.
- Compatible with Windows, macOS, and Linux terminals (clears the screen automatically).

## How It Works

1. **Enter the Range**:  
   You will be prompted to enter the minimum (`Min`) and maximum (`Max`) values for the guessing range. Pressing Enter without typing a value will use the defaults: 0 for Min and 100 for Max.

2. **Start Guessing**:  
   The game will randomly choose a number between your selected Min and Max. Enter your guesses one at a time. If your guess is too high or too low, you will be notified.

3. **Win and Replay**:  
   When you guess correctly, the game displays the number of attempts you made. You can then choose to play again or exit.

## Example Gameplay

```
Enter Min (0):
Enter Max (100):
Guess: 50
50 is smaller
Guess: 75
75 is bigger
Guess: 60
60 is the number!
Number Of Guesses: 3
Play again? (Y/N)
```

## Usage

### 1. Clone or Download

Clone this repository or download the `number_guessing_game.py` file.

```bash
git clone https://github.com/Argh94/your-repo-name.git
cd your-repo-name
```

Or just download the file:

- [number_guessing_game.py](./number_guessing_game.py)

### 2. Run the Game

Ensure you have Python 3 installed. Open your terminal or command prompt and run:

```bash
python number_guessing_game.py
```

### 3. Follow On-Screen Prompts

- Input your desired minimum and maximum range.
- Start guessing numbers until you find the correct one.
- Decide if you want to play another round.

## Requirements

- Python 3.x
- Works on Windows, macOS, and Linux

## Code Structure Overview

- **clear()**: Clears the terminal screen.
- **validate_input(a)**: Checks if user input is a valid integer.
- **main()**: Runs the main game loop, handles user inputs, guess checking, and replay logic.

## Customization

You can change the default minimum and maximum range by editing the `DEFAULT_MIN` and `DEFAULT_MAX` variables at the top of the script.

## License

This project is open source and free to use.

---

**Enjoy the game and happy guessing!**
