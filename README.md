# GeminiRAG-AI 🔍💬

**GeminiRAG-AI** is a multimodal, retrieval-augmented generation (RAG) project that leverages the power of Google's **Gemini 1.5** models. This project combines image and text input, embeddings, and conversational AI to create intelligent, context-aware outputs.

---

## 🚀 Features

- 🧠 **Text Generation** – Generate intelligent answers, summaries, and blog posts from user prompts.
- 🖼️ **Image + Prompt → Blog** – Upload an image and generate descriptive blog content.
- 💬 **Conversational Memory** – Engage in multi-turn chat with persistent memory using Gemini's `start_chat()`.
- 🔎 **Content Embedding** – Embed user input, documents, or chat logs for semantic search.
- 🛡️ **Safety-Aware Prompts** – Includes safety setting integration to detect and filter unsafe content.

---

## 🧠 What is RAG?

**Retrieval-Augmented Generation (RAG)** is an AI technique that:
1. **Retrieves relevant context** (via embeddings or documents).
2. **Generates answers** based on both the prompt and the retrieved information.

This project demonstrates a simplified RAG pipeline using Google's `embedding-001` model and `gemini-1.5-flash`.

---

## 📦 Tech Stack

- Python 3.10+
- [Google Generative AI SDK (`google.generativeai`)](https://pypi.org/project/google-generativeai/)
- Gemini 1.5 (Flash variant)
- PIL (for image handling)
- IPython (for Markdown rendering)
- Optional: Gradio (for UI deployment)

---

## 🔧 Setup Instructions

### 1. Install Dependencies

```bash
pip install -U google-generativeai pillow
