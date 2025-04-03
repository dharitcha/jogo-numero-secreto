# Secret Number Game

## Overview
The Secret Number Game is a simple number-guessing game designed to help beginners learn JavaScript fundamentals. The game randomly selects a number within a predefined range, and the player must guess the correct number with hints guiding them.

## Features
- **Random Number Generation:** The game selects a random number between 1 and 10.
- **User Input Handling:** Players can input their guesses via an input field.
- **Hint System:** The game provides hints if the guessed number is too high or too low.
- **Attempt Tracking:** Displays the number of attempts taken to guess the secret number.
- **Game Reset:** A button allows users to restart the game with a new secret number.

## Technologies Used
- **JavaScript**: Game logic, random number generation, and UI updates.
- **HTML**: Basic structure for the game interface.
- **CSS**: Styling for the UI.

## How It Works
### Game Flow
1. The game starts with a randomly generated secret number.
2. The player inputs a guess and submits it.
3. The game checks if the guess is correct:
   - If correct, it displays a success message with the attempt count.
   - If incorrect, it provides a hint (higher or lower).
4. The player can restart the game to try again with a new number.

### Example Interaction
```
Game: Choose a number between 1 and 10.
User: 5
Game: The secret number is lower.
User: 3
Game: The secret number is higher.
User: 4
Game: You got it in 3 attempts!
```

## Installation and Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/dharitcha/js-secret-number-game.git
   ```
2. Open `index.html` in a web browser.
3. Guess the number and enjoy the game!

## Future Improvements
- Expand the number range for more challenge levels.
- Add difficulty settings with different number ranges.
- Implement a graphical UI with animations.
- Add sound effects for user feedback.

## License
This project is open-source and available under the MIT License.

