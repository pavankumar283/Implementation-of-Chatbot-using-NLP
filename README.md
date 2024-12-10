# Implementation-of-Chatbot-using-NLP
## Overview
Develop a conversational chatbot that can understand and respond to user queries using Natural Language Processing (NLP) techniques.

## Description:
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
## Features
- Understands various user intents such as greetings, farewells, gratitude, and more.
- Provides relevant responses based on user input.
- Maintains a conversation history that can be viewed by the user.
- Built using Python and leverages popular libraries for NLP and machine learning.

## How to Use

1. Upon running the application, a Streamlit interface will open in your web browser.

2. You will see a chat interface with a message input box labelled "What is up?"

3. Start a conversation by typing a message in the input box and pressing Enter.

4. The chatbot will respond to your message, and the conversation will continue. You can ask questions or have a general chat with the bot.

5. The conversation history will be displayed in the chat interface, with user and assistant messages shown.

6. The chatbot is powered by an NLP model and can provide responses based on the conversation's context.

7. To stop the chatbot, simply close the Streamlit interface or the terminal where it's running.

   ## Technologies Used
- **Python**
- **NLTK**
- **Scikit-learn**
- **Streamlit**
- **JSON** for intents data

  ## Usage
To run the chatbot application, execute the following command:
```bash
streamlit run app.py
```

Once the application is running, you can interact with the chatbot through the web interface. Type your message in the input box and press Enter to see the chatbot's response.

---

## Intents Data
The chatbot's behavior is defined by the `intents.json` file, which contains various tags, patterns, and responses. You can modify this file to add new intents or change existing ones.

---

## Conversation History
The chatbot saves the conversation history in a CSV file (`chat_log.csv`). You can view past interactions by selecting the "Conversation History" option in the sidebar.

---

## Contributing
Contributions to this project are welcome! If you have suggestions for improvements or features, feel free to open an issue or submit a pull request.

---
#Outcome:
A fully functional chatbot capable of understanding and responding to natural language inputs, providing an interactive and user-friendly experience.

## Acknowledgments
- **NLTK** for natural language processing.
- **Scikit-learn** for machine learning algorithms.
- **Streamlit** for building the web interface.

---

Replace `<repository-url>` and `<repository-directory>` with the actual URL of your repository and the name of the directory where the project is located. Adjust any sections as necessary to better fit your project's specifics.

