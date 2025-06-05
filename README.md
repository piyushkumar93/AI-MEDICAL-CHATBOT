🧠 AI Medical Chatbot
An intelligent and interactive AI-powered chatbot designed to provide general medical information and assist users with basic health-related queries. This project leverages natural language processing and vector-based memory to simulate human-like conversation in the healthcare domain.

📌 Features
✅ Conversational AI: Interacts with users in natural language to address medical-related questions.

🧬 Medical Memory Integration: Uses vector stores to retain and retrieve relevant information efficiently.

🔐 Secure & Modular: .env file for managing sensitive tokens and environment variables.

📦 Lightweight & Extendable: Easily extend the chatbot with additional medical data or memory types.

💬 LangChain Integration: Makes use of LangChain and Hugging Face for advanced NLP tasks.

🛠️ Tech Stack
Technology	Description
Python	Core programming language
LangChain	Framework for building with LLMs
Hugging Face	Language models for processing user queries
FAISS	Vector database for semantic search
OpenAI / Transformers	LLM support (optional)
VS Code + Git	Development and version control

🧾 Setup Instructions
1. Clone the Repository

git clone https://github.com/piyushkumar93/AI-MEDICAL-CHATBOT.git
cd AI-MEDICAL-CHATBOT

2. Create a Virtual Environment

python -m venv venv
source venv/bin/activate      # On Windows: venv\Scripts\activate

3. Install Dependencies
pip install -r requirements.txt

5. Configure Environment Variables
Create a .env file in the root directory:


HUGGINGFACE_API_KEY=your_key_here
OPENAI_API_KEY=your_key_here
(This file is already added to .gitignore)

5. Run the Bot
python medibot.py


📂 Project Structure

medical-chatbot-main/
│
├── data/                       # Sample or medical text data
├── vectorstore/db_faiss/      # Vector DB index files
├── connect_memory_with_llm.py # Handles LangChain memory connection
├── medibot.py                 # Main chatbot script
├── .env                       # Environment variables (excluded in git)
├── .gitignore
├── README.md
└── Pipfile / requirements.txt

🧠 Use Cases
💬 Patient FAQs

🔍 Initial symptom checking

📚 Educational tool for medical awareness

🏥 Triage automation prototype

⚠️ Disclaimer
This chatbot is for educational and demonstrative purposes only. It does not provide professional medical advice. Always consult a licensed healthcare provider for medical concerns.

🙌 Contributions
Contributions, suggestions, and improvements are welcome! Feel free to open issues or submit PRs.

📬 Contact
Created with ❤️ by PIYUSH KUMAR

