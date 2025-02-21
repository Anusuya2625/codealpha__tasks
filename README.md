# codealpha__tasks
Developed  project using python for codealpha internship
TASK 1
Hangman Game in Python
Overview
The Hangman game is a popular word-guessing game where the player attempts to guess a hidden word by suggesting letters within a limited number of attempts. This Python implementation of Hangman allows users to guess letters in a randomly chosen word, with feedback provided for each guess. The game concludes when the player either guesses the word correctly or exhausts their allowed number of incorrect guesses.

The game is text-based and runs entirely in the command line or terminal, providing a fun and interactive way to test one's vocabulary and deduction skills.

Features
Random Word Selection: The program selects a random word from a predefined list of words.
User Input: The player inputs one letter at a time.
Game Progress: The player sees the current state of the word after each guess, with unguessed letters represented by underscores (_).
Attempt Limitation: The player has a limited number of incorrect guesses before the game ends.
Input Validation: The game handles invalid inputs (e.g., non-alphabetical characters, repeating guesses).
How to Play
Run the game script by executing the following command in your terminal:

bash
Copy
python hangman.py
The game will randomly choose a word from the predefined list. You will be prompted to guess a letter.

The game will display the current state of the word, with underscores representing unguessed letters.

If you guess a correct letter, the word's state is updated. If the guess is incorrect, your remaining attempts will decrease by one.

The game continues until you either:

Guess the word correctly (win).
Run out of attempts (lose).
To exit the game early, type "exit" or "quit".
TASK 2
Overview
This project is a Chatbot implemented in Python. The chatbot simulates a conversational agent that can interact with users, provide simple responses to common questions, and engage in basic conversation. It uses a simple rule-based approach to match user input with predefined patterns and provide appropriate responses.

The chatbot can handle a variety of queries such as greetings, simple facts, and responses to custom commands. It's an ideal starting point for anyone interested in creating more complex conversational agents using Python.

Features
Pattern Matching: The bot responds based on regular expressions that match user input.
Simple Conversations: The bot can respond to common user inputs, such as greetings and inquiries about its capabilities.
Extensible: The framework is easy to extend. New patterns and responses can be added quickly.
Input Validation: The bot can handle unexpected inputs and continue the conversation.
How to Run the Chatbot
Run the chatbot script by executing the following command in your terminal:

bash
Copy
python chatbot.py
The chatbot will prompt you for an input. You can start by saying "Hello" or asking simple questions like "What's your name?".

The chatbot will respond to your input based on predefined patterns. To exit the conversation, simply type 'exit' or 'quit'.
TASK 3
Overview
This project is a Stock Portfolio Management System built using Python. The system allows users to manage their stock portfolio by adding, removing, and viewing their stocks and their performance over time. The program fetches real-time stock data using the Alpha Vantage API (or another stock market API) to provide the latest market prices, historical data, and portfolio performance analysis.

The application is a simple, text-based solution designed for individuals who wish to track their investments and monitor the market value of their stock holdings. It provides a straightforward way to manage a portfolio, make decisions based on live data, and calculate portfolio value in real time.

Features
Portfolio Management: Users can add, remove, and track stocks in their portfolio.
Real-Time Stock Data: Fetches up-to-date stock prices and other relevant market data via an API.
Portfolio Value Calculation: The system calculates the current value of the user's portfolio based on the current market prices of the stocks they own.
Stock Performance Analysis: The system can calculate the total value of the portfolio and track changes over time.
Extensible: Easily add more features such as historical data, dividend tracking, or performance analytics.
How to Use
Run the Python script to start managing your stock portfolio:

bash
Copy
python portfolio_manager.py
The system will prompt you for different actions:

Add a Stock: Input the stock symbol (ticker) and the number of shares you own.
Remove a Stock: Remove a stock from your portfolio by its ticker symbol.
View Portfolio: See your portfolio, including the number of shares and the current value of each stock.
Calculate Portfolio Value: Get the total current value of your portfolio based on the live stock data.
You can exit the program by typing exit when prompted.
