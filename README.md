# ⚛️ The React Quiz

A modern, interactive quiz application built with **React**.  
This project tests your general React knowledge (or any subject via JSON data) featuring a timer, highscore tracking, and a comprehensive progress overview.

The application utilizes the **Context API** combined with the **useReducer** hook for efficient and scalable global state management.

---

## 🌟 Features

- **Start Screen** — Displays the number of questions.
- **Timer** — 30 seconds countdown per question.
- **Progress Bar** — Visual indicator of current progress and score.
- **Highscore System** — Stores the highest score in the current session.
- **Instant Feedback** — Visual response for correct and incorrect answers.
- **Summary Screen** — Shows final score, percentage, and highscore.
- **Restart Quiz** — Reset the quiz without reloading the page.

---

## 🛠️ Tech Stack

- **React** — Functional Components & Hooks
- **State Management** — Context API + useReducer
- **Data Fetching** — Fetch API
- **Mock Backend** — JSON Server
- **Styling** — CSS / CSS Modules

---

## 📂 Project Structure

```text
src/
├── components/      # UI Components (Header, Question, Timer, etc.)
├── contexts/        # QuizContext (Global State & Logic)
├── data/            # questions.json
├── App.js           # Root Component
└── index.js         # Entry Point
```


🚀 Getting Started
1. Clone the repository
git clone https://github.com/your-username/react-quiz.git
cd react-quiz

2. Install dependencies
npm install

3. Start the Mock API

This project uses JSON Server to simulate a backend server.

# Install json-server globally if not installed
npm i -g json-server

# Start the server
npm run server


