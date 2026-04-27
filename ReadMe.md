<div style="background-color: #Ffff99; padding: 10px;">

<h3>  
<b ">This is a simple RAG app</b>  </h3>
</div>

<p>This RAG app aims use any CSV files (Vulnerrability Report)  as input and binds the files in to a single file. Then allows the end user to query anything from the Vulnerrability Report. There 3 components in this RAG + CSV + Ollama.</p>

<h3> <b>    Architecture - Ollama(Local) + Hosting the App     </b></h3>
<p>

User (Browser)   <br>
   &nbsp; &nbsp; ↓ <br>
Frontend (React / Streamlit) <br>
   &nbsp; &nbsp; ↓ <br>
Backend API (FastAPI / Flask) <br>
   &nbsp; &nbsp; ↓ <br>
RAG Pipeline <br>
   &nbsp; &nbsp; ↓ <br>
CSV (stored as embeddings in vector DB) <br>
   &nbsp; &nbsp; ↓ <br>
Ollama running on your machine/server <br>
</p>

 