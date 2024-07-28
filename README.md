# Search Engine Using LLMs with LangChain

This project is a sophisticated search engine application built using LangChain, leveraging the power of Large Language Models (LLMs). The search engine is designed to process natural language queries and provide accurate, relevant answers by integrating advanced AI models and various tools. This innovative solution showcases how AI can be harnessed to enhance search capabilities, making information retrieval more intuitive and efficient.

## Features

- **Natural Language Understanding**: Handles complex queries phrased in natural language.
- **Integrated Tools**: Utilizes tools such as Wikipedia API for comprehensive information retrieval.
- **Mathematical Problem Solving**: Includes capabilities to solve mathematical questions using LLM-based reasoning.
- **Interactive Interface**: User-friendly interface built with Streamlit for seamless interaction.
- **State Management**: Maintains conversation history for context-aware responses.

## Technologies Used

- **LangChain**: For chaining together language models and other tools.
- **Streamlit**: For creating an interactive web interface.
- **Wikipedia API**: For fetching information from Wikipedia.
- **Python**: Core programming language for implementation.

## Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/sharad-18/Search-Engine-using-LLMs.git
    cd Search-Engine-using-LLMs
    ```

2. **Create a Virtual Environment**:
    ```bash
    python -m venv env
    source env/bin/activate  # On Windows, use `env\Scripts\activate`
    ```

3. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Set Up API Keys**:
    - Obtain the necessary API keys (e.g., Groq API Key for language models).
    - Add your keys to the `config.py` file or set them as environment variables.

5. **Run the Application**:
    ```bash
    streamlit run app.py
    ```

## Usage

1. **Open the Application**:
   - Navigate to the URL provided by Streamlit (typically `http://localhost:8501`) in your web browser.

2. **Enter Your Query**:
   - Use the text input area to type in your question or search query.
   - Press the "Find My Answer" button to get the response.

3. **View Responses**:
   - The assistant will process your query and display the response below the input area.
   - Previous interactions will be displayed, maintaining a conversation history.


