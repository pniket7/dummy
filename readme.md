**1.TITLE:**

- ELLO-Financial Advisor Chatbot

**2.OVERVIEW:**

- This project implements a Financial Advisor Chatbot app on a Streamlit user interface.
- The chatbot is designed to interact with users, provide financial advice, and guide them through the loan application process.

**3.PROJECT STRUCTURE:**

- env.example: Template file for environment variables. Should be renamed to .env and filled with the appropriate values.
- gitignore: Specifies files and directories to be ignored by version control. .env is ignored to keep sensitive information secure.
- Dockerfile: Docker configuration file for building the project's containerized environment.
- chat.py: Main script containing the chatbot logic and Streamlit user interface.
- requirements.txt: List of Python dependencies required for the project.

**4.PREREQUISITES:**

- Python 3.9 or later installed.
- Docker installed (optional).

`     `**5.SETUP:**

- Clone the repository-
  “<https://github.com/PearlThoughts/banker-Ai>”
- Navigate to the Project Directory-
  “cd banker-Ai”
- Create a Virtual Environment-
  “python -m venv venv”

- Activate the virtual environment-

On Windows-

“.\venv\Scripts\activate”

On macOS/Linux-

“source venv/bin/activate”

- Install the required dependencies-

“pip install -r requirements.txt”

- Set up the environment variables-

Create a copy of env.example and rename it to .env.

Open .env and replace OPENAI\_API\_KEY="sk-" with your actual OpenAI API key.

- Run the Streamlit app-

“streamlit run chat.py”

` `**6.USAGE:**

- Open the Streamlit app in your browser.
- Enter your messages in the input field and click "Send" to interact with the chatbot.
- Follow the conversation flow as instructed by the financial advisor chatbot.
- Start a new conversation or exit the chat using the provided buttons.







