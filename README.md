# AI Resume Screening & Ranking System

This project is an AI-powered resume screening and ranking system built using Streamlit, scikit-learn, and PyPDF2. The application allows users to upload resumes in PDF format, compare them to a given job description, and rank them based on cosine similarity using TF-IDF.

## Features

- Upload multiple PDF resumes.
- Enter a job description to compare.
- Uses TF-IDF & Cosine Similarity for ranking.
- Displays ranked resumes with similarity scores.

## Folder Structure
```
resume_screening_app/
│── .venv/
│── app.py
│── requirements.txt
├── resume_ranking.ipynb
│── data/
│   ├── sample_resume.pdf
│── README.md
│── .gitignore
```

## Installation & Setup

### 1️ Clone the Repository
```bash
git clone https://github.com/mohanchitini/resume_ranking.git
```
[GitHub Repository](https://github.com/mohanchitini/resume_ranking)

### 2️ (Optional) Create a Virtual Environment
```bash
python -m venv .venv
```
Activate on Windows:
```bash
source .venv\Scripts\activate
```
Activate on Mac/Linux:
```bash
source .venv/bin/activate
```

### 3️ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️ Run the Application
```bash
streamlit run app.py
```
The app will open in your default web browser.

## How It Works

1. Upload PDF resumes using the file uploader.
2. Enter a job description in the provided text area.
3. The system extracts text from the resumes and converts them into TF-IDF vectors.
4. The job description is compared against resumes using cosine similarity.
5. Ranked results are displayed with similarity scores.

## Deployment

### Deploy on Streamlit Cloud (Free)
1. Push your project to GitHub.
2. Go to Streamlit Cloud and log in.
3. Click "New App," select your GitHub repo, and set the file path to `app.py`.
4. Click "Deploy" 

## Requirements

- streamlit  
- PyPDF2  
- pandas  
- scikit-learn  
- numpy  

Install using:
```bash
pip install -r requirements.txt
```

## End Users

**HR & Recruiters** – Automates resume screening for faster hiring.
**Hiring Managers** – Ranks resumes efficiently for job roles.
**Job Portals** – Enhances resume-job matching accuracy.
**AI Enthusiasts & Students** – Learn NLP-based resume analysis.

## Future Scope

**AI-Based Scoring** – Use ML/Deep Learning for better ranking.  
**Advanced NLP** – Integrate BERT/GPT for deeper analysis.  
**Multi-Format Support** – Add DOCX, TXT & OCR for images.  
**Skill Matching** – Extract skills & experience automatically.  
**API Integration** – Connect with job portals & HR systems.  

## Conclusion

This AI-powered Resume Screening & Ranking System addresses the challenge of manual resume screening, which is time-consuming and inefficient. By leveraging TF-IDF and Cosine Similarity, the system automates resume ranking, ensuring fast, objective, and accurate candidate shortlisting. With PDF text extraction, real-time ranking, and easy deployment via Streamlit, this project provides an efficient, scalable, and user-friendly solution for recruiters, hiring managers, and job portals. 🚀
