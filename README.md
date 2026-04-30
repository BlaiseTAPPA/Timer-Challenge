# Timer Challenge

**Test your timing precision!**  
A reaction and timing game built with **React + Vite**.

Stop the timer as close as possible to the target time to maximize your score. The closer you are, the higher your points!

![Timer Challenge Preview](https://via.placeholder.com/800x450/0ea5e9/1e2937?text=Timer+Challenge)

_(Replace this image with a real screenshot or GIF of the game once uploaded to GitHub)_

## Features

- 4 progressive difficulty levels:
  - Easy → 1 second
  - Not Easy → 5 seconds
  - Getting Tough → 10 seconds
  - Pros Only → 15 seconds
- Smart scoring system based on **how close** you stop to the target time
- Modern and clean UI with cyan gradients
- Attractive result modal
- Precise timer management using `useRef` and `useEffect`
- Fully responsive design

## Tech Stack

- **React 18** (Hooks, Portals)
- **Vite** — Blazing fast build tool
- JavaScript (ES6+)
- Modern CSS (Flexbox & Gradients)

## Installation & Setup

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Steps

# Clone the repository

git clone https://github.com/your-username/timer-challenge.git
cd timer-challenge

# Install dependencies

npm install

# Start development server

npm run dev

#Build for Production
npm run build
npm run preview

## Project Structure

├── public
│ └── vite.svg
├── src
│ ├── assets
│ │ └── react.svg
│ ├── components
│ │ ├── Player.jsx
│ │ ├── ResultModal.jsx
│ │ └── TimerChallenge.jsx
│ ├── App.jsx
│ ├── index.css
│ └── main.jsx
├── .gitignore
├── index.html
├── package-lock.json
├── package.json
└── vite.config.js

## How to play

1.Choose a difficulty level from the four cards
2.Click "Start Challenge"
3.Click the button again when you think you've reached the target time
4.View your score and accuracy in the result modal

The higher the difficulty, the greater the challenge!

## Scoring System

Your score is calculated based on the difference between the stopped time and the target time.
The closer you are to the target, the higher your score.

## Project Highlights

° Accurate timer handling without memory leaks
° Clean usage of useRef, useState, and useEffect
° Modal implemented with createPortal
° Well-structured and modular code
° Smooth and modern user interface

## Future Improvements

Local leaderboard using localStorage
Sound effects and advanced animations
Dark / Light theme toggle
Persistent high scores
Internationalization (i18n)
Multiplayer mode

## License

This project is licensed under the MIT License.
