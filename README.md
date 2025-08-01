# 💼 AI Resume Analyzer

A smart tool for analyzing resumes using **Natural Language Processing (NLP)** — provides keyword insights, predictions, and improvement recommendations for candidates and recruiters.

## 🔍 Features

### For Users:
- Extracts basic info, skills, and keywords from resumes
- Recommends:
  - Skills to add
  - Job roles
  - Courses and certificates
  - Tips and videos
- Scores resumes out of 100

### For Admins:
- Tabular view of all users' resume data
- Export data to CSV
- Resume feedback dashboard
- Charts for:
  - Experience level
  - Resume score
  - Roles, location, ratings, etc.

## 🛠 Tech Stack

- **Frontend:** Streamlit, HTML, CSS
- **Backend:** Python (3.9.12), Streamlit
- **Database:** MySQL
- **Modules:** `pyresparser`, `pdfminer3`, `nltk`, `pandas`, `plotly`, etc.

## 🧪 Installation & Setup

1. **Clone the repository:**

```bash
git clone https://github.com/lovelymahor/AI_Resume_Analyzer.git
cd "AI Resume Analyzer"
```

### Create and activate a virtual environment
```base
python -m venv venvapp
venvapp\Scripts\activate   # for Windows
Install dependencies:
```
```base
cd App
pip install -r requirements.txt
python -m spacy download en_core_web_sm
```

### Setup MySQL

Create a database named cv
Update your MySQL credentials inside App/App.py (line 95)
Replace pyresparser file:
Replace the resume_parser.py inside:


venvapp\Lib\site-packages\pyresparser\
with the custom one provided in the pyresparser folder.

### Run the app:

```base
streamlit run App.py
```
### 🔐 Admin Login

Username: admin
Password: admin@resume-analyzer

### 📦 Requirements

- Python 3.9.12
- MySQL
- VS Code (recommended)
- C++ Build Tools

### 🧠 Usage
- Upload a PDF resume
- Get detailed analysis
- Try using the sample resume in Uploaded_Resumes

### 🎯 Roadmap
- Resume scoring
- Role prediction
- Visual feedback analytics
- User profile view
- More domain-specific recommendations

### 📧 Contact
Created by lovelymahor
