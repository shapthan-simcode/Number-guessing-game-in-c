# Number Guessing Game in C

This is a simple number guessing game written in C.  
The program generates a random number between 1 and 100, and the player has to guess it.  
After each guess, the program provides feedback whether the guess is too high, too low, or correct.

---

## Features
- Random number generation between 1 and 100  
- Feedback after each guess  
- Counts the number of attempts  

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/C-Number-Guessing-Game.git
   cd C-Number-Guessing-Game
gcc guessing_game.c -o guessing_game
./guessing_game   # On Linux/Mac
guessing_game.exe # On Windows
Number Guessing Game
---------------------
Guess a number between 1 and 100
Enter your guess: 50
Too high! Try again.
Enter your guess: 25
Too low! Try again.
Enter your guess: 37
Correct! You guessed it in 3 attempts.
