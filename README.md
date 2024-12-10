# Implementation-of-Chatbot-using-NLP
## Overview
Develop a conversational chatbot that can understand and respond to user queries using Natural Language Processing (NLP) techniques.

##Description:
This project involves creating an interactive chatbot that uses NLP to process and understand natural language input. The chatbot will simulate human conversation, providing responses based on the user's input. It can be designed to handle tasks like answering frequently asked questions, assisting with navigation, or offering general information.
## Installation

### 1. Clone the Repository
```bash
git clone <repository-url>
cd <repository-directory>
```

### 2. Create a Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### 3. Install Required Packages
```bash
pip install -r requirements.txt
```

### 4. Download NLTK Data
```python
import nltk
nltk.download('punkt')
```
## Prerequisites

Before you can run this chatbot, make sure you have the following prerequisites installed:

- Python
- Streamlit
- OpenAI Python SDK
- TOML library

You can install the required libraries using `pip`:

```bash
pip install streamlit openai toml

## How to Use

1. Upon running the application, a Streamlit interface will open in your web browser.

2. You will see a chat interface with a message input box labelled "What is up?"

3. Start a conversation by typing a message in the input box and pressing Enter.

4. The chatbot will respond to your message, and the conversation will continue. You can ask questions or have a general chat with the bot.

5. The conversation history will be displayed in the chat interface, with user and assistant messages shown.

6. The chatbot is powered by an NLP model and can provide responses based on the conversation's context.

7. To stop the chatbot, simply close the Streamlit interface or the terminal where it's running.
