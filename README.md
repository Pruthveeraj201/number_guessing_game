# number_guessing_game
import random
def number_guessing_game():
 X = 20
 Y = 50
 Number = random.randint(X, Y)
 print("Welcome to the number guessing game!")
 guess = int(input(f"Guess a number between {X} and {Y}: "))
 if guess < X:
 print("enter the valid number")
 elif guess >Y:
 print("enter the valid number")
 while guess != Number:
 if guess < Number:
 print("\nToo low... try again!")
 elif guess > Number:
 print("\nToo high... try again!")
 guess = int(input("Guess again: "))
 print("You have guessed it right.")
number_guessing_game()
