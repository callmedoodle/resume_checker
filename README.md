# resume_checker
# 📄 Resume Checker – ATS-Based Resume Analyzer

This project is an **AI-powered Resume Checker** that evaluates your resume against a specific job description (JD) to calculate an **ATS (Applicant Tracking System) Match Score**. It helps job seekers optimize their resumes for different roles using keyword analysis and skill matching.

## 🔧 Features

- ✅ Extracts text from resumes (PDF format)
- ✅ Identifies relevant skills from the resume
- ✅ Matches resume skills with recommended skills for various job roles
- ✅ Accepts user-provided Job Description to extract keywords
- ✅ Calculates ATS Match Score and displays it in a visual pie chart
- ✅ Provides smart suggestions and best-fit job roles
- ✅ Clean and interactive UI built using **Gradio**

---

## 🚀 Demo

Just upload your resume and paste the job description. The tool will analyze your resume and provide:
- A pie chart of your ATS score
- Suggested improvements
- Best-matching job roles

---

## 🧠 Roles and Skills Mapped

The analyzer currently supports the following roles:
- AI/ML Intern
- Data Analyst
- Web Developer
- Backend Developer
- Cloud Engineer
- DevOps Engineer
- Cybersecurity Analyst
- Data Scientist
- Business Analyst
- Full Stack Developer

Each role has a predefined list of key skills used for matching.

---

## 📦 Installation & Setup

### Requirements:
- Python 3.7+
- pip

### Install dependencies:

```bash
pip install gradio pdf2image pytesseract nltk matplotlib PyMuPDF
sudo apt-get install -y poppler-utils  # for Linux
python resume_checker.py
