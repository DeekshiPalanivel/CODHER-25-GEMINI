# 📰 SecureNews – GenAI-Powered News Video Subtitle Translator with RAG

A Generative AI–powered web application that translates news video subtitles into multiple languages and re-embeds the translated text back into the video. Built during **CODHER**, a women-only hackathon, this project aims to make news accessible across language barriers while maintaining **factual accuracy** using a **Retrieval-Augmented Generation (RAG)** pipeline.

---

## 🚀 Features

- 🎥 Upload any news video clip
- 🌐 Translate subtitles to selected languages using GenAI
- 🧠 Context-aware translation with RAG (Retrieval-Augmented Generation)
- ✅ Verified fact-checking to reduce misinformation
- 📝 Embed translated text back into the video
- 💾 Download or stream the translated video

---

## 🛠️ Tech Stack

| Layer         | Tools / Libraries                               |
|---------------|-------------------------------------------------|
| **Backend**   | Python (Flask or Colab-based backend)           |
| **AI/ML**     | OpenAI API / HuggingFace Transformers           |
| **Subtitles** | Whisper                                         |
| **RAG**       | FAISS / Pinecone (for retrieval) + LLM          |
| **Embedding** | FFmpeg                                          |
| **Deployment**| Google Colab                                    |

---

## 🧠 How It Works

1. **User uploads a news video** via the frontend UI.
2. Backend extracts subtitles (or transcribes the audio using Whisper).
3. A **RAG pipeline** retrieves relevant factual data and context from trusted sources.
4. Subtitles are translated using **Generative AI** enhanced with this context.
5. Translated, fact-checked text is re-embedded into the video using `ffmpeg`.
6. The final translated video is returned to the user for preview/download.

---

## 💡 Project Motivation

We created this project during **CODHER**, a women-only hackathon, to explore the use of **Generative AI in the field of Entertainment**. With rising concerns around misinformation, our goal was to enable **multilingual access to trustworthy news** using an intelligent and context-aware system powered by RAG.

---

## 🧑‍💻 Team

**Deekshikaa Palanivel**  
**Krithika Ravishankar**

---

## 📄 License

This project is open-source for educational and research use.
