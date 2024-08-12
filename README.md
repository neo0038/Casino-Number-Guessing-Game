# Casino Number Guessing Game

This is a simple console-based C++ game where players can bet money on a number between 1 and 10. The game is based on chance, with players trying to guess the correct number to win a reward.

## Overview

The game is designed to be a fun and engaging way to test your luck. Players start with a certain amount of money, place bets, and guess a number. If the guessed number matches the randomly generated number, the player wins 10 times the bet amount. Otherwise, they lose the bet amount.

## Features

- **Betting System**:
  - Players can bet any amount of their current balance.
  - Correct guesses multiply the bet by 10.
  - Incorrect guesses result in losing the bet amount.
  
- **Random Number Generation**:
  - The game uses a random number generator to pick a number between 1 and 10 for each round.
  
- **User Interaction**:
  - Simple prompts guide the player through the game.
  - Players can choose to play multiple rounds until they run out of money.

## Game Rules

1. Choose a number between 1 to 10.
2. If your guess matches the random number, you win 10 times the amount you bet.
3. If your guess is incorrect, you lose the bet amount.
4. The game continues until you decide to stop or you run out of money.

## Installation and Running the Game

To play the game, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/CasinoNumberGuessingGame.git
   cd CasinoNumberGuessingGame
Compile the Code:

Use a C++ compiler like g++ to compile the code:
bash
Copy code
g++ -o casino_game casino_game.cpp
Run the Game:

Execute the compiled file to start the game:
bash
Copy code
./casino_game
Usage
Start the Game:

Enter your name and the starting balance.
Place a Bet:

Enter the amount you want to bet. The bet cannot exceed your current balance.
Guess a Number:

Choose a number between 1 and 10.
Check Results:

The game will randomly pick a number. If your guess is correct, you'll win 10 times your bet; otherwise, you'll lose the bet amount.
Continue or Exit:

You can choose to play another round or exit the game.
Contribution
If you'd like to contribute to this project, feel free to fork the repository and submit a pull request. Any improvements or bug fixes are welcome!
