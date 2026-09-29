# 🤖 Rule-Based AI Chatbot

A simple and interactive **Rule-Based AI Chatbot built using Python** as part of my Artificial Intelligence Internship at **DecodeLabs**.

The chatbot uses predefined rules, conditional logic, and a response dictionary to simulate a basic conversational experience. It can handle common conversations, perform mathematical calculations, provide the current date and time, and handle invalid or unknown inputs.

## 🚀 Project Overview

This project demonstrates the fundamentals of **rule-based artificial intelligence**.

Unlike machine-learning or large-language-model systems, this chatbot uses predefined rules and conditions to determine how it should respond to different user inputs.

The chatbot runs continuously in the terminal until the user enters an exit command.

## ✨ Features

- 👋 Greeting and basic conversation
- 🤖 Information about the chatbot
- 🧠 Basic AI and Python-related questions
- ➕ Addition of multiple numbers
- ➖ Subtraction of multiple numbers
- ✖️ Multiplication of multiple numbers
- ➗ Division of multiple numbers
- 📅 Current date
- 🕐 Current time
- 💬 Predefined conversational responses
- 🛡️ Empty-input validation
- ⚠️ Invalid-input and error handling
- 🚫 Division-by-zero protection
- 🔄 Continuous conversation loop
- 🚪 Multiple exit commands
- 💡 Help command

## 🛠️ Technologies Used

- **Python**
- Dictionaries
- Conditional statements
- `while` and `for` loops
- String manipulation
- User input processing
- Exception handling
- Mathematical operations
- `datetime` module

## 🧠 How It Works

The chatbot follows a simple rule-based architecture:

```text
User Input
    ↓
Input Processing
    ↓
Command / Rule Detection
    ↓
Predefined Response or Calculation
    ↓
Bot Response
    ↓
Continue Conversation
```

For conversational queries, the chatbot searches a predefined response dictionary.

For mathematical commands, it extracts the numbers from the user's input and performs the requested operation.

## 💬 Example Commands

### General Conversation

```text
hello
hi
hey
how are you
what is your name
who are you
what can you do
help
thank you
```

### AI and Python Questions

```text
what is ai
what is python
what is a chatbot
what is rule based ai
```

### Date and Time

```text
date
today
what is the date
time
current time
what time is it
```

### Mathematical Operations

```text
add 10 20
subtract 50 20
multiply 5 6
divide 100 4
```

The chatbot also supports multiple numbers:

```text
add 10 20 30
subtract 100 20 10
multiply 2 3 4
divide 100 2 5
```

Example:

```text
You: add 10 20 30
Bot: The result is 60.0
```

## 🚪 Exit Commands

The conversation can be ended using:

```text
bye
exit
quit
goodbye
```

Example:

```text
You: bye
Bot: Goodbye! Have a great day!
```

## 📂 Project Structure

```text
Rule-Based-AI-Chatbot/
│
├── smart_rule_bot.py
└── README.md
```

## ⚙️ Requirements

- Python 3.x
- VS Code or any Python-compatible IDE

The project uses only Python's standard library, including the `datetime` module. No external Python packages are required.

## ▶️ How to Run

### 1. Open the project folder

Open the project in VS Code or navigate to the project directory using the terminal.

### 2. Check Python installation

```bash
python --version
```

### 3. Run the chatbot

```bash
python smart_rule_bot.py
```

## 🖥️ Sample Output

```text
=======================================================
                 SMART BOT
          RULE-BASED AI CHATBOT
=======================================================

Hello! I'm SmartBot.
I can chat with you and perform basic calculations.
Type 'help' to see what I can do.
Type 'bye' to end the conversation.

You: hello
Bot: Hello! How can I help you today?

You: what is python
Bot: Python is a high-level programming language known
for its simple syntax and wide range of applications.

You: add 25 15
Bot: The result is 40.0

You: time
Bot: The current time is 07:30:12 PM

You: bye
Bot: Goodbye! Have a great day!

=======================================================
                 CHATBOT CLOSED
=======================================================
```

## 📚 Concepts Learned

This project helped strengthen my understanding of:

- Python fundamentals
- Dictionaries and key-value pairs
- Conditional statements
- Loops
- String methods
- User input processing
- Input validation
- Exception handling
- Mathematical operations
- Date and time handling
- Rule-based decision making
- Command-line application development

## 🎯 Learning Objective

The main objective of this project was to understand how a basic rule-based AI system processes user input and makes decisions using predefined logic.

It also provides a foundation for understanding more advanced Artificial Intelligence and Machine Learning concepts.

## 🔮 Future Improvements

Possible future improvements include:

- Expanding the chatbot's knowledge base
- Adding more conversational responses
- Supporting additional mathematical operations
- Improving natural-language input handling
- Adding conversation history
- Developing a graphical user interface
- Adding more advanced text-processing techniques

## 👨‍💻 Internship Project

**Project:** Project 1 — Rule-Based AI Chatbot  
**Domain:** Artificial Intelligence  
**Internship:** DecodeLabs  
**Technology:** Python

This project was developed as part of my **Artificial Intelligence Internship at DecodeLabs**.

## 🙏 Acknowledgement

Thanks to **DecodeLabs** for providing the opportunity to work on this project and strengthen my practical understanding of Artificial Intelligence and Python programming.

---

⭐ If you found this project interesting, feel free to explore the repository!
