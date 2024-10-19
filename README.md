Chat-with-your-code

This project is a chatbot designed to enable users to interact with their codebase through the OpenAI Language Model (LLM). It leverages a Streamlit app to offer a simple and intuitive chat interface for user interaction.
Features

ChatGPT

Users can input their OpenAI key and GitHub repository name. The repository is cloned, split into smaller sections, and embedded. LangChain is used to create a Q&A retriever, allowing users to chat with and ask questions about their code. The chat interface makes it easy to interact with the codebase.
To use this codebase chatbot, follow these steps:

    Clone the repository:

git clone https://github.com/Ankitsingh0805/ChatWithYourCode.git

    Install the required dependencies:

pip install -r requirements.txt

    Get your OpenAI API Key and add it here
    Set up a free account on Deeplake and store the API key

    Run the Streamlit app:

streamlit run main.py

Access the chat interface by opening your web browser and navigating to http://localhost:8501.

Enter your OpenAI key and the name of your GitHub repository in the provided input fields.

The codebase will be chunked and embedded, and the chat interface will be displayed.

Ask questions or provide instructions using natural language, and the chatbot will respond accordingly.
Limitations

    The codebase chatbot relies on the OpenAI Language Model and its capabilities.
    Large codebases or repositories with complex structures may take longer to chunk and embed.
    The accuracy and quality of responses depend on the accuracy of the language model and the code embeddings.


