
<tr>
<td width="50%" valign="top">

### [DocSupport](https://github.com/VishnuVardhanReddyKothapuli/DocSupport)

**Agentic RAG knowledge assistant**

A full-stack document-grounded AI assistant that processes PDFs, web pages, YouTube transcripts, and text to deliver context-aware answers with source citations.

**Highlights**
- LangGraph-based agentic RAG orchestration
- PostgreSQL with pgvector and HNSW vector search
- Evidence sufficiency checks and deterministic abstention
- Prompt-injection defense and answer-grounding validation
- Asynchronous ingestion using Celery and Redis
- Langfuse tracing for pipeline latency, token usage, and grounding evaluation
- Citation-aware React workspace

**Technology Stack**

`Python` `FastAPI` `LangGraph` `PostgreSQL` `pgvector` `Groq` `React` `TypeScript` `Celery` `Redis` `Langfuse`

</td>
<td width="50%" valign="top">

### [Local RAG PDF Q&A Bot](https://github.com/VishnuVardhanReddyKothapuli/Local-RAG-PDF-QnA-Bot)

**Local-first document question answering**

A document Q&A application designed to retrieve relevant PDF passages and answer questions using a locally served language model.

**Pipeline**

```text
PDF → Text Extraction → Chunking
   → Embeddings → ChromaDB
   → Retrieval → Ollama / Llama
   → Context-aware Answer
```

`Python` `LangChain` `FastAPI` `ChromaDB` `Ollama` `Hugging Face`

</td>
</tr>
