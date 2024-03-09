# Blackjack

This Python script offers a comprehensive and engaging implementation of the classic card game Blackjack. Players compete against the computer, aiming to achieve a score as close to 21 as possible without exceeding it (busting). Aces can hold values of 1 or 11, adding a strategic layer to decision-making during gameplay.

Gameplay Features

Simplified Deck: The game utilizes a simplified deck where aces can be valued as either 1 or 11 for strategic play.
Player Choice: Players have the flexibility to "hit" (draw another card) or "stand" (keep their current hand), allowing for strategic decision-making.
Automated Computer Turns: The computer follows a pre-defined logic to draw cards until reaching a minimum score of 17 or higher.
Win/Loss Determination: The winner is determined by the player or computer who achieves a score closest to 21 without busting.
Multiple Rounds: Players have the option to enjoy multiple rounds of Blackjack, enhancing replayability.
Playing the Game

File Setup: Save the Python code as a file (e.g., blackjack.py).
Execution: Open a terminal or command prompt and navigate to the directory where you saved the file.
Run the Script: Execute the Python script using the command python blackjack.py.
Gameplay: Follow the on-screen prompts to play a round.
Multiple Rounds: Choose "y" to play another round or "n" to exit.
Code Structure

The code is well-structured for readability and maintainability by employing functions:

deal_card: Handles the random selection of a card from the simplified deck.
calculate_score: Calculates the total score of a hand, considering the value of aces.
compare: Compares player and computer scores to determine the winner.
play_game: Manages the core gameplay loop for a single round.
