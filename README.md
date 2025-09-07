# SceneScribe 🎥📝🎤

**SceneScribe** is a beginner-friendly multimodal AI applet built with **Google AI Studio** + **Cloud Run**.  
It can take **images and audio** (and later video), then generate structured notes:
- 📌 Scene Summary  
- 🧑‍🤝‍🧑 Key Entities  
- 🔤 Text Found (OCR-like)  
- 🎙 Audio Transcript  
- ✅ Action Items  

Powered by **Gemini 2.5 Pro/Flash**, this project shows how to combine **AI + full stack skills** to deploy a working app in just **3 days**.

---

## 🚀 Features
- Upload **images** and get instant scene understanding.
- Upload **audio** and get transcripts + combined insights.
- Simple **React frontend** with file upload.
- **FastAPI backend** calling Gemini APIs.
- Deployed on **Google Cloud Run**.

---

## 🛠 Tech Stack
- **Frontend:** React + Vite + Tailwind (optional styling)
- **Backend:** FastAPI (Python)
- **AI:** Gemini 2.5 (via `google-genai` SDK)
- **Deployment:** Google Cloud Run

---

## 📅 Roadmap
**Day 1:** Backend + Image pipeline MVP  
**Day 2:** Add audio + polish UI  
**Day 3:** Deploy to Cloud Run + submission post  

---

## ⚡ Quick Start (Local Dev)
### Backend
```bash
cd backend
python -m venv .venv
source .venv/bin/activate   # (Linux/Mac)
# .venv\Scripts\Activate    # (Windows PowerShell)
pip install -r requirements.txt

# Run FastAPI
uvicorn app.main:app --reload
```
