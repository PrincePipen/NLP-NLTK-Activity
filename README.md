# Simple Chatbot with Pattern Matching

This project is a simple conversational chatbot built using Python and the NLTK library (Project 7).
It tokenizes user input, identifies keywords, and responds based on pattern matching using regular expressions.
It also includes a feature to compare two NLTK techniques: Lemmatization vs. Stemming, fulfilling the +3 bonus points requirement.

## Prerequisites

Ensure you have Python 3.x installed on your system.

## Setup Instructions

1.  **Install dependencies:**
    Open a terminal in the project directory and run the following command to install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

2.  **Run the application:**
    Run the chatbot script using Python:
    ```bash
    python chatbot.py
    ```
    The script will automatically download the necessary NLTK corpora (`punkt`, `wordnet`, `averaged_perceptron_tagger`) on its first run.

## Features & Usage

*   **Chat:** Once the application starts, you can converse with the bot by typing your messages.
*   **Technique Comparison:** To see a comparison between Lemmatization and Stemming (Bonus Points), type `!compare <your sentence>` in the chat prompt. For example: 
    `!compare The quick brown foxes are running fast.`
*   **Quit:** Type `quit` to exit the chat session.
