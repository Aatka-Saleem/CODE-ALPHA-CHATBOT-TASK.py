ChatBotApp

A simple chatbot application built with Tkinter and NLTK.

Features

- Basic conversation functionality with predefined pairs
- User input and bot response display
- Scrollable chat history
- Send button for submitting user input

Technical Details

- Built with Tkinter for the GUI
- Uses NLTK for chat functionality
- Predefined conversation pairs in the conversation_pairs list
- Chatbot responds based on user input using the respond() method

Code Structure

- ChatBotApp class defines the chatbot application
- __init__ method initializes the chatbot and sets up the GUI
- send method handles sending user input and displaying the response

Conversation Pairs

- Defined in the conversation_pairs list
- Each pair contains a regular expression pattern and a list of possible responses
- The chatbot responds based on the first matching pattern

GUI

- Window title: "CHATBOT"
- Window geometry: 580x660
- Window background color: #2F4F4F
- Label frame background color: #5D478B
- Chat history text widget background color: #5D478B
- Chat history text widget foreground color: #FFFFFF
- Entry field background color: #DCDCDC
- Submit button background color: #5D478B
