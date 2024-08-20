# Guess-the-Number-Game
A number guessing game where the player tries to guess a randomly generated number between 1 and 100 within a limited number of attempts.

## Files
- `index.html`: Contains the HTML structure of the game.
- `style.css`: Contains the CSS for styling the game.
- `guessTheNumber.js`: Contains the JavaScript code for the game logic.

## Explanation:
- `Random Number Generation`: The code generates a random number between 1 and 100 at the start of the game.
- `Element Selection`: HTML elements are selected using `document.querySelector` to manipulate them later.
- `Event Listener`: An event listener is addede to the submit button to handle the player's guess.
- `Guess Validation`: The `validateGuess` function checks if the guess is a valid number and within the range of 1 to 100.
- `Guess Checking`: The `checkGuess` function compares the player's guess with the random number and provides the feedback.
- `Display Functions`: Functions to display guesses, messages, and manage game state.
- `End Game and New Game`: Functions to handle the end of the game and starting a new game. 
