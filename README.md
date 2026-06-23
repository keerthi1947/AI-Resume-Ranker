# 🤖 AI-Powered Resume Ranker

## Overview

AI-Powered Resume Ranker is a Natural Language Processing (NLP) based web application that automatically ranks resumes according to a given job description.

The application extracts text from PDF resumes, analyzes the content using TF-IDF Vectorization, and calculates similarity scores using Cosine Similarity. Based on the similarity score, candidates are ranked from most suitable to least suitable.

---

## Features

* 📄 Upload multiple PDF resumes
* 📝 Enter a job description
* 🤖 Automatic resume ranking
* 📊 Match percentage calculation
* 🛠 Skill detection and extraction
* 🏆 Best candidate recommendation
* 📈 Score visualization using charts
* ⬇ Download results as CSV

---

## Technologies Used

* Python
* Streamlit
* Pandas
* Scikit-Learn
* PDFPlumber
* NumPy
* Natural Language Processing (NLP)

---

## Machine Learning Concepts Used

### TF-IDF (Term Frequency - Inverse Document Frequency)

TF-IDF converts textual information into numerical vectors and assigns higher importance to meaningful words.

### Cosine Similarity

Cosine Similarity measures how closely a resume matches the job description by comparing vectorized text representations.

---

## Project Workflow

1. Upload PDF resumes
2. Extract text from resumes
3. Paste job description
4. Convert text into TF-IDF vectors
5. Calculate cosine similarity scores
6. Rank resumes based on scores
7. Display results and best candidate
8. Export results as CSV

---

## Installation

Install required packages:

```bash
pip install streamlit pandas scikit-learn pdfplumber numpy
```

Run the application:

```bash
streamlit run app.py
```

---

## Project Structure

```text
Resume_Ranker
│
├── app.py
├── utils.py
├── requirements.txt
├── README.md
├── screenshots/
```

---

## Future Improvements

* ATS Score Prediction
* Advanced Resume Parsing
* Semantic Skill Matching
* AI-Based Candidate Recommendation
* Deep Learning Models

---

## Author

Developed as an NLP-based Resume Screening and Ranking System using Python and Streamlit.
