The most interesting thing I've built so far is **ContractIQ**, an AI-powered contract intelligence application that combines multiple AI technologies into one desktop application.

It can extract and classify legal clauses, generate contract summaries, answer questions using RAG, and compare two contract versions to highlight changes.

I used **Llama 3 through Ollama** for extraction, summarization, and question answering; **RoBERTa** for legal clause classification; **Sentence Transformers and FAISS** for semantic search and retrieval; and **PyMuPDF** for PDF processing. I built the desktop interface using **PySide6** and used background threads to keep it responsive.

One thing I'm particularly proud of is that it can run locally on a user's computer. Since contracts often contain sensitive information, this allows users to process documents without sending them to external AI APIs by default.

I also created a **README** documenting the project, its features, technology stack, setup instructions, and usage.

Building ContractIQ gave me hands-on experience combining LLMs, RAG, traditional machine learning, and software engineering to create a complete application rather than just a standalone AI model.
