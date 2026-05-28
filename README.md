<div align="center">

# 🎥 YouTube RAG AI Learning Assistant

### 🚀 AI-Powered YouTube Video Question Answering System Built with n8n + OpenAI + Qdrant

<img src="https://img.shields.io/badge/n8n-AI%20Automation-orange?style=for-the-badge&logo=n8n" />
<img src="https://img.shields.io/badge/OpenAI-GPT--4o-green?style=for-the-badge&logo=openai" />
<img src="https://img.shields.io/badge/Qdrant-Vector%20Database-red?style=for-the-badge" />
<img src="https://img.shields.io/badge/RAG-Semantic%20Search-blue?style=for-the-badge" />
<img src="https://img.shields.io/badge/AI-Learning%20Assistant-purple?style=for-the-badge" />

---

### 🧠 Turn YouTube Videos into an Interactive AI Learning Experience

This project allows users to ask questions directly from YouTube video transcripts using **Retrieval-Augmented Generation (RAG)** and semantic search.

Instead of manually searching through long videos, users can now interact with video knowledge using AI. 🚀

</div>

---

# 🌟 Overview

This project is an advanced **YouTube Video RAG System** built using:

- 🤖 OpenAI GPT Models
- 🧠 Semantic Search
- 📚 Qdrant Vector Database
- 🎥 YouTube Transcript Processing
- ⚡ n8n Workflow Automation
- 💬 AI Agent Systems

The assistant extracts YouTube transcripts, converts them into vector embeddings, stores them inside Qdrant, and retrieves only relevant knowledge during conversations.

---

# 🔥 Features

## ✅ AI-Powered YouTube Learning Assistant

- Fetch YouTube video transcripts automatically
- Convert transcript text into embeddings
- Store semantic knowledge in Qdrant
- Ask questions directly from video content
- Generate contextual AI responses

---

## ✅ Hallucination-Safe Responses

Unlike generic chatbots:

✔ AI answers ONLY from transcript knowledge  
✔ Prevents external misinformation  
✔ Uses transcript-grounded semantic retrieval  

---

## ✅ Retrieval-Augmented Generation (RAG)

This system uses:

```text
Transcript Retrieval
        +
Semantic Search
        +
GPT Response Generation
```

to generate accurate and context-aware answers.

---

## ✅ Beginner-Friendly Learning Experience

The AI can:

- Explain concepts simply
- Summarize long discussions
- Clarify technical topics
- Answer follow-up questions

---

# 📂 Repository Structure

```text
youtube-rag-n8n/
│
├── RAG knowledge ingestion.json
├── Ask questions to the YouTube video.json
└── README.md
```

---

# ⚙️ Workflows Included

# 1️⃣ RAG Knowledge Ingestion Workflow

## Purpose

Processes YouTube transcripts and converts them into searchable vector embeddings.

---

## Responsibilities

✅ Fetch YouTube transcripts  
✅ Process transcript data using JavaScript  
✅ Split transcript into chunks  
✅ Generate embeddings using OpenAI  
✅ Store vectors inside Qdrant  
✅ Build searchable video knowledge base  

---

## Technologies Used

| Technology | Purpose |
|---|---|
| YouTube Transcript API | Transcript Extraction |
| JavaScript | Data Processing |
| OpenAI Embeddings | Semantic Search |
| Qdrant | Vector Storage |
| n8n | Workflow Automation |

---

# 2️⃣ Ask Questions to the YouTube Video Workflow

## Purpose

Allows users to interact with video knowledge using AI.

---

## Responsibilities

✅ Accept user questions  
✅ Generate semantic search embeddings  
✅ Retrieve relevant transcript chunks  
✅ Inject transcript context into GPT  
✅ Generate grounded AI responses  
✅ Prevent hallucinated responses  

---

## Technologies Used

| Technology | Purpose |
|---|---|
| GPT-4o Mini | AI Response Generation |
| Semantic Search | Knowledge Retrieval |
| Qdrant | Vector Search |
| AI Agent | Intelligent Q&A |
| Prompt Engineering | Hallucination Reduction |

---

# 🧩 Complete System Architecture

