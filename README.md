# Guess The Number Game 🤔🔍

---

### Live Demo: [https://tanishka-cs.github.io/guessgame/](https://tanishka-cs.github.io/guessgame/)

[![Guess The Number Game Interface](![Screenshot (404)](https://github.com/user-attachments/assets/cf5da0d6-35a5-49ad-80ab-db52f1fa66fd)
)
](https://tanishka-cs.github.io/guessgame/)

## Overview

This is a simple, interactive web-based "Guess The Number" game where the player tries to guess a randomly generated secret number between 1 and 100. It provides real-time feedback to help the player narrow down their guess.

## Features

* **Interactive Gameplay:** Enter your guess and get instant feedback.
* **Intelligent Hints:** Receive clues if your guess is too high or too low.
* **"Very Close" Indicator:** Get a special message if your guess is within 5 of the secret number.
* **Attempt Counter:** Tracks how many tries it takes you to guess the correct number.
* **Play Again Option:** Easily reset the game to start a new round with a fresh number.
* **Input Validation:** Prevents invalid number entries outside the specified range.
* **User-Friendly Interface:** Clean and intuitive design for ease of use.
* **Responsive Design:** Adapts to various screen sizes for a consistent experience on desktop and mobile.

## Game Rules

* A secret number is randomly generated between 1 and 100 at the start of each game.
* Enter your guess in the input field and submit it.
* The game will tell you if your guess is:
    * **Right Guess!** (You win!)
    * **VERY CLOSE!** (Within 5 of the secret number)
    * **HINT: Try a greater number!**
    * **HINT: Try a smaller number!**
* The game counts your attempts.
* You can reset the game at any time to play again.

## Technologies Used

* **HTML5:** For structuring the web page content and user input elements.
* **CSS3:** For styling, ensuring a responsive, visually appealing layout, and background effects.
* **JavaScript (ES6+):** For the core game logic, number generation, user interaction handling, and dynamic content updates.

## How to Play

1.  **Visit the Live Demo:** The easiest way is to use the live demo link provided above.
2.  **Enter Your Guess:** Type a number between 1 and 100 into the input box.
3.  **Submit Guess:** Click the "Submit Guess" button.
4.  **Read Feedback:** The game will provide a hint or declare if you've guessed correctly.
5.  **Keep Guessing:** Continue entering numbers until you find the secret number.
6.  **Play Again:** Click the "Play Again 🔄" button to reset the game and start a new round.

### Running Locally

If you wish to run this project on your local machine:

1.  **Download the `index.html` file**. All the game's code is self-contained within this single HTML file.
2.  **Open the file:** Open the `index.html` file directly in your preferred web browser.

## What I Learned / Key Takeaways

* **Front-End Development Fundamentals:** Solidified understanding of HTML structure, CSS styling, and JavaScript logic in a self-contained project.
* **DOM Manipulation:** Gained practical experience in interacting with HTML elements dynamically using JavaScript to update game messages and input states.
* **Event Handling:** Implemented event listeners for button clicks to trigger game logic.
* **Random Number Generation:** Used JavaScript's `Math.floor(Math.random() * 100) + 1` to generate a random secret number.
* **Input Validation:** Implemented checks for `isNaN()` and number range (`< 1` or `> 100`) to ensure valid user input.
* **Conditional Logic:** Applied `if/else if/else` statements for providing hints and determining the win condition, including using `Math.abs()` for the "very close" logic.
* **Responsive Web Design:** Practiced using CSS to ensure the game looks good on different screen sizes.
* **Git & GitHub Pages:** Utilized Git for version control and successfully deployed the project live using GitHub Pages.

## Author

**Tanishka Yadav**

* [LinkedIn Profile](https://www.linkedin.com/in/tanishka-yadav-5b5021366)
* [GitHub Profile](https://github.com/Tanishka-cs)
