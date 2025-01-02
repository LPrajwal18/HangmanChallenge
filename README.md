# Hangman Game

## Overview
This project implements a simple console-based Hangman game where players guess letters to reveal a hidden word. It includes features such as tracking lives, displaying a placeholder for the word, and providing feedback for correct or incorrect guesses.

---

## Features
- Random word selection from a predefined list.
- Visual feedback with ASCII art for the hangman stages.
- Tracks player lives and guessed letters.
- Interactive console interface.
- Game ends with a win or loss message.

---

## Requirements
- Python 3.6 or higher

---

## How to Play
1. Clone or download this repository.
2. Run the `solution.py` file in a Python-supported environment.
3. Players will:
   - Guess one letter at a time.
   - Get feedback on whether the letter is in the word.
   - Lose a life for each incorrect guess.
4. The game ends when:
   - All letters are guessed correctly (win).
   - All lives are lost (loss).

---

## File Descriptions
- `solution.py`: Main game logic.
- `hangman_words.py`: Contains the list of words used for random selection.
- `hangman_art.py`: Contains ASCII art for the hangman stages and the game logo.

---

## Example Gameplay
1. The game displays a hidden word as underscores (`_ _ _ _`).
2. Players enter a letter.
3. If the letter is correct, it reveals its position(s) in the word.
4. If incorrect, a life is deducted, and the hangman drawing progresses.
5. The game ends with a win or loss message.

---

## How to Run the Project
1. Open a terminal/command prompt.
2. Navigate to the project directory.
3. Run the following command:
   ```bash
   python solution.py
   ```

---
