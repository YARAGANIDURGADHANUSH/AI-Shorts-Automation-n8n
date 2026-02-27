# 🎬 AI Shorts Automation (n8n)

A fully automated end-to-end AI video generation pipeline that creates and publishes YouTube Shorts without any manual intervention.

---

## 🚀 Project Overview

This project implements an autonomous workflow using **n8n** that performs:

- AI idea generation
- Viral idea shortlisting
- Script generation using LLM APIs
- Image prompt creation
- AI image generation
- Voice narration generation
- Automated video rendering
- Scheduled publishing to YouTube Shorts

The entire pipeline runs programmatically from idea → final uploaded video.

---

## ⚙️ Workflow Architecture

Idea Generation → Script Creation → Prompt Engineering → Image Generation → Voiceover Creation → Video Rendering → Automated Upload to YouTube

---

## 🧠 Tech Stack

- **n8n** – workflow automation  
- **Groq LLM API** – idea & script generation  
- **Pollinations AI** – image generation  
- **Google TTS** – narration  
- **Creatomate API** – video rendering  
- **YouTube API** – automatic publishing  

---

## 🎥 Demo Video

Watch the generated AI Short:

https://www.youtube.com/shorts/G2qfF9bzExg

---

## 📁 Repository Contents

- `n8n_workflow.json` — Complete automation workflow  
- `final_video.mp4` — Sample generated output  
- `.env.example` — Required environment variables  
- `README.md` — Project documentation  

---

## 🔐 Environment Setup

Create a `.env` file with the following variables:

```
GROQ_API_KEY=YOUR_API_KEY
CREATOMATE_API_KEY=YOUR_CREATOMATE_API_KEY
YOUTUBE_OAUTH=YOUR_YOUTUBE_CREDENTIALS
```

---

## 🔄 Automation

The workflow runs automatically via a schedule trigger and produces AI-generated videos without manual editing.

---

## 👨‍💻 Author

**Durga Dhanush YaraganI**
