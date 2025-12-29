# 🤖 AI Video Summarizer & Quiz Generator

Transform YouTube videos into comprehensive summaries and interactive quizzes using AI-powered multimodal analysis.

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-1.28+-red.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

---

## 📋 Overview

This application leverages advanced AI techniques to automatically process YouTube videos and generate:

- **Executive summaries** – concise overviews of video content  
- **Key takeaways** – important concepts extracted from the video  
- **Full transcripts** – speech-to-text conversion using Whisper  
- **Interactive quizzes (MCQs)** – auto-generated questions for learning and assessment  
- **Visual analysis** – OCR-based text extraction from video frames  
- **Downloadable PDF report** – summary and learning material in a shareable format  

The system combines **speech, visuals, and NLP** to deliver a complete video-to-knowledge pipeline.

---

## ✨ Features

### 🎥 Video Processing
- YouTube URL input with automatic video ID extraction  
- Audio download using `yt-dlp`  
- Audio preprocessing with `ffmpeg`  
- Speech-to-text transcription using **Whisper AI**  

### 📊 Content & Visual Analysis
- Video frame extraction  
- OCR using **Tesseract + OpenCV**  
- Detection of on-screen text, slides, and visuals  
- Multimodal alignment of audio transcript and visual text  

### 🧠 AI Intelligence
- Topic segmentation using **Sentence Transformers (Hugging Face)**  
- AI-powered summary generation using **Groq LLM**  
- Automatic quiz / MCQ generation with explanations  

### 🎯 Quiz Modes
- **Learning Mode** – instant feedback with explanations  
- **Test Mode** – full assessment with final score  
- Progress tracking and result calculation  

### 👤 User Features
- User authentication (login / signup)  
- Video history tracking  
- Session persistence  
- **Downloadable PDF summary report**  

---

## 🛠️ Tech Stack

- **Python**
- **Streamlit** – web interface  
- **Whisper AI** – speech-to-text transcription  
- **Groq LLM** – summary & quiz generation  
- **Sentence Transformers (Hugging Face)** – topic segmentation  
- **OpenCV + Tesseract OCR** – visual text extraction  
- **yt-dlp** – YouTube download  
- **ffmpeg** – audio processing  
- **ngrok** – public URL for Colab deployment  

---

## 🚀 Quick Start (Google Colab – Recommended)

1. Open `Ai_summerizer_app.ipynb` in **Google Colab**  
2. Add API keys using **Colab Secrets** (🔑 icon in sidebar):
   - `GROQ_API_KEY` → get from https://console.groq.com  
   - `NGROK_AUTH_TOKEN` → get from https://ngrok.com  
3. Run all cells  
4. The notebook will generate a **public Streamlit URL**  
5. Sign up or log in (demo credentials: `demo / demo123`)  
6. Paste a YouTube URL and generate summary & quiz  

⚠️ **API keys are not stored in the repository.**  
All secrets are handled via environment variables or Colab secrets.

---

## 🎥 Demo Video

Watch the full demo of the application here:

👉 **[Click to watch demo video](https://drive.google.com/file/d/1-dA0VDlSsPH2cv9vNBRKSQHkEhBkgHD0/view?usp=drivesdk)**

The demo showcases:
- YouTube video ingestion  
- End-to-end AI processing pipeline  
- Summary generation  
- Quiz / MCQ generation  
- Downloadable PDF report  

---

## 🧠 System Architecture

<img width="929" height="39" alt="image" src="https://github.com/user-attachments/assets/909706b7-fc0f-4470-8a33-e6fd7172750b" />

The diagram illustrates the complete pipeline from YouTube ingestion to AI-generated summaries, quizzes, and downloadable PDF reports.

---

## 📌 Outputs

The system generates:
- Speech transcript (Whisper)  
- Visual OCR text (frames)  
- Topic-segmented content  
- AI-generated summary   
- Quiz / MCQs   
- **Downloadable PDF report**  

---

## 🚀 Future Improvements

- Multi-language transcription and summaries  
- Enhanced PDF / DOCX export with custom formatting  
- Collaborative quiz mode with leaderboards  
- Improved visual chart and diagram understanding  

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository  
2. Create a new branch  
3. Commit your changes  
4. Open a pull request  

---

## 📝 License

This project is licensed under the **MIT License**.  
See the `LICENSE` file for details.

---

## 👨‍💻 Author

**Poonam**
