📌 skillcraft technology internship - task 03(alternative ) completed
✔️ task - quiz game 

Interactive Multi-Type Quiz Game Web Application
📝 Project Description:
This project involves developing an interactive multiple-choice quiz game that enhances learning through fun and engagement. The application dynamically presents questions, accepts responses, and evaluates performance in real time. It supports various question types, including:
✅ Single Choice
✅ Multiple Select
✅ Fill in the Blanks
By incorporating various input formats, the quiz system becomes versatile and effective for testing different levels of understanding.
🎯 Objectives:
Build a responsive web-based quiz application.
Include support for:
Single-choice questions
Multi-select questions
Fill-in-the-blank questions
Track user answers and evaluate correctness.
Show real-time score and feedback.
Offer replay or retry options.
💡 Features:
User-friendly interface
Question and answer randomization
Real-time score tracking
Multi-type question support
Instant feedback and summary display
🛠️ Technologies Used:
HTML – for structure and layout
CSS – for styling and responsiveness
JavaScript – for logic and interactivity
🧱 Project Structure:
bash
CopyEdit
quiz-app/
│
├── index.html # Main HTML file
├── style.css # Styling
└── script.js # JavaScript logic
🔄 Functional Flow:
User opens the quiz interface.
A question is displayed with answer options based on the question type.
User submits their answer(s).
The system validates the input:
For MCQ: checks selected option(s)
For fill-in-the-blank: compares text
Score is updated.
User moves to the next question.
At the end, the final score and review are displayed.
✅ Sample Question Types:
1. Single Choice Example
json
CopyEdit
{
 "type": "single",
 "question": "What is the capital of India?",
 "options": ["Delhi", "Mumbai", "Chennai", "Kolkata"],
 "answer": "Delhi"
}
2. Multi Select Example
json
CopyEdit
{
 "type": "multiple",
 "question": "Which of these are programming languages?",
 "options": ["Python", "HTML", "C++", "CSS"],
 "answer": ["Python", "C++"]
}
3. Fill in the Blank Example
json
CopyEdit
{
 "type": "fill",
 "question": "______ is the process of finding and fixing bugs.",
 "answer": "Debugging"
}
📈 Outcomes:
Improved understanding of front-end web development.
Practical implementation of logic for handling multiple types of input.
Enhanced skills in JavaScript and dynamic UI rendering.
