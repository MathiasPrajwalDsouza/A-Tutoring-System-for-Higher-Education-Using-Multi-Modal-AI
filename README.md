# Textora AI – Multimodal AI Chat Platform

<div align="center">

![Textora AI](https://img.shields.io/badge/Textora%20AI-v3.2-purple?style=for-the-badge)
![React](https://img.shields.io/badge/React-18.x-61DAFB?style=for-the-badge&logo=react)
![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

### A futuristic multimodal AI platform with voice, document intelligence & self-training abilities

</div>

---

## 📚 Table of Contents

- Overview  
- What Makes Textora Special  
- Features  
- Tech Stack  
- Architecture  
- Installation  
- Configuration  
- Usage  
- OCR & Semantic Pipeline  
- Training & Fine-Tuning  
- API Reference  
- Performance  
- Contributing  
- License  

---

## 🌟 Overview

Textora AI is an advanced multimodal AI chat system designed for education, research, and document intelligence.  
It combines real-time chat, OCR-powered textbook understanding, voice interaction, and self-training LLaVA fine-tuning into one seamless platform.

---

## 🚀 What Makes Textora Special

- Understands PDFs like a human  
- Links diagrams to text automatically  
- Generates AI training datasets by itself  
- Fine-tunes its own vision language model  
- Works locally using Ollama models  
- Beautiful futuristic UI  

---

## ✨ Features

### UI
- Liquid cursor ripple effects  
- Glassmorphism & animated particles  
- Dark & Light mode  
- Fully responsive  

### Chat
- Multimodal input (Text + Image + Voice)  
- Markdown & LaTeX rendering  
- Persistent chat history  

### Document AI
- OCR at 300 DPI  
- Equation detection & LaTeX parsing  
- Diagram detection & caption linking  

### AI Training
- Auto question generation  
- Student & Expert answers  
- LLaVA LoRA fine-tuning  

---

PDF → OCR → Semantic Linking → Multi-Agent QA → LLaVA Training → Smart Chat


---

## 🛠 Tech Stack

| Layer | Technology |
|-----|-----------|
| Frontend | React, KaTeX, Lucide |
| Backend | Flask, PaddleOCR, CLIP |
| Models | Qwen-VL, LLaMA3, LLaVA |
| Training | HuggingFace + PEFT |

---

## 🚀 Installation

### Frontend
```bash

git clone https://github.com/yourusername/textora-ai.git
cd textora-ai/frontend
npm install
npm start

Backend

cd ../backend
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python app.py

Ollama

ollama pull qwen3-vl:8b
ollama pull llama3:8b

⚙ Configuration
REACT_APP_API_URL=http://localhost:5000





## 🧠 Architecture

📖 Usage

Upload PDFs

Chat using text or voice

Generate training dataset

Fine-tune your own AI

🔌 API

POST /generate
Returns AI response from multimodal models.

🧪 Training

Creates thousands of LLaVA samples

Trains LoRA adapters

Only 4M trainable params

8–12 hrs on RTX 3090

📊 Performance
Task	Speed
OCR	2–5 sec/page
Semantic linking	1 sec/page
Training	8–12 hrs
🤝 Contributing

Fork → Branch → Commit → PR

📄 License

MIT License

⭐ Star this project if you like AI that learns by itself 😎
Made with ❤️ by Textora AI Team


---

Next I can help you with:

- GitHub project description  
- Tags & SEO keywords  
- Repository banner image  
- CONTRIBUTING.md  
- LICENSE file  
- Project logo  

Just tell me what you want next 🚀
