Overview:
This is a simple Number Guessing Game written in C. The goal of the game is for the user to guess a randomly generated number between 1 and 100. The program provides feedback on whether the guess is too high, too low, or correct, and tracks the number of attempts made by the user.

FEATURES:
The program generates a random number between 1 and 100.
The user is prompted to input a guess.
After each guess, the program provides feedback on whether the guess is too high, too low, or correct.
The program counts the number of attempts and displays it once the user guesses the correct number.

Requirements:
To run the program, you need:
1. A C compiler (e.g., GCC)
2. A terminal or command-line interface to run the executable

How it Works:
The program starts by seeding the random number generator with srand(time(0)), ensuring that the random numbers are different each time the program is run.
The target number is randomly generated within the range 1-100 using rand() % 100 + 1.
A do-while loop is used to repeatedly prompt the user for guesses until the correct number is guessed.
After each guess, the program gives feedback:
If the guess is too high, it prints "Too high! Try again."
If the guess is too low, it prints "Too low! Try again."
If the guess is correct, it prints a congratulatory message along with the number of attempts made.
