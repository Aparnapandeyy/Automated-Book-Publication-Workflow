# 📚 Automated Book Publication Workflow

A multi-agent, AI-powered pipeline that automates book content generation, rewriting, review, and storage — all while keeping humans in the loop.

---

## 🎯 Objective

Fetch content from a public domain book URL, apply AI-driven "spinning" (rewriting), enable iterative human feedback, and store multiple versions with intelligent search and retrieval.

---

## 🧠 Key Features

- ✅ **Web Scraping** from Wikisource using `requests` and `BeautifulSoup`
- 🤖 **AI Writer** using Hugging Face `FLAN-T5` (free model)
- ✍️ **AI Reviewer** for grammar/style suggestions
- 🧑‍💻 **Human-in-the-Loop** editing with feedback
- 🗂️ **Versioning** using `ChromaDB`
- 🔍 **RL-style Smart Retrieval** using vector search and intelligent querying

---

## 🔧 Tech Stack

| Tool            | Purpose                                |
|-----------------|----------------------------------------|
| Python          | Core development language              |
| Google Colab    | Execution environment                  |
| Hugging Face    | AI-powered writing & reviewing         |
| BeautifulSoup   | HTML parsing for scraping              |
| ChromaDB        | Lightweight vector DB for versioning   |
| Transformers    | Access to FLAN-T5 and related models   |

---

## 📁 File Structure


---

## 🚀 Run in Google Colab

> Open the notebook and execute cells in order. It covers all six steps.

**[▶️ Colab Notebook](https://colab.research.google.com/drive/1fvsuDZvZ9sWBbb1qVUNRByhg8-3r-fPb#scrollTo=UjoC0Rk-x1gK)**

## 📹 Demo Video: [Insert YouTube/Drive link after recording]

---

## 📦 Install Dependencies (if running locally)

```bash
pip install transformers torch sentencepiece beautifulsoup4 requests chromadb
