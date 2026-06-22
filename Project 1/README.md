# 🤖 KHAN — AI Chatbot

A beginner-friendly AI assistant built with Python as part of an AI engineering training project at **DecodeLabs**. KHAN is a rule-based conversational chatbot that responds to common questions about Artificial Intelligence, Machine Learning, and Deep Learning.

---

## 📌 Features

- Greets users by name and tracks conversation turns
- Responds to common AI-related questions using a keyword-matching engine
- Handles unrecognized inputs gracefully
- Tracks session duration and logs end time on exit
- Simple, readable Python code — great for beginners

---

## 🚀 Getting Started

### Prerequisites

- Python 3.x

No external libraries required — only the Python standard library (`datetime`).

### Installation

```bash
git clone https://github.com/your-username/khan-ai-chatbot.git
cd khan-ai-chatbot
```

### Running the Chatbot

```bash
jupyter notebook "Artificial intelligence P1.ipynb"
```

Or run the notebook cells in order inside Jupyter.

---

## 💬 Sample Conversation

```
Enter your name: Seif
KHAN: Nice to meet you, Seif! I'm KHAN, your AI assistant. Type 'exit' to quit.

Seif: what is deep learning
KHAN: Deep Learning is a type of Machine Learning that uses neural networks with many layers to understand complex patterns like images and speech.

Seif: bye
KHAN: Goodbye! Have a great day.

Seif: exit
KHAN: Goodbye, Seif! We had 2 exchanges.
Session ended at 22:49:04
```

---

## 🧠 Supported Questions

| Input | Response Topic |
|---|---|
| `hello` / `hi` | Greeting |
| `how are you` | Status check |
| `what is ai` | Artificial Intelligence |
| `what is machine learning` | Machine Learning |
| `what is deep learning` | Deep Learning |
| `what is decodelabs` | About DecodeLabs |
| `who made you` | About the creator |
| `help` | Usage hint |
| `bye` | Farewell |
| `exit` | End the session |

---

## 📁 Project Structure

```
khan-ai-chatbot/
├── Artificial intelligence P1.ipynb   # Main chatbot notebook
├── requirements.txt                    # Dependencies
├── README.md                           # Project documentation
└── LICENSE                             # MIT License
```

---

## 🛠️ How It Works

1. The user enters their name to start a personalized session.
2. Each input is cleaned (lowercased and stripped) and checked against a dictionary of keyword-response pairs.
3. If a keyword is found anywhere in the user's message, the corresponding response is returned.
4. The session ends when the user types `exit`, displaying total exchange count and session end time.

---

## 📚 Built With

- Python 3
- Jupyter Notebook
- `datetime` (standard library)

---

## 👤 Author

Built by an AI Engineer in training at **DecodeLabs**.

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
