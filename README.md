# 🧠 Resume Optimizer & Generator

This Streamlit web app helps users **build, optimize, and generate professional resumes** using AI. Upload your existing resume and job description, and the app provides optimized suggestions. You can also generate a LaTeX resume from scratch based on inputs.

---

## 🚀 Features

- 📤 Upload your PDF Resume
- 🧾 Enter Personal, Education, Experience, Skills & Project details
- 📈 Optimize resume using AI to match the job description
- 📝 Generate LaTeX-based resume from scratch
- 🧠 Integrated with Google Gemini Pro via LangChain
- 📊 ATS Score calculation and resume enhancement insights

---

## 🛠️ Technologies Used

- [Streamlit](https://streamlit.io/)
- [LangChain](https://www.langchain.com/)
- [Google Gemini API](https://ai.google.dev/)
- Python Libraries: `asyncio`, `scikit-learn`, `dotenv`, `PyPDFLoader`

---

## 📂 Project Structure

Resume_Optimizer/
│
├── frontend.py # Main Streamlit App
├── backend.py # Core Logic & Prompt Engineering
├── resume.tex # LaTeX Resume Template
├── .env # Environment Variables (Google API Key)
└── README.md # This file


---

## 🔧 Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/resume-optimizer.git
   cd resume-optimizer
