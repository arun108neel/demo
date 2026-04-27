<h3> <b>     This is a simple RAG app      </b></h3> 
<p>This RAG app aims use any CSV files (Vulnerrability Report)  as input and binds the files in to a single file. Then allows the end user to query anything from the Vulnerrability Report. There 3 components in this RAG + CSV + Ollama.</p>

<h3> <b>    Architecture - Ollama(Local) + Hosting the App     </b></h3>
<p>

User (Browser)
   ↓
Frontend (React / Streamlit)
   ↓
Backend API (FastAPI / Flask)
   ↓
RAG Pipeline
   ↓
CSV (stored as embeddings in vector DB)
   ↓
Ollama running on your machine/server
</p>

 