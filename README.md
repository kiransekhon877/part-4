Name:- Kirandeep Kaur
Student Id:- 041134559
Website Project:- Quiz
Project Overview: Quiz Game
The Quiz Game project is an interactive web-based application designed to test users' knowledge on various topics, such as general knowledge, science, geography, history, or even custom categories. The game consists of multiple-choice questions, and after users answer each question, they receive instant feedback on whether their answer is correct or incorrect. Once the user completes all the questions, their total score is displayed, and they are encouraged to try again with a new set of questions.

Main Features:

Multiple-Choice Questions: Users can answer questions with multiple options.
Instant Feedback: Correct and incorrect answers are immediately highlighted.
Scoring System: Users receive a score at the end based on how many questions they answered correctly.
Mockup Overview:
A mockup serves as a visual prototype of the Quiz Game, showing the layout and UI design before the actual implementation. The mockup should include the following key screens and features:

Home Screen:

Title and Intro: The top of the page will have the title of the game (e.g., "Quiz Challenge").
Start Button: A prominent "Start Quiz" button that initiates the game.
Category Selection (Optional): Dropdown or button choices to let the user select a specific category (e.g., General Knowledge, Science, etc.).
Instructions: A small section explaining how to play (e.g., "Answer the questions, select the correct option, and see your score at the end!").
Challenges Faced During the Development of the Quiz Game:
Dynamic Question Generation:

Problem: Ensuring the quiz generates random questions each time a user plays.
Solution: Use arrays or objects to store all the questions and answers, and then randomize the question selection using JavaScript. This required careful handling of state and question tracking to avoid repeating questions.
Tracking User Progress and Scoring:

Problem: Tracking user answers and calculating their score in real-time.
Solution: Use JavaScript to keep track of the user's score by incrementing it when a correct answer is selected. This also required handling cases where users answer incorrectly and preventing multiple attempts at answering the same question.
Providing Instant Feedback:

Problem: Providing real-time feedback after each answer to let users know whether they were right or wrong.
Solution: Use event listeners to detect when a user selects an answer and immediately display feedback (correct/incorrect). This involved manipulating the DOM to show visual indicators like color changes or icons (green for correct, red for incorrect).
