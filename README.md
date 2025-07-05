📄 Multiple PDF Chat using LangChain, OpenAI, and Streamlit
Interact with the contents of multiple PDF documents using natural language!
This app combines LangChain, OpenAI GPT (gpt-4o), FAISS, and Streamlit to build a conversational PDF assistant using RAG (Retrieval-Augmented Generation).

🚀 Features

✅ Upload and chat with multiple PDFs
🧠 Uses LangChain’s ConversationalRetrievalChain
🔍 Retrieves relevant document chunks using FAISS
💬 Supports streaming responses from GPT-4o
💡 Maintains chat memory for multi-turn conversations
⚡ Built with Streamlit for a simple UI

🧠 How It Works

Upload PDFs via Streamlit UI
Extract text with PyPDFLoader
Split content into chunks using RecursiveCharacterTextSplitter
Generate embeddings using OpenAI
Store and retrieve using FAISS
Feed retrieved context into GPT-4o to answer user questions

🛠️ Tech Stack

Python
Streamlit
LangChain
OpenAI (gpt-4o)
FAISS (for vector similarity search)
PyPDFLoader (PDF text extraction)
.env (for managing secrets)


⚙️ Setup Instructions
1. Clone the Repository
git clone https://github.com/avineshgh/Multiple-PDF-Chat-RAG.git
cd Multiple-PDF-Chat-RAG

2. Create .env File
Create a .env file in the project root and add your OpenAI key:
OPENAI_API_KEY=your_openai_key_here

3. Install Requirements
pip install -r requirements.txt

4. Run the App
streamlit run app.py


💬 Example Questions

"Summarize the key points from all documents."
"What are the common terms in these PDFs?"
"What does section 3.2 mention in the second PDF?"


🙌 Acknowledgements

LangChain
OpenAI
Streamlit
FAISS by Facebook Research

🪪 License
This project is licensed under the MIT License.
