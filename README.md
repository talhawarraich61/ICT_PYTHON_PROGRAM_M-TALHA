# Number Guessing Game

A simple command-line number guessing game written in Python.

The computer picks a random number between 1 and 100. You keep guessing until you get it right. After each guess, the game tells you if your guess was too high or too low.

## Features

- Random number between 1 and 100
- Hints after every guess (too high / too low)
- Counts how many attempts you took
- Handles invalid input (like letters) without crashing
- Type `exit` anytime to quit

## Requirements

- Python 3.6 or higher
- No external libraries needed

## How to Run

1. Clone this repository:
```
   git clone https://github.com/YOUR-USERNAME/ICT_PYTHON_PROGRAM_M-TALHA.git
```
2. Go to the project folder:
```
   cd ICT_PYTHON_PROGRAM_M-TALHA
```
3. Run the game:
```
   python play_game.py
```

## Example Output
<img width="958" height="514" alt="image" src="https://github.com/user-attachments/assets/1eee898a-e12c-4e76-9a16-879025bc777f" />

## How It Works

- `random.randint(1, 100)` picks the secret number.
- A `while` loop keeps asking for guesses until the player wins or types `exit`.
- `try/except` catches invalid input.
- `if / elif / else` compares the guess with the secret number.

## Author

Muhammed Talha- Github acc; talhawarraich61
