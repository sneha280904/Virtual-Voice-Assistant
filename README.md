---

# OIBSIP-Task-2

This repository contains the implementation for **Task 2** of the Oasis Infobyte Internship Program. The task focuses on **creating a simple yet effective number guessing game using Python**.

## Project Description

The goal of this project is to build a console-based number guessing game in Python. The game generates a random number and the user tries to guess it within a limited number of attempts. After each guess, the user is provided feedback indicating whether their guess was too high or too low.

## Features

- Random number generation
- User input validation
- Hints after each guess (too high / too low)
- Limited number of attempts
- Score tracking (if extended)
- Simple and beginner-friendly code structure

## Prerequisites

- Python 3.x installed on your system

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/sneha280904/OIBSIP-Task-2.git
   ```

2. Navigate to the project directory:
   ```bash
   cd OIBSIP-Task-2
   ```

3. Run the Python script:
   ```bash
   python number_guessing_game.py
   ```

## File Structure

```
OIBSIP-Task-2/
│
├── number_guessing_game.py   # Main Python script for the number guessing game
└── README.md                 # Project documentation
```

## Example Output

```
Welcome to the Number Guessing Game!
I'm thinking of a number between 1 and 100.
You have 10 attempts to guess it.

Enter your guess: 50
Too low!

Enter your guess: 75
Too high!

...
```
