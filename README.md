📄 Multiple PDF Chat using LangChain, OpenAI, and Streamlit<br>
Interact with the contents of multiple PDF documents using natural language!<br>
This app combines LangChain, OpenAI GPT (gpt-4o), FAISS, and Streamlit to build a conversational PDF assistant using RAG (Retrieval-Augmented Generation).<br>
<br>
<br>
🚀 Features<br>
<br>
✅ Upload and chat with multiple PDFs<br>
🧠 Uses LangChain’s ConversationalRetrievalChain<br>
🔍 Retrieves relevant document chunks using FAISS<br>
💬 Supports streaming responses from GPT-4o<br>
💡 Maintains chat memory for multi-turn conversations<br>
⚡ Built with Streamlit for a simple UI<br>
<br>
🧠 How It Works<br>
<br>
Upload PDFs via Streamlit UI<br>
Extract text with PyPDFLoader<br>
Split content into chunks using RecursiveCharacterTextSplitter<br>
Generate embeddings using OpenAI<br>
Store and retrieve using FAISS<br>
Feed retrieved context into GPT-4o to answer user questions<br>
<br>
🛠️ Tech Stack
<br>
Python<br>
Streamlit<br>
LangChain<br>
OpenAI (gpt-4o)<br>
FAISS (for vector similarity search<br>)
PyPDFLoader (PDF text extraction)<br>
.env (for managing secrets)<br>
<br>
<br>
⚙️ Setup Instructions<br>
1. Clone the Repository<br>
git clone https://github.com/avineshgh/Multiple-PDF-Chat-RAG.git<br>
cd Multiple-PDF-Chat-RAG<br>
<br>
2. Create .env File<br>
Create a .env file in the project root and add your OpenAI key:<br>
OPENAI_API_KEY=your_openai_key_here<br>
<br>
3. Install Requirements<br>
pip install -r requirements.txt<br>
<br>
4. Run the App<br>
streamlit run app.py<br>
<br>
<br>
💬 Example Questions<br>
<br>
"Summarize the key points from all documents."<br>
"What are the common terms in these PDFs?"<br>
"What does section 3.2 mention in the second PDF?"<br>
<br>
<br>
🙌 Acknowledgements<br>
<br>
LangChain<br>
OpenAI<br>
Streamlit<br>
FAISS by Facebook Research<br>
<br>
🪪 License<br>
This project is licensed under the MIT License.
