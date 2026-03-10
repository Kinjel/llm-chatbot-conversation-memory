# LLM Chatbot with Conversation Memory

## Overview

This project implements an interactive chatbot powered by a **Large Language Model (LLM)** with persistent conversation memory. The chatbot maintains the history of user and assistant messages, enabling multi-turn conversations and contextual responses.

The system uses a modular node-based architecture to manage message preparation, model execution, and response handling.

---

## Technologies Used

* Python
* Groq API (LLaMA 3.3 Model)
* PocketFlow
* Google Colab

---

## Features

* Multi-turn conversation support
* Persistent chat memory using shared message history
* Modular workflow with separate preparation, execution, and post-processing stages
* Real-time response generation using an LLM

---

## Workflow

1. User enters a query.
2. The message is appended to the conversation history.
3. The LLM processes the message along with previous context.
4. The chatbot generates a response.
5. The response is stored in memory for future conversation turns.

---

## Example Interaction

User:

```id="chatbot_query_example"
How does machine learning work?
```

Chatbot:
Machine learning allows systems to learn patterns from data and improve predictions without being explicitly programmed.

---

## How to Run

1. Install required libraries

```id="chatbot_install_cmd"
pip install pocketflow
pip install groq
```

2. Add your Groq API key.

3. Run the notebook:

```id="chatbot_notebook_run"
llm-chatbot-conversation-memory.ipynb
```
