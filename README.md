# Introduction

This repository serves to test the naive extent of OpenAI's GPT-OSS model via Ollama with Langchain through a FastAPI interface.

The repository is package managed and served with UV and Python 3.11. Documentation on UV can be found here: [![UV]](https://docs.astral.sh/uv/concepts/projects/dependencies/).

Vector Database is using ChromaDB (the free version). documentation on Chroma can be found here:  [![Chroma]](https://www.trychroma.com/home).

---

## Purpose

This application is to be used as a RAG system for .pdf and .docx documents that can chat with OpenAI's localized GPT-OSS model. Utilizing a localized LLM improves security and customization.
Additionally, the application leverages free-to-use tools, creating a platform for an unlimited multimodal free use. In use models, orchestration, and system prompting are bespoke and interchangable.

---

## Web Page Example

<img width="1088" height="1290" alt="Screenshot 2025-09-22 at 1 41 56 PM" src="https://github.com/user-attachments/assets/12ac592e-6cd5-4aa8-9038-6d57491d2638" />

---

## Additional Credit

Original format and Chroma connectivity forked from: [![Original Repo]](https://github.com/firstpersoncode/local-rag)

---

---

## Future Considerations

- Continous conversation (follow up caching)
- Powerpoint handling
- Speed (current runtime varies by machine given localized LLM dependencies)
- Selection of documents within a Collection for response targeting
- Multiple collections

---
