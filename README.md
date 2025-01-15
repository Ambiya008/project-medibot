Medibot: AI-Powered Medical Chatbot
1. Project Details
   
Medibot is an AI-powered medical chatbot designed to provide accurate health information and support. It leverages advanced language models to process user queries, retrieve relevant medical data, and generate responses. The chatbot integrates LangChain, Hugging Face models, and FAISS for document search and retrieval.

3. Features
   
Medical Document Search: Extracts information from PDF medical documents.
Intelligent Query Processing: Uses Hugging Face sentence transformers for embeddings.
Memory Support: Integrates FAISS to create and store vectorized embeddings for fast retrieval.
Streamlit Interface: A user-friendly web application for interaction with the chatbot.
Customizable Knowledge Base: Easily add new documents to expand the chatbot's knowledge.

5. Prerequisites
 
Before you begin, ensure you have the following installed:

Python 3.9+

Git: For version control.

Pip: Python package manager.

Hugging Face Access Token: Required to access Hugging Face models.



8. Installation
   
Follow these steps to set up the project locally:

Clone the repository:

git clone https://github.com/Ambiya008/project-medibot.git

cd project-medibot

Create a virtual environment and activate it:

python -m venv venv

source venv/bin/activate  # Linux/Mac

.\venv\Scripts\activate   # Windows

Install the required dependencies:

pip install -r requirements.txt

10. Configuration
Create a .env file in the root directory to store sensitive information:

makefile

HF_ACCESS_TOKEN=your_hugging_face_access_token

Ensure .env is added to .gitignore to prevent pushing it to GitHub.




13. Running the Application
14. 
Run the following command to start the chatbot interface:

streamlit run medibot.py

Access the application at http://localhost:8501.

16. Project Structure
    
The project directory is organized as follows:

![Screenshot (118)](https://github.com/user-attachments/assets/c14157df-0344-4d43-ba63-6f73cc2cd172)

18. Technology Used
    
Frontend

Streamlit: A lightweight web application framework for Python.

Backend

Python 3.9+: For core logic.

LangChain: To manage interaction between the chatbot and knowledge base.

Hugging Face Transformers: For embeddings using pre-trained language models.

FAISS: For efficient vector search and retrieval.




20. Running the Application
    
Run the following command to start the chatbot interface:

streamlit run medibot.py

Access the application at http://localhost:8501.



some screenshots of my project:
![Screenshot (115)](https://github.com/user-attachments/assets/eac8f004-e16f-40c4-ba5e-5367c573d9fc)
![Screenshot (117)](https://github.com/user-attachments/assets/81a93d30-8669-4c38-966b-9974a6dd5997)
![Screenshot (116)](https://github.com/user-attachments/assets/83d47a16-97aa-46af-a4e1-d4dc5a8862d4)









