🤖 Simple Python Chatbot

A basic rule-based chatbot built using Python. This chatbot analyzes user input and responds based on predefined patterns and probabilities.

📌 Features
Simple and lightweight chatbot
Uses word matching and probability logic
Handles greetings, farewells, and common queries
Supports custom long responses
Easy to extend with new responses

🛠️ Technologies Used
Python
Regular Expressions (re module)

⚙️ How It Works
User enters a message
Input is cleaned and split into words
Each predefined response is checked:
Matches words with input
Calculates probability score
The response with the highest probability is selected
If no good match → returns unknown response.

