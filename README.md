# Hangman Game 🎮

This is a simple console-based Hangman game written in Python. The player tries to guess the hidden word by suggesting letters one at a time. 
The game gives feedback on correct and incorrect guesses, and displays a visual hangman to show the player’s remaining lives.

## Features
- **Random Word Selection**: Each game session starts with a randomly chosen word from a list.
- **Guess Tracking**: The game shows letters that have already been guessed and provides feedback on each guess.
- **Life System**: Players start with 6 lives, with one life lost for each incorrect guess.
- **Visual Stages**: Each incorrect guess brings the player closer to the complete hangman figure.

## Project Structure
- `hangman_art.py`: Contains ASCII art for the game's logo and each stage of the hangman figure.
- `hangman_words.py`: Contains a list of possible words for the game.

## Requirements
- Python 3.x
- `hangman_art.py` and `hangman_words.py` files in the same directory as the main script.

## How to Play
1. Clone the repository:
   ```bash
   git clone https://github.com/yukamenes/Hangman.git
2. Run the hangman.py script
   ```bash
   python main.py
3. Guess letters one by one. Each incorrect guess decreases your lives.
4. Win by guessing the entire word before running out of lives, or lose if you reach 0 lives.
![image](https://github.com/user-attachments/assets/8881fc52-45df-421d-b7f6-84251f297316)

## License
This project is open-source and available under the MIT License.

## Enjoy playing Hangman! Good luck with your guesses!

