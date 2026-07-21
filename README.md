# 🎥 AI Video Assistant

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.11+-blue?style=for-the-badge&logo=python"/>
  <img src="https://img.shields.io/badge/Streamlit-UI-red?style=for-the-badge&logo=streamlit"/>
  <img src="https://img.shields.io/badge/OpenAI-Whisper-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/LangChain-RAG-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge"/>
</p>

<p align="center">
  <b>An AI-powered Video Analysis Assistant that converts videos into intelligent knowledge.</b>
</p>

---

## 🚀 Overview

AI Video Assistant is an intelligent application that extracts valuable insights from video content.

It can:

- 🎙️ Extract audio from YouTube videos or local video files
- 📝 Generate accurate transcripts using Whisper
- 🌍 Translate transcripts into English (if required)
- 📄 Generate AI-powered summaries
- 📌 Extract key decisions
- ✅ Extract action items
- ❓ Extract important questions
- 🧠 Build a searchable knowledge base using RAG
- 💬 Chat with your video using natural language

---

# ✨ Features

✅ YouTube Video Support

✅ Local Video Upload

✅ Automatic Audio Extraction

✅ Speech-to-Text using Whisper

✅ AI Generated Summary

✅ Automatic Title Generation

✅ Key Decisions Extraction

✅ Action Items Detection

✅ Important Questions Detection

✅ RAG-based Question Answering

✅ Interactive Streamlit UI

---

# 🏗️ Project Structure

```
AI-VIDEO-ASSISTANT/
│
├── core/
│   ├── audio_processor.py        # Audio extraction & preprocessing
│   ├── transcriber.py            # Whisper transcription
│   ├── summarizer.py             # Summary & title generation
│   ├── extractor.py              # Action items, decisions & questions
│   ├── rag_engine.py             # Vector database & RAG pipeline
│   └── __init__.py
│
├── utils/
│   ├── helper.py                 # Utility functions
│   ├── constants.py              # Global constants
│   └── __init__.py
│
├── app.py                        # Streamlit Web App
├── main.py                       # CLI Version
├── test.py                       # Testing file
├── requirements.txt              # Dependencies
├── .gitignore
├── .env                          # API Keys (Not uploaded)
└── README.md
```

---

# ⚙️ Tech Stack

| Category | Technology |
|----------|------------|
| Language | Python |
| UI | Streamlit |
| Speech Recognition | OpenAI Whisper |
| LLM | Mistral AI |
| Framework | LangChain |
| Embeddings | Mistral Embeddings |
| Vector Database | ChromaDB |
| Translation | Deep Translator |
| Video Download | yt-dlp |
| Audio Processing | FFmpeg + Pydub |

---

# 📦 Installation

Clone the repository

```bash
git clone https://github.com/jeetgondaliya2-prog/AI-VIDEO-ASSISTANT.git

cd AI-VIDEO-ASSISTANT
```

Install dependencies

```bash
pip install -r requirements.txt
```

Install FFmpeg

Windows

```bash
winget install Gyan.FFmpeg
```

Linux

```bash
sudo apt install ffmpeg
```

Mac

```bash
brew install ffmpeg
```

---

# 🔑 Environment Variables

Create a `.env` file.

```env
MISTRAL_API_KEY=your_api_key
```

---

# ▶️ Run the Project

### Streamlit App

```bash
streamlit run app.py
```

### CLI Version

```bash
python main.py
```

---

# 📚 Workflow

```text
Video
   │
   ▼
Extract Audio
   │
   ▼
Whisper Transcription
   │
   ▼
Translation (Optional)
   │
   ▼
Summary Generation
   │
   ├──────────────► Title
   │
   ├──────────────► Action Items
   │
   ├──────────────► Questions
   │
   └──────────────► Key Decisions
   │
   ▼
Create Embeddings
   │
   ▼
Chroma Vector Database
   │
   ▼
Chat with Video (RAG)
```

---

# 📸 Screenshots

> Add your screenshots here

```
Home Screen

Summary

RAG Chat

Transcript

```

---

# 🎯 Future Improvements

- 🔹 Multiple Video Support
- 🔹 PDF Report Export
- 🔹 Speaker Identification
- 🔹 Timeline Based Search
- 🔹 Meeting Analytics Dashboard
- 🔹 Multi-language Support
- 🔹 Cloud Deployment
- 🔹 Voice Chat with Videos
- 🔹 Video Highlights Detection

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Added new feature"
```

4. Push

```bash
git push origin feature-name
```

5. Open a Pull Request

---

# ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub.

It motivates future development and helps others discover the project.

---

# 👨‍💻 Author

**Jeet Gondaliya**

GitHub:
https://github.com/jeetgondaliya2-prog



---

# 📄 License

This project is licensed under the MIT License.
