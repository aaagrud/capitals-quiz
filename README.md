# Capital City Quiz

A simple quiz application built with Node.js, Express, EJS, and PostgreSQL. The app quizzes users on the capital cities of various countries.

## Features
- Users can input their answers to capital city questions.
- The app provides feedback on whether the answer was correct.
- The total score is displayed to the user.

## Prerequisites
1. Node.js installed
2. PostgreSQL installed and running

## Installation
1. Clone the repository
2. Install dependencies: `npm install`
3. Set up the PostgreSQL database:
   - Create a database named `world`.
   - Create a table named `capitals` with columns `country` and `capital`.
   - Insert data into the table from capitals.csv.
4. Start the server: `nodemon index.js`
5. Visit `http://localhost:3000` in your browser to play the quiz.

## Usage
- Enter capital of the displayed country
- Click submit to check
- View your total and feedback on each submission

## Technologies Used
- Node.js
- Express
- EJS
- PostgreSQL
- CSS


