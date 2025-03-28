# AI-Powered Resume Screening And Ranking System

## Overview
This project is a Streamlit-based web application that ranks resumes based on their relevance to a given job description using TF-IDF vectorization and cosine similarity.
This project automates the process of resume screening by ranking resumes based on predefined criteria using Natural Language Processing (NLP) and Machine Learning (ML) techniques.

## Objectives
- Automate the resume screening process to save time and effort.
- Improve hiring efficiency by ranking resumes based on job relevance.
- Reduce bias in resume screening by using objective evaluation criteria.
- Provide a user-friendly interface for recruiters to process resumes.

## Techniques Used
- **Python:**(Backend logic)
- **Streamlit :**(Frontend UI framework)
- **PyPDF2:**(Extract text from PDF files)
- **scikit-learn:**(Natural Language Processing and similarity scoring)
- **Pandas:**(Data processing and table rendering)

## Features
-Upload multiple PDF resumes.
-Enter a job description as input.
-Extract text from PDFs using PyPDF2.
-Compute similarity scores between the job description and resumes.
-Display ranked results in tabular format.
-Simple and interactive UI powered by Streamlit.
-Real-time ranking of resumes based on job relevance.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/resume-screening-app.git
   cd resume-screening-app
   ```

2. Create a virtual environment:
    ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
   
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Running the App
Run the following command to launch the Streamlit app:
 ```sh
streamlit run resume_app.py
  ```


## Dependencies
- Python 3.x
- Jupyter Notebook
- Pandas
- Scikit-learn
- NLTK or SpaCy (for NLP processing)
- PyPDF2 (for extracting text from PDFs)
- Docx (for processing Word documents)

## Conclusion
This AI-powered resume screening and ranking system provides an efficient way to analyze and rank resumes based on job relevance. By leveraging NLP techniques, the tool automates the initial screening process, reducing the time and effort required for recruiters. Future enhancements will further improve accuracy and usability, making it an indispensable tool for HR professionals and hiring managers.
