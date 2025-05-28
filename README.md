# Tech Quiz Test Suite
Module 19 Challenge

https://github.com/Pricilla-Francis/Tech-Quiz-Test-Suite.git


# User Story
AS AN aspiring developer
I WANT to take a tech quiz
SO THAT I can test my knowledge and improve my skills

# Acceptance Criteria
GIVEN I am taking a tech quiz
WHEN I click the start button
THEN the quiz starts and I am presented with a question
WHEN I answer a question
THEN I am presented with another question
WHEN all questions are answered
THEN the quiz is over
WHEN the quiz is over
THEN I can view my score
WHEN the quiz is over
THEN I can start a new quiz

# Features

Interactive tech quiz experience
Multiple-choice questions
Real-time scoring
Option to restart the quiz

How It Works

1. **Start the Quiz**: Click the "Start Quiz" button.
2. **Answer Questions**: Select your answer to each question.
3. **See Your Results**: View your final score once all questions are answered.
4. **Try Again**: Click "Start New Quiz" to try again.



├── client/                 // the client application
├── cypress/                // Folder for Cypress
    ├── component/          // Folder for component tests
        └── Quiz.cy.jsx     // Component tests for the Quiz component
    ├── e2e/                // Folder for end-to-end tests
        └── quiz.cy.js      // End-to-end tests for the Tech Quiz
    ├── fixtures/           // Folder for test fixtures
        └── questions.json  // Mock data for testing
    └── tsconfig.json
├── server/                 // the server application
├── .gitignore
├── cypress.config.ts       // Runs the application using imports from lib/
├── package.json
├── tsconfig.json
└── README.md              // App description, link to video, setup and usage instructions  
