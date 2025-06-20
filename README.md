# python-number-game
A Python project for a number guessing game built for the MK:U programming module assignment.
import random # Importing to generate random numbers

# Global list to store game statistics (number of attempts per game)

# Function to start game
def start_game():
"""
Initialises the game, generates a random number, and handles guesses until the player wins
"""
print("Welcome to the Number Guessing Game!")
print("I have chosen a number betweewn 1 and 100. Try to guess it in five tries!")
