# RAGVerse

###### RAGVerse is a modular, LLM-powered Retrieval-Augmented Generation (RAG) pipeline that scrapes web content, embeds it using state-of-the-art embeddings (like nomic-embed-text via Ollama), stores the embeddings in Astra DB (powered by Cassandra), and serves contextual answers using Groq-hosted LLMs (like llama3-70b) through LangChain.

## setup
```bash
  uv venv .venv
  source .venv/bin/activate
```
```bash
  uv pip install -r requirements.txt
```
