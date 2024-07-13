# guess-the-number
Global Variables:

secret_number: Holds the randomly generated number the player needs to guess.
num_range: Determines the range of numbers for the game, initially set to 100.
remaining_guesses: Tracks the number of guesses the player has left.

Helper Function (new_game()):
Initializes a new game by setting secret_number to a random integer within num_range and calculates remaining_guesses based on the logarithm of num_range.

Event Handlers:
range100() and range1000(): Change the range of num_range to either 100 or 1000 and start a new game.
reset(): Resets the game within the current range.
input_guess(guess): Handles the player's input guess, compares it with secret_number, provides feedback (higher, lower, correct), and manages remaining guesses.
