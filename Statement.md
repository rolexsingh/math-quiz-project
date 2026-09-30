# Problem Statement:
1. The Gap / Need:
. Many beginner math learners or students want a quick, distraction-free way to practice basic mental arithmetic (addition, subtraction, multiplication, and division). Standard online tools are often full of ads, overly complex graphics, or require account creation for simple practice.

2. The Target Users:
. Primary school students or basic learners looking to practice quick math drills.
. Self-learners who want instant feedback on their arithmetic speed and accuracy.

3. The Solution:
. The Math Quiz Game provides a lightweight, command-line interface (CLI) application built in Python. It allows users to quickly select a specific math topic, answer targeted multiple-choice questions, get immediate answer verification, and track their score in a clean, straightforward environment.

# Scope of the Project:
The project is a single-session command-line quiz application. Scope includes:

. Collecting the user's name for a personalized experience
. Letting the user choose one of four arithmetic topics
. Presenting 5 multiple-choice questions for the chosen topic
. Giving instant right/wrong feedback per question
. Calculating and displaying a final score out of 5
Out of scope (for this version): multiple topics in a single run, a graphical interface, persistent score history/storage, difficulty levels, and a timer. These are listed as possible future enhancements in the project report.

# High-Level Features:
. Instead of just saying "Hello [Name]", make it time-aware based on the user's system clock (e.g., "Good Morning, Rahul!" or "Good Evening, Rahul!").
. After showing the final score, ask the player: "Would you like to try another topic? (y/n)" so they don't have to restart the script manually from the terminal.
. Display clear progress indicators before each question (e.g., Question 3 of 5) so the player always knows where they are in the quiz.
. After completing the 5 questions, display a quick summary list showing which specific questions the user got right or wrong alongside the correct answers.
