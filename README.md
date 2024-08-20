# LLM-local-RAG
A locally-hosted Retrieval Augmented Generation pipeline for querying a Large Language Model on YOUR documents.

Based on the framework by [Local-rag-Example](https://blog.duy.dev/build-your-own-rag-and-run-them-locally/) with [Ollama](https://ollama.com/), [LangChain](https://www.langchain.com/) and [Streamlit](https://streamlit.io/).

## Install and Run Ollama

Visit and download https://ollama.com/download

Unzip Ollama.app and move to Applications folder.

Open a terminal and execute:
```
ollama pull llama3.1
ollama serve
```

## Clone repo and setup dependencies
```
git clone https://github.com/Sydney-Informatics-Hub/LLM-local-RAG/
cd LLM-local-RAG
conda create -n localrag python=3.11 pip
conda activate localrag
pip install langchain streamlit streamlit_chat chromadb fastembed pypdf langchain_community
```

## Run the Frontend
```
streamlit run app.py
```



