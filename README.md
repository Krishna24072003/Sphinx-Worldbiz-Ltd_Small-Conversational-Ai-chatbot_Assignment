## Small Conversational AI Chatbot
This repository contains the code and documentation for a small conversational AI chatbot developed as an assignment for Sphinx Worldbiz Ltd. 
This repository contains a simple rule-based conversational AI chatbot built using Python and the Natural Language Toolkit (NLTK).
The chatbot is designed to simulate basic conversations and provide **pre-defined responses based on input patterns**.
## Features
1.Greets users with a friendly introduction.
2.Handles basic queries like greetings, asking for the chatbot's name, and casual questions.
3.Provides responses based on regular expression patterns.
4.Easy to customize and expand with more patterns and responses.
5.Includes functionality to quit the conversation.

## How It Works
The chatbot leverages the nltk.chat.util.Chat class to match user input against predefined regular expression patterns. 
It uses reflections, a built-in dictionary that handles conversational shifts between first-person and second-person pronouns.

## Basic Chatbot Flow:
1.The user interacts with the chatbot through text input.
2.The chatbot matches the input to pre-defined patterns.
3.Based on the pattern, the chatbot provides an appropriate response.
4.The chatbot continues the conversation until the user types "quit."

# Requirements
To run the chatbot locally, ensure that you have the following dependencies installed:

1. Python 3.11
2. Jupyter Notebook
3. NLTK

## Example Interaction
##Type 'quit' to exit the conversation.
Hi, I'm AIChatbot.How can I assist you today
User:  what is your name?
AIChatbot: My name is AIChatbot and I'm here to assist you!
User:  I want to apply for leave
AIChatbot: which type of leave?
User:  Casual leave
AIChatbot: how many days and date
User:  5 days from 16-OCT-2024
AIChatbot: Thanks for the information, you can follow the link https://sphinx.shrmpro.com/
User:  quit
AIChatbot: None




