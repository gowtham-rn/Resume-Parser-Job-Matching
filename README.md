# Resume Parser & Job Role Matching System

## Project Overview
This project is a Resume Parsing and Job Role Matching system developed using Python and basic Machine Learning techniques.
It analyzes a candidate’s resume in PDF format and matches it against predefined job roles using text similarity methods.

The system helps identify the most suitable job role for a candidate based on their skills.

---

## Objectives
- Extract text from resume PDF files
- Analyze skills using NLP techniques
- Compare resume content with job role skill profiles
- Predict the best matched job role

---

## Technologies Used
- Python
- Pandas
- Scikit-learn
- PDFPlumber
- TF-IDF Vectorizer
- Cosine Similarity

---

## Files Included
- `resume_job_matching.py` – Main Python program
- `Resume_Parser_Dataset.xlsx` – Dataset containing job roles and skills
- `requirements.txt` – List of required Python libraries

---

## Dataset Information
The dataset contains candidate skill data mapped to different job roles such as:
- Developer
- QA
- HR
- Product Owner
- UX Designer

These records are used to create skill profiles for each job role.

---

## Resume Input
For privacy reasons, resume files are not included in this repository.

To test the project:
1. Add your resume PDF to the project directory
2. Rename the file as `resume.pdf`

---

## How to Run the Project

1. Install required dependencies:
```
pip install -r requirements.txt
```

2. Run the program:
```
python resume_job_matching.py
```

---

## Sample Output
```
Resume Job Matching Results

Developer : 3.95%
QA : 3.66%
HR : 3.47%
Product Owner : 3.43%
UX Designer : 2.91%

Best Suitable Job Role:
Developer
```

---

## Use Cases
- Resume screening systems
- Applicant Tracking System (ATS) concepts
- Academic mini-projects
- NLP and ML learning applications

---

## Academic Note
This project is developed for educational and learning purposes.
