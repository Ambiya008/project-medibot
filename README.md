Medibot: AI-Powered Medical Chatbot
1. Project Details
Medibot is an AI-powered medical chatbot designed to provide accurate health information and support. It leverages advanced language models to process user queries, retrieve relevant medical data, and generate responses. The chatbot integrates LangChain, Hugging Face models, and FAISS for document search and retrieval.

2. Features
Medical Document Search: Extracts information from PDF medical documents.
Intelligent Query Processing: Uses Hugging Face sentence transformers for embeddings.
Memory Support: Integrates FAISS to create and store vectorized embeddings for fast retrieval.
Streamlit Interface: A user-friendly web application for interaction with the chatbot.
Customizable Knowledge Base: Easily add new documents to expand the chatbot's knowledge.
3. Prerequisites
Before you begin, ensure you have the following installed:

Python 3.9+
Git: For version control.
Pip: Python package manager.
Hugging Face Access Token: Required to access Hugging Face models.
Render Account (if deploying on Render).
4. Installation
Follow these steps to set up the project locally:

Clone the repository:

bash
Copy code
git clone https://github.com/Ambiya008/project-medibot.git
cd project-medibot
Create a virtual environment and activate it:

bash
Copy code
python -m venv venv
source venv/bin/activate  # Linux/Mac
.\venv\Scripts\activate   # Windows
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
5. Configuration
Create a .env file in the root directory to store sensitive information:
makefile
Copy code
HF_ACCESS_TOKEN=your_hugging_face_access_token
Ensure .env is added to .gitignore to prevent pushing it to GitHub.
6. Dialogflow Setup (Optional)
If you're integrating Dialogflow for additional features:


7. Running the Application
Run the following command to start the chatbot interface:

bash
Copy code
streamlit run medibot.py
Access the application at http://localhost:8501.

8. Project Structure
The project directory is organized as follows:

bash
Copy code
project-medibot/
│
├── data/                          # Folder for storing medical PDF documents
│   └── The-Gale-Encyclopedia.pdf
├── vectorstore/db_faiss/          # FAISS database files
│   ├── index.faiss
│   └── index.pkl
├── .env                           # Environment variables (not included in GitHub)
├── medibot.py                     # Main Streamlit application file
├── create_memory_for_llm.py       # Script to create memory for the LLM
├── connect_memory_with_llm.py     # Script to connect FAISS memory with the LLM
├── requirements.txt               # Project dependencies
├── README.md                      # Project documentation
└── runtime.txt                    # Python runtime version for deployment
9. Technology Used
Frontend
Streamlit: A lightweight web application framework for Python.
Backend
Python 3.9+: For core logic.
LangChain: To manage interaction between the chatbot and knowledge base.
Hugging Face Transformers: For embeddings using pre-trained language models.
FAISS: For efficient vector search and retrieval.







6. Running the Application
Run the following command to start the chatbot interface:

bash
Copy code
streamlit run medibot.py
Access the application at http://localhost:8501.

some screenshots of the project![Screenshot (117)](https://github.com/user-attachments/assets/99901798-3ea7-4b7b-8711-b0d271565818)
![Screenshot (116)](https://github.com/user-attachments/assets/b1355fc8-0301-47d5-a9bc-16c39e9ba8d8)
![Screenshot (115)](https://github.com/user-attachments/assets/b11c9a06-9a4c-4580-8752-340872112d18)


