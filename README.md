# Unlimited Colors Background Changer

This project is a simple web application that changes the background color of the page every second when the "Start" button is clicked. Users can stop the color changes by clicking the "Stop" button.

## Features

- Generates random colors in hexadecimal format.
- Changes the background color every second when started.
- Allows stopping the color change at any time.

## Files

- `index.html`: Contains the HTML structure, buttons for starting and stopping the color change, and links to the JavaScript file.
- `script.js`: Contains the logic to generate random colors and change the background color at a specified interval.

## Usage

1. Open `index.html` in a web browser.
2. Click the "Start" button to begin changing the background color every second.
3. Click the "Stop" button to stop the color change.

## Code Explanation

### `randomColor` Function

- Generates a random hex color code by randomly selecting six hexadecimal characters.
  
### `startChangingColor` Function

- Initiates a setInterval that calls the `changeBgColor` function every second if no interval is currently active.
- `changeBgColor`: Changes the background color to a new random color.

### `stopChangingColor` Function

- Stops the color-changing interval and resets it.

## Technologies Used

- HTML
- CSS
- JavaScript

