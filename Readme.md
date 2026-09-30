Math Quiz Game # Math Quiz Game (Python CLI Project)

**It acts as a digital flashcard game or mini-test that runs directly inside your computer’s terminal**. This project was built as part of the Python Essentials
evaluated course project (VITyarthi).

## Overview

When the program runs, it asks the user for their name and then lets them
choose one of four math topics. Based on the topic selected, the program
presents 5 multiple-choice questions (a/b/c/d). For each question, the user's
answer is checked against the correct option, immediate feedback
("correct answer" / "wrong answer" / "invalid answer") is shown, and a final
score out of 5 is displayed at the end.

  ## code
  def start_quiz():
    name = input("Enter your name: ")
    print("Welcome to the Math Quiz, name!")
## Menu Details
Topic                 Examples 
Addition               25+25=50
Subtraction            30-15=15
Multiplication         6*6=36
Division               36/6=6
## Feature Upgrades
- I can use Python’s random module so the computer generates fresh numbers automatically use at every time, making the game replayable.
- Give players a choice between Easy to hard digits .
- Give players at a fixed time to make the game more exciting.
- The program ask the user if you wanted to closing immediately after showing the  yours score: "Do you want to play again? (y/n)" .

## Technologies / Tools Used

- **Language:** Python 3
- **Concepts used:** `input()`/`output`, conditionals (`if`/`elif`/`else`),
  type casting (`int()`, `str()`), variables, basic scoring logic
- **Environment:** Runs from any terminal with Python 3 installed
- **Version Control:** Git & GitHub

## Project Structure

```
math-quiz-project/
│
├── main.py            # Complete quiz program (entry point)
├── README.md           # Project documentation (this file)
├── statement.md         # Problem statement, scope, and target users
└── screenshots/          # Screenshots of the program running
```

## How to Install & Run

### Prerequisites
- Python 3.7 or above installed on your system
  (check with `python --version` or `python3 --version`)

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/arsh26bce11502/math-quiz-project.git
   cd math-quiz-project
   ```

2. **Run the program**
   ```bash
   python main.py
   ```
   (On some systems, use `python3 main.py` instead)

3. **Follow the on-screen prompts**
   - Enter your name when asked
   - Enter a number from 1-4 to choose a topic
   - Answer each question by typing `a`, `b`, `c`, or `d`
   - View your final score at the end

No external libraries or installation steps are required — the project uses
only Python's built-in `input()`/`print()` functions.

## Instructions for Testing

To manually test the program:

1. Run `python main.py`
2. Test each of the 4 menu options (1, 2, 3, 4) in separate runs to confirm
   all four topics (addition, subtraction, multiplication, division) work
   correctly.
3. For each topic, test:
   - Entering the **correct** option for a question → should print
     `correct answer`
   - Entering an **incorrect** option (one of the other 3 letters) →
     should print `wrong answer`
   - Entering something outside a/b/c/d (e.g. `x`) → should print
     `invalid answer`
4. Confirm that the final score displayed matches the number of questions
   answered correctly.

## Screenshots

_See the `screenshots/` folder for sample runs of the program (topic
selection, a question being answered, and the final score screen)._

## Author

Built by Utkarsh Singh(23MIM10156 ), 3rd Year, VIT Bhopal — as part of
the Python Essentials evaluated course project.
