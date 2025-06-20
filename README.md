# The Muilti-Tool: Introduction to Python

By Ajene Christian

## Introduction

As a coder who’s just mastered JavaScript, you're probably hungry for your next challenge or maybe you're just starting you're coding journey. Either way, Python is a great language to have in your tool kit. It is easy to read, beginner-friendly, and one of the most popular programming languages in the world, currently **ranked #1** on the [TIOBE](https://www.tiobe.com/tiobe-index/) index. **Python is an interpreted, object-oriented, high-level programming language with dynamic semantics.** In simpler terms, it is _versatile_ and **doesn't require compiling** your code to run it. Developers use it for everything from websites and task automation to machine learning, and even powering applications like Netflix.

One reason it's so widely loved is that its syntax reads almost like plain English, making it _easier to maintain_, write, and debug. While reading this, I'll walk you through what makes Python a great tool for developers, how it compares to JavaScript, and show syntax and features to get you started.

## The Set-Up: Getting Started with Python

1. Install Python

   Go to [python.org](python.org), and download the latest version for your operating system. On Windows, make sure to check the box that says "Add Python to PATH" during installation.

2. Check installation

   Open a terminal and type:

   ```bash
   python3 --version
   ```

3. Run your first Python script

   Create a new file:

   ```bash
   touch hello.py
   touch good-bye.txt
   ```

   To run your file:

   ```bash
   python hello.py
   ```

## Why Learn Python?

Learning Python gives you access to a completely different side of the development world. While JavaScript is good for building great interactive web applications, Python is the go to language for solving problems behind the scenes. Unlike JavaScript, which started from the browser and adapted for back-end development, Python was designed from the beginning to be **general purpose and expressive**. Engineers at companies like Google and NASA use it because its powerful, readable, and well-supported.

Python is the most versatile computer programming language, allowing developers to use it for:

- Data Mining
- Data Analytics
- Data Visualization
- AI and machine learning (like training an AI model to write poetry or detect cancer cells)
- Building apps
- Web Development and Web Application Development
- Developing games
- Quantitative and Qualitative Analysis
- Data Engineering

There are a few other capabilities of Python, which is why it is being used more across more industries. 

## Python in Practice

### Variables & Data Types:

In Python, you don't use `let`, `const`, or `var` to define a variable. You just write the variable name and assign it a value.

```python
name = 'Janice'  # STRING
age = 23         # INTEGER
pi = 3.14        # FLOAT
has_job = False  # BOOLEAN
```

### Functions & Code Blocks:

Use `def` to define a function.

```python
def call_me(name):
    print('Hi ',name)

call_me('Jason') # This is how you execute a function
```

### Conditionals:

```python
balance = 42

if balance > 20:
    print('Congrats Your Rich!')
elif balance < 10:
    print('Back to Work...')
else:
    print('Keep Grinding!')
```

### Lists and Dictionaries:

Lists are like arrays and dictionaries are like objects in JavaScript.

```python
dinner = ['Greens', 'Beans', 'Tomatoes', 'Ham'] # List
table = { name: 'Sam', seat: 1, is_eating: True } # Dictionary
```

### Iteration:

Loops in Python are extremely simple!

```python
dinner = ['Greens', 'Beans', 'Tomatoes', 'Ham']
serving_size = 2

# For Loop
for plate in dinner:
    print('Eating', plate)

#While Loop
while serving_size > 10:
    print('Still eating')
    serving_size += 1
```

## Python vs JavaScript

While both are very useful, they each shine in different areas. JavaScript is the best for building a web interface but Python excels in data-heavy tasks, automation, and fast development. If programming languages were tools in a workshop, JavaScript would be
a power drill; fast and focused. Python would be a multi-toll that folds out to whatever you need.

Key Differences:

- Syntax: Python uses indentation instead of curly braces, which forces you to write clean and readable code.
- Typing: Python leans more toward clarity and consistency, to allow the developer to ficus on problem solving.
- Use Cases: Python dominates AI, data science, automation, ans scripting.

Commonalities:

- Both support object-oriented and functional programming.
- Both have large, supportive communities. Giving you opportunities for feedback.
- You can build a full-stack applications using either.

## Conclusion & Tips for learning this language/framework.

Learning Python has made me a better developer. Its helped me improve my problem solving skills without having to worry about syntax. If you already know JavaScript, you'll be able to pick up on it quickly. JavaScript taught me web development but Python helped solidify my coding problem solving skills.

Tips:

- Start building small projects
- Read Documentation [(Free Book!)](https://automatetheboringstuff.com/)
- Try Online coding platforms like CodeAcademy
- Follow YouTube Tutorials
  - [Programming with Mosh](https://www.youtube.com/watch?v=K5KVEU3aaeQ&t=56s)
  - [freeCodeCamp Tutorial](https://www.youtube.com/watch?v=rfscVS0vtbw)

### Resources

- https://www.fdmgroup.com/news-insights/why-learn-python/

- https://www.geeksforgeeks.org/difference-between-python-and-javascript/

- https://leapcell.io/blog/python-cheat-sheet-a-quick-guide-to-core-syntax-and-features
- https://www.freecodecamp.org/news/learn-python-for-javascript-developers-handbook/
