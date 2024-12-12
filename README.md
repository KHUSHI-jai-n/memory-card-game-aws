# MEMORY CARD GAME

A fun and engaging memory matching game! Test your memory by matching meme cards. Built using AWS S3 and AWS CodePipeline.

## About the Game

The Meme Matching Game is a simple memory game built with **HTML**, **CSS**, and **JavaScript**. 

### How to Play
- Flip two cards at a time to reveal their images.
- Match pairs of meme cards to make them disappear from the board.
- If the cards don't match, they flip back to their blank side.
- Try to match all pairs with the fewest clicks possible!

---

## Features
- Interactive card flipping animation.
- Tracks the total number of clicks to complete the game.
- Dynamic game board with shuffled meme cards every time you play.
- Fully responsive design for both desktop and mobile devices.

---

## Technology Stack
- **HTML**: Structure of the game.
- **CSS**: Styling and layout.
- **JavaScript**: Game logic and interactivity.

---

## Deployment Details

### Hosting Environment
The game is hosted on **Amazon S3** as a static website.

### Deployment Pipeline
- **Version Control**: The source code is managed on **GitHub**.
- **Continuous Deployment**: The pipeline is powered by **AWS CodePipeline**.
    - Detects changes in the GitHub repository.
    - Automatically deploys the updated code to the S3 bucket hosting the game.
