# week1---Python---task
Python Bigginer task for The Developers Arena Internship
🎉 Personal Introduction Program

Repository: Personal-Introduction-Project
Files included: personal_intro.py, requirements.txt, screenshot.png, README.md

📌 Project Overview The Personal Introduction Program is a simple Python project designed to introduce beginners to basic programming concepts.
The program asks the user for their *name, **age, **hobby, and *city, and then displays a friendly, personalized welcome message.

This project helps beginners understand:

    How to take input from the user
    How to store data in variables
    How to use print statements
    How to format output using f-strings
    How to write clean, documented code

🎯 Objectives

    Learn Basic Python Syntax Understand how print(), variables, and comments work. Write clean and readable Python code.

    Understand User Inputs Use the input() function to take information from the user. Store that information in meaningful variables.

    Practice String Formatting Use f-strings to combine text and variables to create a friendly message.

    Build a Real Python Program Create a working .py file that runs without errors. Make the program interactive.

    Improve Problem-Solving Skills Break a problem (personal intro) into smaller steps. Build the program step by step.

    Learn Basic GitHub Workflow Create a repository. Upload project files (README.md, .py, screenshot, requirements.txt). make clean, well-structured project folders.

    Write Good Documentation Describe what the project does. Explain how to run it. Add screenshots to show the output.

    Practice Testing & Debugging Test the program using different inputs. Fix errors like spacing, indentation, or input mismatches.

    Follow Coding Standards Use comments inside code. Maintain proper naming conventions for variables. Keep code simple and readable for beginners.

    Gain Confidence in Programming Learn how simple Python programs are created. Understand how real projects are submitted.

Build a foundation for future Python and data projects.---
🧭 Features (What the program asks & prints)

    Prompts:
        What is your name?
        How old are you?
        What is your favorite hobby?
        Which city do you live in?
        What is one thing you want to learn? (extra friendly question)
    Output: A multi-line welcome with emoji and friendly phrasing, e.g.:

##Step by Step Installation and Configuration Guide

✅ 1. Install Python

Windows

    Go to https://www.python.org/downloads/
    Download Python 3.x Installer
    IMPORTANT: Check the box “Add Python to PATH”
    Click Install Now
    After installation, open Command Prompt and type: python --version

✅ 2. Create Project Folder

Create a folder named: Personal-Introduction-Project Inside this folder, create: personal_intro.py README.md requirements.txt screenshot.png (added after running your program)

✅ 3. Add Code to personal_intro.py

name = input("What is your name? ") age = input("How old are you? ") hobby = input("What is your favorite hobby? ") city = input("Which city do you live in? ")

print("\n🎉 Welcome", name + "! 🎉") print(f"You are {age} years old, live in {city}, and love {hobby}.") print("Nice to meet you! 😊")

✅ 4. Run the Program

Windows

cd path\to\Personal-Introduction-Project python personal_intro.py

After entering your details, take a screenshot of the output and save it as: screenshot.png

✅ 5. Create requirements.txt

Inside the file, write: Python 3.x This tells the reviewer the Python version needed.

✅ 6. Upload Project to GitHub

Steps

    Go to GitHub.com

    Click New Repository

    Name it: Personal-Introduction-Project

    Click Create Repository

    Upload files: Click Add File → Upload Files Drag & drop: README.md personal_intro.py requirements.txt screenshot.png

    Click Commit Changes

✅ 7. Verify Everything

Check that your GitHub repository contains: ✔️ README.md ✔️ personal_intro.py ✔️ requirements.txt ✔️ screenshot.png ✔️ Proper project description and instructions

##Code Structure

Personal-Introduction-Project/ │ ├── README.md │ ├── personal_intro.py │ └── Contains: │ │ # Python Program │ name = input("What is your name? ") │ age = input("How old are you? ") │ hobby = input("What is your favorite hobby? ") │ city = input("Which city do you live in? ") │ │ print("\n🎉 Welcome", name + "! 🎉") │ print(f"You are {age} years old, live in {city}, and love {hobby}.") │ print("Nice to meet you! 😊") │ ├── requirements.txt │ └── Contains: │ Python 3.x │ └── screenshot.png └── Output screenshot of the program 🖼️ Visual Documentation

Sample expected output:

What is your name? Alex How old are you? 21 What is your favorite hobby? Coding Which city do you live in? Bengaluru

🎉 Welcome Alex! 🎉 You are 21 years old, live in Bengaluru, and love Coding. Nice to meet you! 😊

🧪 Testing Evidence

Test Case Input Output

1 John, 18, Cricket, Delhi Displays correct welcome message 2 Asha, 20, Painting, Mumbai Displays correct welcome message 3 Raju, 30, Reading, Chennai Displays correct welcome message

All tests should show proper formatting and correct values.

🛠️ Technical Details

✔ Concepts Used

Variables Input handling f-string formatting String concatenation Console input/output Basic program structure

✔ Program Flow

    Ask user for name, age, hobby, and city
    Save inputs into variables
    Display a personalized welcome message using f-strings

📚 What I Learned

Through this project, I learned: How to install and set up Python correctly How to write my first interactive Python script How to use variables and input functions How f-strings make formatting easier How to debug simple errors in code How to take a screenshot and include it in documentation How to create a GitHub repository and upload files How to write a complete README.md

✅ Final Notes

This project helped build hands-on experience with:

Python basics GitHub workflow Documentation writing Running and testing code

🎉 Great job completing your first Python project!
