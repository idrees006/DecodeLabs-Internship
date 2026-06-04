# 🤖 DEC0DE_BOT v1.0 | Rule-Based AI Chatbot

A intelligent command-line chatbot built with Python that demonstrates explicit control flow logic and interactive user engagement. This project is part of the **DecodeLabs AI Engineering Internship (Batch 2026)**.

---

## 📋 Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [How to Run](#how-to-run)
- [Usage Examples](#usage-examples)
- [Project Structure](#project-structure)
- [Skills Demonstrated](#skills-demonstrated)
- [Author](#author)

---

## 🎯 Project Overview

**DEC0DE_BOT** is a rule-based chatbot that simulates human interaction using explicit if-else logic. It showcases fundamental AI concepts including:
- Continuous loop execution
- Input normalization and validation
- Conditional response logic
- Nested conditions for enhanced user experience
- Graceful error handling

This project demonstrates the ability to build interactive systems with structured control flow—a key foundation for AI development.

---

## ✨ Features

✅ **Interactive Conversations** - Natural dialogue with users  
✅ **Smart Greetings** - Recognizes multiple greeting variations  
✅ **Help System** - Users can ask "help" to see available commands  
✅ **Nested Logic** - Follow-up questions for intelligent responses  
✅ **Graceful Exit** - Multiple exit commands recognized  
✅ **Error Handling** - Catches and handles interruptions safely  
✅ **Empty Input Handling** - Responds to silent inputs  

---

## 📦 Requirements

- Python 3.7 or higher
- No external dependencies required (uses only built-in `sys` module)

---

## 🚀 Installation

1. **Clone the repository** (or download the project)
   ```bash
   git clone https://github.com/idrees006/DecodeLabs-Internship.git
   cd DecodeLabs-Internship
   ```

2. **Verify Python is installed**
   ```bash
   python --version
   ```

---

## ▶️ How to Run

Run the chatbot with a single command:

```bash
python main.py
```

Or if using Python 3 specifically:
```bash
python3 main.py
```

The chatbot will initialize and display:
```
====================================================
🤖 DEC0DE_BOT v1.0 | Rule-Based AI Chatbot initialized.
Status: Online | Type 'exit' or 'quit' to end session.
====================================================
```

---

## 💬 Usage Examples

### Start a Conversation
```
You: hello
Dec0deBot: Greetings, engineer! Welcome to the team. How can I assist you today? 💻

You: what can you do?
Dec0deBot: I am programmed to demonstrate explicit control flow logic. You can ask me:
           -> 'About your project'
           -> 'What are your skills?'
           -> 'Who built you?'

You: about your project
Dec0deBot: This is Project 1: The Rule-Based AI Chatbot for the DecodeLabs internship! 🛡️
Dec0deBot: Would you like to know the qualification criteria? (yes/no): yes
Dec0deBot: Excellent! You must complete this project to unlock next week's assignments. 🔑
```

### Available Commands
- **Greetings**: `hello`, `hi`, `hey`, `greetings`
- **Help**: `help`, `what can you do`
- **Project Info**: `project`, `about your project`
- **Skills**: `skills`, `logic`
- **Creator**: `creator`, `who built you`, `decodelabs`
- **Exit**: `exit`, `quit`, `goodbye`, `bye`

---

## 📁 Project Structure

```
DecodeLabs-Internship/
├── main.py              # Main chatbot application
├── README.md            # This file (Project documentation)
└── requirements.txt     # Project dependencies (if any)
```

---

## 🧠 Skills Demonstrated

| Skill | Implementation |
|-------|-----------------|
| **Continuous Loops** | `while True:` loop for persistent interaction |
| **Control Flow** | Nested if-elif-else statements for logic |
| **Input Processing** | `.strip().lower()` normalization |
| **Conditional Logic** | Multiple condition checks and branching |
| **Error Handling** | Try-except blocks for interruptions |
| **User Interaction** | Dynamic input/output engagement |

---

## 🎓 Qualification Criteria Met

✅ Continuous loop requirement  
✅ Exit commands functionality  
✅ Explicit if-else logic  
✅ Greeting system implementation  
✅ Nested conditions for smart responses (Bonus Milestone)  
✅ Graceful error handling  

---

## 🚀 Future Enhancements

- [ ] Add more sophisticated NLP using libraries (NLTK, spaCy)
- [ ] Implement database for conversation history
- [ ] Add machine learning for improved response matching
- [ ] Create a GUI interface using Tkinter or PyQt
- [ ] Integrate with external APIs for real-time information
- [ ] Add sentiment analysis for emotional awareness

---

## 📝 Author

**DecodeLabs AI Engineering Intern** | Batch 2026  
🔗 [GitHub Profile](https://github.com/idrees006)

---

## 📞 Support & Questions

For questions about this project, feel free to:
- Open an issue on GitHub
- Contact the DecodeLabs team
- Review the inline code comments for detailed logic explanations

---

## ⭐ Show Your Support

If you found this project helpful, please give it a ⭐ star on GitHub!

---

**Happy Coding! 🚀**
