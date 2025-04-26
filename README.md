# Quiz-App

This Quiz-App demonstrates the power of React.js in building dynamic, interactive user interfaces.
It’s a perfect example of how to handle user input, manage state, and create a seamless user experience using modern frontend technologies.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [File Structure](#file-structure)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Project](#running-the-project)
- [Environment Variables](#environment-variables)
- [Deployment](#deployment)
- [Contact](#contact)
- [License](#license)

## Overview

The Quiz-App is an interactive web application built using React.js that allows users to test their knowledge across various topics.
It dynamically presents multiple-choice questions, captures user answers, and provides instant feedback and scoring.

The app focuses on delivering a smooth, responsive, and user-friendly experience, making learning and self-assessment both fun and engaging.
You can view the live portfolio at: [LIVE PREVIEW](https://badshahyadav.github.io/Quiz-App/)

## Features

- **Dynamic Quiz Questions:** Displays a set of multiple-choice questions.

- **Real-Time Feedback:** Instantly shows whether the selected answer is correct or incorrect.

- **Score Tracking:** Calculates and displays the user's score at the end.

- **Responsive Design:** Fully responsive across desktop, tablet, and mobile devices.

- **Component-Based Structure:** Built with reusable and modular React components.

- **State Management:** Uses React hooks (useState, useEffect) for managing quiz state and behavior.

- **Simple Deployment:** Hosted using GitHub Pages.

## Tech Stack

- **Frontend**: React.js, Vite (for fast build and development).
- **Styling**: CSS3 (or Tailwind CSS if you used it).
- **Deployment**: GitHub Pages.
- **State Mangement** : React Hooks (useState, useEffect).

## Main Components

- **App.jsx** : Main application logic and state.

- **QuestionCard.jsx** : Displays each question and options.

- **Result.jsx** : Shows final score and results.

- **QuizData.js** : (Optional) Holds the quiz questions and answers in an array.

## Future Improvements (optional ideas)

- Add a **Timer** for each question.

- Create **Categories** for different quiz topics.

- Show **Correct Answer Explanation** after each question.

- Integrate a **Leaderboard** using local storage or Firebase.

- Add **Dark/Light** Theme Toggle.

## File Structure

Here's an overview of the project's file structure:

```plaintext
Quiz-App/
├── public/
│   └── favicon.svg (or favicon.ico)
│   └── index.html
│
├── src/
│   ├── assets/
│   │   └── (images, icons if any)
│   │
│   ├── components/
│   │   ├── QuestionCard.jsx
│   │   ├── Result.jsx
│   │   └── (any other reusable components)
│   │
│   ├── data/
│   │   └── quizData.js (static quiz questions/answers)
│   │
│   ├── App.jsx (main app logic)
│   ├── main.jsx (entry point — renders App)
│   └── App.css (global styles)
│
├── package.json
├── vite.config.js
├── README.md
├── .gitignore
└── index.html (under public/)

```

## Getting Started

### Prerequisites

Ensure you have the following tools installed on your development machine:

- **React.js** (Use current version)
- **npm** or **yarn**

### Installation

Clone the repository to your local machine:

```bash
https://github.com/BadshahYadav/Quiz-App.git
cd Quiz-App
```

Install the dependencies:

```bash
npm install
# or
yarn install
```

### Running the Project

To start the development server, run:

```bash
npm run dev
# or
yarn dev
```

Open your browser and navigate to `http://localhost:5173/` to view the application.

## Environment Variables Setup

The project requires the following environment variables. Create a `.env` file in the root directory and add your values:

```plaintext
VITE_APP_TITLE=Quiz App
VITE_APP_VERSION=1.0.0
VITE_PUBLIC_URL=https://yourusername.github.io/Quiz-App/
```

Vite environment variables must start with VITE_ or they won’t work!
## How to use them in your code:

In any React file (e.g., App.jsx):
```plaintext
const title = import.meta.env.VITE_APP_TITLE;
console.log(title);  // Outputs: Quiz App
```

## Deployment (GitHub Pages)

 Install gh-pages package

```bash
npm install gh-pages --save-dev
```

```bash
npm run deploy
```

Follow the prompts to deploy your application.

## Contact

If you have any questions or feedback, feel free to contact me via the [contact form](https://badshahyadav.github.io/Portfolio/) on my portfolio website or connect with me through my social profiles.

## License

This project is open-source and available under the [MIT License](LICENSE).
