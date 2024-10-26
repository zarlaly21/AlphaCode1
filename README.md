# AlphaCode1
#Task 01 
Hangman Game
This Python Hangman game is a console-based program where players guess letters to figure out a randomly chosen word within a limited number of attempts. The code follows these steps:
Setup: A word list of colors is provided, and get_word() selects one at random.
Gameplay: In the play(word) function, the player has 6 attempts to guess either letters or the entire word. Correct guesses reveal letters; incorrect guesses draw parts of a hangman using display_hangman().
Tracking: Guessed letters and words are stored to prevent duplicates.
Loop: main() initiates the game, offering the player the option to play again after each round.
With each incorrect guess, a part of the hangman is drawn until the player either guesses the word or loses.
This project is a basic chatbot built with Python and machine learning, designed to interact with users by understanding and responding to simple queries. It uses natural language processing (NLP) to identify user intentions (intents) and responds from a predefined set of answers stored in an intents.json file. The model is trained using Keras to recognize patterns in text, employing tokenization and lemmatization for better accuracy.

#Task 2
This project is a machine learning-powered chatbot that uses natural language processing (NLP) to interact with users. Built with Python, the chatbot can understand user queries, match them to predefined intents, and respond accordingly, simulating a real conversation.

Key Features:

Intent Recognition: The chatbot can recognize various types of user intents, such as greetings, farewells, questions, and requests for information.
Response Generation: For each recognized intent, the chatbot provides a relevant response from a predefined set, ensuring engaging and coherent dialogue.
Model Training: Using Keras, the model is trained on a dataset (intents.json) containing different patterns (input examples) and responses to help the chatbot understand various ways users might phrase their questions or statements.
Tokenization and Lemmatization: The chatbot preprocesses user inputs by tokenizing and lemmatizing to reduce words to their base form, improving the accuracy of intent recognition.
Persistence of Knowledge: The chatbot saves pre-trained model weights and vocabulary using pickle, ensuring that these components don’t need to be reprocessed on every interaction.
Technology Stack:

Python: Primary programming language.
Keras: For building and training the neural network model.
NLTK: Used for text preprocessing, including tokenization and lemmatization.
JSON: Storing intents, patterns, and responses.
The chatbot can serve as a conversational agent for basic tasks or educational purposes, providing an accessible interface for users while showcasing fundamental machine learning and NLP techniques.
