# DMV-Bot🚦

This is a Streamlit application that allows you to interact with a chatbot designed to provide answers to your questions about DMV processes and requirements. The chatbot is powered by OpenAI's GPT-4 language model and is trained using a dataset of DMV documents, FAQs, and other relevant resources.

To use the app, enter your OpenAI API key and type your question into the text input box. The chatbot will respond based on its knowledge of DMV guidelines and the documents it was trained on.

### Requirements:
- Python 3.6 or higher
- Streamlit
- PyPDF2
- Langchain

### Installation:
1. **Clone this repository**:
    ```bash
    git clone https://github.com/sahithichikkela/CaliforniaDMVBot.git
    ```

2. **Install the required dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

### Usage:
1. **Run the Streamlit app**:
    ```bash
    streamlit run app.py
    ```

2. **Enter your OpenAI API key** into the text input box and click "Submit."

3. **Ask your question** in the input box and click the "Chat" button. The chatbot will generate a response in the output box below.
