# 🌴 AI Resume Analyzer

## 📌 Overview

AI Resume Analyzer is an intelligent web application that analyzes resumes using Natural Language Processing (NLP) techniques. The system extracts relevant information from uploaded resumes, identifies key skills, predicts suitable career domains, and provides recommendations to improve employability.

This project was developed as part of the Master of Computer Applications (MCA) program at Amity University Bengaluru.

---

## 🎯 Objectives

* Automate resume screening and analysis.
* Extract candidate information from PDF resumes.
* Recommend skills, certifications, and courses.
* Predict suitable job roles based on resume content.
* Generate resume improvement suggestions.
* Provide analytics for recruiters and administrators.

---

## ✨ Features

### 👨‍💼 Candidate Module

* Resume Upload (PDF)
* Resume Parsing
* Skill Extraction
* Keyword Analysis
* Job Role Prediction
* Resume Score Generation
* Skill Recommendations
* Course Recommendations
* Interview Preparation Resources
* Resume Improvement Suggestions

### 👨‍💻 Admin Module

* View Candidate Records
* Download Data as CSV
* User Analytics Dashboard
* Feedback Management
* Resume Database Management
* Statistical Reports and Charts

---

## 🛠 Technology Stack

### Frontend

* Streamlit
* HTML
* CSS
* JavaScript

### Backend

* Python

### Database

* MySQL

### Libraries Used

* pandas
* pyresparser
* pdfminer3
* NLTK
* Plotly
* spaCy

---

## 📂 Project Structure

```text
AI-Resume-Analyzer/
│
├── App/
│   ├── App.py
│   ├── Courses.py
│   ├── requirements.txt
│   └── Other Supporting Files
│
├── Uploaded_Resumes/
│
├── pyresparser/
│
├── README.md
│
└── Database Files
```

---

## ⚙️ Prerequisites

Install the following software before running the project:

* Python 3.9+
* MySQL Server
* Visual Studio Code
* Visual Studio Build Tools (C++)

---

## 🚀 Installation

### Clone Repository

```bash
git clone https://github.com/Amritheshmt22/AI-Resume-Analyzer.git
```

### Move to Project Directory

```bash
cd AI-Resume-Analyzer
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux/Mac

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Download spaCy Model

```bash
python -m spacy download en_core_web_sm
```

---

## 🗄 Database Configuration

1. Open MySQL.
2. Create a database:

```sql
CREATE DATABASE cv;
```

3. Update MySQL credentials inside:

```python
App.py
```

with your:

* Host
* Username
* Password
* Database Name

---

## ▶️ Run the Application

```bash
streamlit run App.py
```

After execution, open the generated local URL in your browser.

---

## 📊 Functionalities

### Resume Analysis

The application extracts:

* Name
* Email
* Phone Number
* Skills
* Education Details
* Experience Information
* Keywords

### Recommendations

The system provides:

* Skill Recommendations
* Course Recommendations
* Career Domain Suggestions
* Resume Improvement Tips

### Analytics

Admin Dashboard includes:

* User Statistics
* Resume Score Analysis
* Job Domain Distribution
* Feedback Reports
* Downloadable CSV Reports

---

## 📈 Future Enhancements

* AI-Based Interview Question Generator
* ATS Compatibility Checker
* LinkedIn Profile Analyzer
* Multi-Language Resume Support
* Resume Comparison Feature
* AI Career Roadmap Generator

---

## 👨‍🎓 Academic Information

**Project Title:** AI Resume Analyzer

**Developed By:** Amrithesh M T

**Course:** Master of Computer Applications (MCA)

**Institution:** Amity University Bengaluru

**Academic Year:** 2025–2026

---

## 🤝 Contributions

Contributions, suggestions, and improvements are welcome.

Feel free to fork the repository and submit pull requests.

---

## 📄 License

This project is developed for educational and learning purposes.

---

## ⭐ Support

If you found this project useful, please consider giving it a star on GitHub.

---

### Developed with ❤️ by Amrithesh M T
