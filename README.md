# RAG + Agents with Mistral AI

Built from scratch — no LangChain, no magic libraries.

## What's inside

- **LLM API** — basic call with Mistral
- **Embeddings** — text to vectors with mistral-embed
- **Retrieval** — cosine similarity search
- **RAG** — retrieval + generation pipeline
- **Agent** — tool calling + ReAct loop
- **RAG + Agent** — combined: agent decides when to search docs

## Stack
- Mistral AI API
- numpy (vector search)
- python-dotenv

## Run

```bash
pip install mistralai numpy python-dotenv
```

Add a `.env` file with your `MISTRAL_API_KEY`, then open the notebook.
