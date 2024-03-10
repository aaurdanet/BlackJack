Blackjack Game

This is a simple command-line implementation of the classic game Blackjack. The game is played between the player and the dealer (computer). The goal is to get as close to 21 as possible without going over.
How to Play

    Run the program.
    When prompted, type 'y' to play or 'n' to exit.
    Follow the prompts during the game to either get another card ('y') or pass ('n').
    The game will then reveal the final hands and determine the winner.

Code Overview

    deal_card(): Function to randomly select a card from the deck.
    calculate_score(cards): Function to calculate the score of a hand.
    compare(user_score, computer_score): Function to compare the scores of the player and the computer.
    play_game(): Function to play a single round of Blackjack.
    The game logic is structured to handle user input, deal cards, calculate scores, and determine the winner.

Changes Made

    Initialized computer_score variable in the play_game() function to avoid referencing before assignment.
    Changed "Computer" to "Dealer" for consistency in the game messages.
    Added a loop to ask the user if they want to play another round after finishing a game.

Requirements

    Python 3.x
    art.py

Note

    This game follows the basic rules of Blackjack. For advanced rules or additional features, further modifications may be required.

Feel free to reach out for any queries or suggestions!

Enjoy playing Blackjack! 🃏
