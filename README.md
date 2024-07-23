# ChatBot
# Gemini Pro Q/A Project

The Gemini Pro Q/A Project is a Streamlit web application that leverages Google's Generative AI model, Gemini Pro, to provide intelligent answers to user queries. By using the GenerativeModel from the `google.generativeai` library, this application allows users to interact with the AI through a simple web interface.

## Features

- **Interactive Q&A**: Users can input questions and receive answers generated by the Gemini Pro AI model.
- **Streamlit UI**: An easy-to-use web interface powered by Streamlit.
- **Configurable**: API keys and other configurations can be managed through environment variables.

## Installation

### Prerequisites

- Python 3.8 or higher
- A Google Generative AI API key

### Setup

1. **Create a virtual environment**:
    ```
    python -m venv env
    source env/bin/activate  # On Windows, use `env\Scripts\activate`
    ```

2. **Install dependencies**:
    ```
    pip install -r requirements.txt
    ```

3. **Set up environment variables**:
    - Create a `.env` file in the root directory.
    - Add your Google API key to the `.env` file:
      ```
      GOOGLE_API_KEY=your_google_api_key_here
      ```

## Usage

To start the application, run the following command:

```
streamlit run app.py
```

Once the server is running, open your browser and go to http://localhost:8501 to interact with the Gemini Pro Q/A application.

## How to Ask Questions
Enter your question in the input box.
Click the "Submit" button to get a response from the AI.
## How It Works
Generative Model: The application uses the Gemini Pro model from Google Generative AI to generate content based on user input.
Environment Variables: The API key for accessing Google Generative AI is managed via environment variables using the dotenv library.
Streamlit Interface: A user-friendly interface is built with Streamlit, allowing for easy interaction and visualization.

## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request for any improvements or bug fixes.



## Acknowledgments
Streamlit : https://streamlit.io/
Google Generative AI  
dotenv : https://pypi.org/project/python-dotenv/

