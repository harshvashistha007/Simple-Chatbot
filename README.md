# 🤖 Python Chatbot (Rule-Based)

A simple rule-based chatbot built using Python that interacts with users using predefined responses. The bot recognizes keywords in user input and replies accordingly, making basic conversations possible.

---

## 📌 Features

- Responds to common inputs like:
  - "hello"
  - "how are you"
  - "bye"
  - "name"
- Uses random responses for natural conversation
- Handles unknown inputs with default replies
- Continuous chat until user types **exit**

---

## 🛠️ Technologies Used

- Python 🐍
- `random` module

---

## 🚀 How It Works

- The chatbot checks user input for specific keywords  
- If a keyword matches, it selects a random response from predefined options  
- If no keyword matches, it gives a default response  

---

## ▶️ How to Run

1. Make sure Python is installed  
2. Save the file as `chatbot.py`  
3. Open terminal or command prompt  
4. Run the program:

```bash
python chatbot.py

Start chatting! Type exit to stop the bot

💡 Example
🤖 Chatbot: Hello! Type 'exit' to quit.

You: hello
🤖 Chatbot: Hi there!

You: what are you doing
🤖 Chatbot: I don't understand that.

You: bye
🤖 Chatbot: Goodbye!
📈 Possible Improvements

Add more keywords and responses

Use NLP libraries like NLTK or spaCy

Convert into GUI using Tkinter

Deploy as a web chatbot using Flask

🤝 Contributing

Feel free to fork this project and improve it. Contributions are welcome!

📄 License

This project is open-source and free to use.
