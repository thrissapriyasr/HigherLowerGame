
# Higher Lower Game - Guess the Follower Count Game

## Overview

This Python-based console game challenges players to guess which of two randomly selected social media accounts has more followers. The game uses a dataset of social media accounts with their respective follower counts. Players make their guesses by choosing between Account A and Account B, and the game provides feedback on whether the guess was correct or not.

## How to Play

1. The game displays two accounts, labeled as A and B, along with their names, descriptions, and countries.

2. Players guess which account has more followers by typing 'A' or 'B' in the console.

3. The game reveals whether the guess was correct and updates the player's score accordingly.

4. The game continues with a new set of accounts for comparison until the player makes an incorrect guess.

## Features

- **Random Account Selection:** The game randomly selects social media accounts for each round, ensuring variability in gameplay.

- **Score Tracking:** Players earn points for each correct guess, and the game displays the current score after each round.

- **Dynamic Account Swapping:** To keep the game engaging, the account that was initially labeled as B becomes the new A for the next round, preventing repetitive comparisons.

- **Clear Screen Functionality:** The console screen is cleared between rounds, providing a clean interface for the player.

- **Artistic Elements:** The game includes ASCII art for a visually appealing and interactive experience.

## Instructions for Running the Game

1. Make sure you have Python installed on your system.

2. Clone the repository to your local machine.

   ```bash
   git clone https://github.com/your-username/guess-the-follower-game.git
   ```

3. Navigate to the project directory.

   ```bash
   cd guess-the-follower-game
   ```

4. Run the game script.

   ```bash
   python guess_the_follower_game.py
   ```

5. Follow the on-screen instructions to play the game.

## Acknowledgments

- This game was inspired by web-based games that involve comparing social media follower counts.
  
- Special thanks to the [replit](https://docs.replit.com/repls/secret-keys) library for providing the `clear` function, enhancing the user interface.

Feel free to contribute, report issues, or suggest improvements to make this game even more enjoyable!

---

This template assumes that your game script is named `guess_the_follower_game.py`. If your script has a different name, make sure to adjust the instructions accordingly.
