# AI Student Assistant

AI Student Assistant is a beginner Python project designed to help students with simple study tasks.

The current version is not a real AI yet. It is a rule-based program using basic Python concepts such as variables, input, conditions and calculations.

## Who is the user?

The user is a student who wants help with their studies and wants to improve their Python skills.

## What problem are we solving?

Students may need help checking their grades, calculating averages, staying motivated or practising Python.

The goal of this project is to create a simple student assistant that can interact with the user and give different responses depending on their choices.

## Current Features

### Personal greeting

The program asks for the student's name and displays a personalised greeting.

### Grade checker

The user can enter a grade.

The assistant gives a different message depending on the result:

- 16 or more: excellent work
- 10 or more: passed
- Below 10: keep practising

### Average calculator

The user can enter two grades.

The program calculates and displays the average.

### Motivation

The assistant can display motivational messages to encourage the student.

### Learn Python

The user can choose their Python level:

- Beginner
- Intermediate
- Advanced

The assistant then gives a lesson and an exercise adapted to the selected level.

#### Beginner

The student learns about variables.

Example:

```python
age = 20
```

## Future improvements with code

The current version can already be improved a lot using only Python.

Possible improvements:

- Add loops so the menu can repeat without restarting the program
- Use functions to avoid repeating code
- Add more Python exercises
- Add more lessons for each level
- Create quizzes with several questions
- Add a score system
- Save the user's results in a file
- Save the user's name, level and progress
- Store previous mistakes
- Detect which exercises the user fails the most
- Recommend the next lesson depending on the user's results
- Add more subjects like English, maths, SQL or algorithms
- Create a better menu
- Add error handling if the user enters an invalid value
- Allow several correct answers for the same exercise
- Randomly choose exercises from a list
- Add difficulty progression
- Create a login or profile system
- Use a database to store user progress
- Create a graphical interface later

## Future improvements with AI

In the future, the project could also use an AI model or an API.

This could allow the assistant to:

- Understand natural language
- Understand different ways of answering the same exercise
- Analyse Python code instead of only comparing text
- Explain errors in the user's code
- Generate new exercises automatically
- Generate exercises adapted to the user's level
- Give personalised hints
- Give different explanations when the user does not understand
- Detect weaknesses automatically
- Analyse previous mistakes
- Recommend what the student should learn next
- Generate quizzes dynamically
- Correct English sentences
- Create English conversations
- Help with technical English
- Adapt the difficulty automatically
- Give personalised feedback
- Create revision sessions for exams
- Answer questions about lessons
- Explain concepts in different ways
- Track the student's learning profile
- Create a more natural conversation with the user

## Long-term vision

The long-term goal is to combine normal Python code with AI.

Python would manage things like:

- Menus
- User profiles
- Scores
- Progress
- Files
- Databases
- Exercise history
- Application logic

AI would manage things like:

- Understanding the user
- Generating explanations
- Generating exercises
- Correcting answers
- Giving personalised feedback
- Adapting the learning experience

The final goal is to create a real intelligent student assistant that improves with the user over time.

## Tests

| Test | Input | Expected result | Actual result |
| Grade checker | 18 | Excellent work! | Excellent work! |
| Grade checker | 12 | You passed! | You passed! |
| Average calculator | 12 and 16 | 14.0 | 14.0 |
| Python Beginner | age = 20 | Correct! | Correct! |
| Invalid menu choice | 9 | I do not understand that choice yet. | I do not understand that choice yet. |