```text
                ┌────────────────────┐
                │   YouTube Video    │
                └─────────┬──────────┘
                          │
                          ▼
                ┌────────────────────┐
                │ Transcript Fetcher │
                └─────────┬──────────┘
                          │
                          ▼
                ┌────────────────────┐
                │ JavaScript Parsing │
                └─────────┬──────────┘
                          │
                          ▼
                ┌────────────────────┐
                │   Text Chunking    │
                └─────────┬──────────┘
                          │
                          ▼
                ┌────────────────────┐
                │ OpenAI Embeddings  │
                └─────────┬──────────┘
                          │
                          ▼
                ┌────────────────────┐
                │ Qdrant Vector DB   │
                └─────────┬──────────┘
                          │
                          ▼
                ┌────────────────────┐
                │    User Question   │
                └─────────┬──────────┘
                          │
                          ▼
                ┌────────────────────┐
                │  Semantic Search   │
                └─────────┬──────────┘
                          │
                          ▼
                ┌────────────────────┐
                │ Relevant Transcript│
                └─────────┬──────────┘
                          │
                          ▼
                ┌────────────────────┐
                │ GPT-4o AI Response │
                └────────────────────┘
```

---

# 💡 Example Questions Users Can Ask

```text
"What is this video about?"
```

```text
"Explain this concept in simple terms"
```

```text
"Summarize the key ideas discussed"
```

```text
"What can I learn from this video?"
```

```text
"Explain a specific topic from the transcript"
```

---

# 🛠 Tech Stack

<div align="center">

| Technology | Usage |
|---|---|
| n8n | Workflow Automation |
| OpenAI API | AI Processing |
| GPT-4o Mini | AI Responses |
| OpenAI Embeddings | Semantic Search |
| Qdrant | Vector Database |
| JavaScript | Transcript Processing |
| RAG Architecture | Retrieval Pipeline |
| Semantic Search | Knowledge Retrieval |
| AI Agent Systems | Intelligent Responses |

</div>

---

# 📥 Setup Instructions

# Step 1 — Clone Repository

```bash
git clone https://github.com/yourusername/youtube-rag-n8n.git
```

---

# Step 2 — Import Workflows into n8n

Import:

```text
RAG knowledge ingestion.json
Ask questions to the YouTube video.json
```

---

# Step 3 — Configure Credentials

Add your:

- OpenAI API Key
- Qdrant Credentials
- YouTube Transcript Access

---

# Step 4 — Run Transcript Ingestion

Execute:

```text
RAG knowledge ingestion.json
```

This workflow will:

✅ Fetch transcripts  
✅ Process transcript chunks  
✅ Generate embeddings  
✅ Store vectors in Qdrant  

---

# Step 5 — Start Asking Questions

Execute:

```text
Ask questions to the YouTube video.json
```

Ask AI questions directly from the video transcript.

---

# 🔐 Security

## This repository does NOT contain:

❌ API Keys  
❌ Secrets  
❌ Tokens  
❌ Credentials  

Please configure your own credentials inside n8n before execution.

---

# 🎯 Key Learnings

This project helped me understand:

✅ Retrieval-Augmented Generation (RAG)  
✅ Transcript-based semantic search  
✅ Vector databases and embeddings  
✅ AI workflow orchestration  
✅ Context-aware AI systems  
✅ Knowledge-grounded response generation  
✅ Prompt engineering  
✅ Hallucination-safe AI design  

---

# 🚀 Future Improvements

- Multi-video collections
- YouTube playlist ingestion
- Video timestamp citations
- Web UI integration
- Multi-user support
- OCR for video slides
- Streaming AI responses
- Hybrid semantic + keyword search
- Advanced memory systems

---

# 📚 Real-World Applications

## 🎓 AI Study Assistant

Learn from educational YouTube videos interactively.

---

## 🧠 Technical Learning Companion

Ask questions from coding tutorials and tech videos.

---

## 📖 Research Video Assistant

Search and summarize research presentations.

---

## 🏢 Internal Training Assistant

Turn training videos into searchable knowledge bases.

---

# 📸 Project Vision

> AI should not only generate responses.
>
> It should retrieve the RIGHT knowledge
> from the RIGHT source
> at the RIGHT time.

This project demonstrates how AI can transform passive video consumption into an active learning experience using semantic search and RAG architecture.

---

# ⭐ Support

If you found this project useful:

⭐ Star the repository  
🍴 Fork the project  
🚀 Contribute improvements  
💬 Share feedback  

---

<div align="center">

# 🚀 Building Real-World AI Systems One Project at a Time

</div>

---

# 📜 License

MIT License
