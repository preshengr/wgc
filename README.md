# Word Guessing Game

A simple and fun word-guessing game built with HTML, CSS, and JavaScript. The user tries to guess a random word by guessing letters one at a time. If the guessed letter is correct, it fills in the blanks, otherwise, the player loses a life. The goal is to guess the word before running out of lives!

## Table of Contents
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

---

## Getting Started

To get a local copy of the project up and running, follow the steps outlined in this guide.

### Prerequisites

Make sure you have a web browser installed such as Google Chrome, Mozilla Firefox, or any modern browser. You also need a text editor like Visual Studio Code or Sublime Text to view and edit the code.

---

## Project Structure

The repository is structured as follows:

```
word-guessing-game/
│
├── index.html      # Main HTML file
├── style.css       # Styling for the game
├── js/
│   ├── script.js   # Game logic
│   ├── words.js    # List of words for the game
```

---

## Installation

Follow these steps to clone and run the game locally:

### Step 1: Clone the repository

```bash
git clone https://github.com/yourusername/word-guessing-game.git
```

### Step 2: Navigate to the project directory

```bash
cd word-guessing-game
```

### Step 3: Open the `index.html` file in your web browser

You can simply double-click the `index.html` file in the project directory, or right-click and choose `Open With` -> `Your preferred web browser`.

Alternatively, you can open it through the terminal (on Mac/Linux):

```bash
open index.html
```

For Windows, you can use:

```bash
start index.html
```

---

## Usage

1. After opening the game in your browser, you will be presented with blank spaces corresponding to the letters of a random word.
2. Guess the word by typing a letter. If the letter is correct, it will be revealed in the correct position(s) of the word.
3. You have a limited number of lives (wrong guesses) before the game is over.
4. Try to guess the word correctly before you run out of lives!

---

## Code Explanation

### 1. `index.html`

This is the main structure of the game. It includes placeholders for the game interface such as the word blanks, letter input, and lives left.

### 2. `style.css`

This file defines the visual styling of the game. It includes colors, fonts, and layout styles for a better user experience.

### 3. `js/script.js`

This file contains the game logic. It handles the user's input, checks if the guessed letter is in the word, updates the UI, and tracks the number of lives left.

### 4. `js/words.js`

This file contains an array of words that will be randomly chosen for the player to guess.

---

## Contributing

If you'd like to contribute to this project, feel free to fork the repository and submit a pull request. All contributions are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add YourFeature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a pull request

## License

This project is open-source and available under the [MIT License](LICENSE).