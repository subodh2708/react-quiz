# 🧠 React Quiz App

A quiz application built with React that uses `useReducer` for state management, and fetches questions from a mock API for dynamic content.

---

## 🚀 Live Demo

🔗 [https://react-quiz-subodh.netlify.app/](https://react-quiz-subodh.netlify.app/)

---

## ✨ Features

- 🎯 Question flow: start → answer questions → see results
- 🔄 State managed with **useReducer** (handles quiz steps, user selections, score)
- 🌐 Questions fetched from a mock API (`my-json-server.typicode.com`)
- 💾 Persistent or dynamic state logic for quiz sessions
- 📱 Responsive UI

---

## 🧰 Tech Stack

- React (Hooks, `useReducer`, Components)
- JavaScript (ES6+)
- CSS (Flexbox / Grid)
- Mock API for quiz data
- Netlify for deployment

---

## ⚙️ Installation & Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/subodh2708/react-quiz.git
   cd react-quiz
   ```

2. Install dependencies
   npm install

3. Configure the mock API

   Update your fetch URL in the project to use your mock API:

   const BASE_URL = "https://my-json-server.typicode.com/your-username/react-quiz";

4. Start the development server

   npm start

The app will run at: http://localhost:3000

🌍 Deployment (Netlify)

    Push your project to GitHub.
    Connect your repo to Netlify.
    Add environment variables if required.
    Use these build settings:
    Build command: npm run build
    Publish directory: build

🧾 License

    This project is open-source and free for learning and personal use.

👋 About

    This project represents my next step in mastering React — moving from useState to useReducer, learning structured state transitions, and handling dynamic API data to create real-world interactive apps.
