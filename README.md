# AI Student Assistant

## Project Overview

**AI Student Assistant** is an intelligent assistant designed to help students learn, practice, and improve their skills.

The goal is to create an AI that adapts to the user's **level and progress** and helps them with different subjects.

The project will start with **Python and English** and will evolve during the year.

---

## Who is the user?

The user is a **student or beginner** who wants help learning and practicing.

The assistant is designed for students who want to improve progressively with exercises adapted to their level.

---

## What problem are we solving?

Learning can be difficult when exercises and explanations are not adapted to the student's level.

Students can also have difficulties identifying what they need to improve.

**AI Student Assistant** provides personalized explanations and exercises based on the user's level and results.

---

# Main Features

## Choose Your Level

When starting a subject, the user chooses their level.

For example:

```text id="6t6a1w"
What is your Python level?

Beginner
Intermediate
Advanced
```

The exercises and explanations are then adapted to this level.

---

# Python Learning

The assistant helps users learn Python through exercises.

It can provide:

* Python explanations
* Code examples
* Exercises
* Questions
* Code correction
* Hints

Different types of exercises can be available.

### Write Code

```text id="74chlo"
Create a variable called "age"
and print its value.
```

### Find the Error

```python id="1ipkkh"
age = input("Age: ")

if age >= 18:
    print("Adult")
```

The student must find the problem.

### Complete the Code

```python id="pfvms5"
def square(n):
    return _____
```

---

# English Learning

The assistant also helps students improve their English.

When starting, the user can choose their English level:

```text id="0m6zzt"
What is your English level?

Beginner
Intermediate
Advanced
```

The AI can provide different types of English lessons and exercises.

## Vocabulary

The assistant can teach new English words and their meanings.

It can also teach **technical English related to computer science and AI**.

Example:

```text id="lj3z65"
Computer = Ordinateur
Keyboard = Clavier
Network = Réseau
Software = Logiciel
```

## Grammar

The AI can explain English grammar and generate exercises.

Example:

```text id="3x93hu"
Choose the correct answer:

Yesterday, I ___ to school.

A. go
B. went
C. gone
```

## Conversation

The user can practice English by having conversations with the AI.

The AI can correct mistakes and explain them.

Example:

```text id="5s64fy"
AI: What did you do yesterday?

User: I go to school.

AI: Because you're talking about yesterday,
you should say:

"I went to school."
```

---

# Smart Hint System

When the user makes a mistake, the AI can provide a hint instead of immediately giving the answer.

For example, in Python:

```python id="62i61v"
number = input("Choose a number: ")

if number % 2 == 0:
    print("Even")
```

The AI could say:

> Think about the type of value returned by `input()`.

The same system can be used for English exercises.

---

# Progress

The assistant can track the user's results.

```text id="0bv61p"
MY PROGRESS

Python          70%
English         60%

Python weakness:
Functions

English weakness:
Past tense
```

This allows the assistant to recommend exercises based on the user's weaknesses.

---

# Development Roadmap

The project will evolve during the year.

### V1 - Basic Version

* Choose Python or English
* Choose a level
* Basic exercises
* Basic explanations

### V2 - Exercises

* More exercises
* Different exercise types
* Scores
* Quizzes

### V3 - AI

* AI-generated exercises
* Personalized explanations
* Smart hints
* Code correction
* English correction

### V4 - Progress

* Save user progress
* Detect weaknesses
* Adapt exercise difficulty

### Future

More features and subjects will be added as the project evolves.

---

# Final Objective

The objective is to progressively create an **AI learning assistant that adapts to the student**.

The project starts with simple **Python and English learning tools** and will become more advanced throughout the year.
