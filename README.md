# quiz_app

A **Trivia App** built with **ReactJS** – challenge yourself with multiple-choice trivia questions and climb the money ladder!

## Features

- Trivia game with multiple-choice questions
- Countdown timer for each question
- Animated progress/money ladder
- Interactive feedback for right/wrong answers
- Clean and responsive UI

## Folder Structure

- **/public**: Static assets and images
- **/src**
  - **assets**: Resource files, such as background images or audio[1]
  - **components**: Reusable React components for the quiz functionality
    - `Start.jsx`: Input for username and starts the quiz[2]
    - `Timer.jsx`: Countdown for each trivia question[3]
    - `Trivia.jsx`: Core trivia game logic (questions, answer selection, interactivity)[4]
  - `App.jsx`: Main React component housing the overall game logic/UI[5]
  - `app.css`: Stylesheet for the application UI[6]
  - `index.js`: Entry point, renders the `App` component[7]

## Getting Started

1. **Clone this repository:**
   ```bash
   git clone https://github.com/abhinaba-dutta-gupta/quiz_app.git
   ```
2. **Install dependencies:**
   ```bash
   npm install
   ```
3. **Start the development server:**
   ```bash
   npm start
   ```
   Open [http://localhost:3000](http://localhost:3000) to play the quiz.

## Technology Stack

- **ReactJS**
- **CSS** for styling
- **Create React App** for bootstrapping
