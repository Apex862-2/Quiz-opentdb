## Quiz App

This program is a simple quiz application built using tkinter in Python. It fetches trivia questions from the Open Trivia DB API and presents them to the user. The user can select an answer for each question and see if they got it right or wrong. They also have the option to skip a question.

### Functionality

1. The program imports the necessary libraries - tkinter, messagebox, requests, and random.
2. It defines a list of API endpoints (qns) for different categories of trivia questions.
3. It makes a GET request to a random endpoint and extracts the data in JSON format.
4. It creates a tkinter window with a question label, option buttons for answers, and buttons for submitting or skipping questions.
5. The `load_question()` function loads a question and its answer options onto the screen. It shuffles the answer options to make the quiz more challenging.
6. The `show_results()` function displays the user's score at the end of the quiz.
7. The `skipbro()` function allows the user to skip a question without answering it.
8. The `check_answers()` function checks if the selected answer is correct and updates the score accordingly.
9. The program initializes the quiz by loading the first question and presenting it to the user.
10. The user can submit answers, skip questions, and view their final score after completing all the questions.

### How to Run

1. Copy the code snippet provided in main.py.
2. The database.py simply contains the links to the qns generated by de api and the topic
3. Save it in a Python file (e.g., `quiz.py`).
4. Install the required libraries (tkinter, requests) if they are not already installed.
5. Run the script using a Python interpreter.
6. Answer the trivia questions presented in the tkinter window and see your final score at the end.

### Note

- Make sure your system has an active internet connection to fetch trivia questions from the API.
- The quiz questions and answers are randomly generated, so you can try the quiz multiple times to test your knowledge.
