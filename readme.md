# Quiz App

A simple, interactive quiz application that runs in the browser. Users can answer multiple-choice questions and get their score at the end.

## Features

- Multiple-choice questions.
- Dynamic question rendering.
- Displays the final score after the quiz is completed.
- Ability to restart the quiz.

## Technologies Used

- **HTML**: For the structure of the application.
- **CSS**: For styling the interface.
- **JavaScript**: For functionality, such as dynamic question loading, tracking answers, and calculating the score.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/quiz-app.git
Navigate to the project directory:
bash
Copy
Edit
cd quiz-app
Open index.html in your browser to run the app.
Structure
index.html: The main HTML file.
style.css: The stylesheet for the app.
script.js: The JavaScript file containing the quiz logic.
Quiz Data
The quiz questions and answers are stored in the quizData array in the script.js file. You can add, remove, or modify questions by editing this array.

Example:

javascript
Copy
Edit
const quizData = [
    {
        question: "What does HTML stand for?",
        a: "Hypertext Markup Language",
        b: "Hypertext Markdown Language",
        c: "Hyperloop Machine Language",
        d: "Helicopters Terminals Motorboats Lamborghinis",
        correct: "a",
    },
];


Future Improvements
Add a timer for each question.
Implement category-based quizzes.
Add a leaderboard to save user scores.
License
This project is licensed under the MIT License.

Feel free to modify or expand this project to suit your needs. Happy coding!