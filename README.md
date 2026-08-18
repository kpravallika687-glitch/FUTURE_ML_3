# Resume Screening & Candidate Ranking System

##  Project Overview

This project was developed as part of my **Machine Learning Internship at Future Interns – Task 3**.

The project focuses on building an NLP-based resume screening system that automatically analyzes resumes against a given job description, evaluates candidate suitability, ranks candidates, and identifies missing skills.

##  Objectives

* Preprocess resume text
* Extract relevant skills from resumes
* Process job descriptions
* Calculate resume-to-job similarity
* Score candidates based on job relevance
* Rank candidates based on their overall fit
* Identify missing or required skills

##  Technologies Used

* Python
* Pandas
* NumPy
* NLTK
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook
* VS Code
* Git & GitHub

## Techniques Used

* Natural Language Processing
* Text Preprocessing
* Tokenization
* Stopword Removal
* Skill Extraction
* TF-IDF Vectorization
* Cosine Similarity
* Skill Matching
* Candidate Scoring
* Candidate Ranking
* Logistic Regression
* Confusion Matrix
* Model Evaluation

##  Project Workflow

```text
Resume Dataset
      ↓
Text Extraction
      ↓
Text Cleaning & Preprocessing
      ↓
Skill Extraction
      ↓
Job Description Processing
      ↓
TF-IDF Vectorization
      ↓
Cosine Similarity
      ↓
Skill Matching
      ↓
Candidate Scoring
      ↓
Candidate Ranking
      ↓
Missing Skill Identification
```

##  Candidate Scoring

The final candidate score combines resume-to-job similarity and required skill matching.

**Final Score = 70% Resume-Job Similarity + 30% Skill Match Score**

This provides an explainable way to compare candidates based on their relevance to the selected job role.

##  Machine Learning Model

A **Logistic Regression** model is used for resume category classification.

The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

##  Business Impact

The system can help recruitment teams:

* Reduce manual resume screening
* Shortlist candidates faster
* Compare candidates consistently
* Identify missing skills
* Reduce recruiter workload
* Support data-driven candidate screening

##  Project Structure

```text
Resume-Screening-System/
│
├── Resume/
│   └── Resume.csv
│
├── resume_screening.ipynb
├── candidate_ranking_results.csv
├── job_description.txt
├── requirements.txt
├── README.md
└── .gitignore
```

## ▶️ How to Run

Clone the repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Navigate to the project:

```bash
cd Resume-Screening-System
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Open Jupyter Notebook:

```bash
jupyter notebook
```

Open `resume_screening.ipynb` and run the cells sequentially.

##  Future Enhancements

* Real-time resume screening
* PDF resume upload
* Web-based screening interface
* Advanced NLP models such as BERT
* Automated candidate recommendations
* Integration with recruitment platforms

##  Internship

**Organization:** Future Interns
**Internship:** Machine Learning Internship
**Task:** Task 3 – Resume / Candidate Screening System
**Domain:** Machine Learning & Natural Language Processing

##  Author

**Pravallika K.**

B.Tech – Computer Science & Engineering (Data Science)
