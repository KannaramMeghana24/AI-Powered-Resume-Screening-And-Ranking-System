# AI-Powered Resume Screening And Ranking System

## Overview
This project automates the process of resume screening by ranking resumes based on predefined criteria using Natural Language Processing (NLP) and Machine Learning (ML) techniques. It helps recruiters efficiently shortlist candidates by scoring resumes according to their relevance to a job description.

## Objectives
- Automate the resume screening process to save time and effort.
- Improve hiring efficiency by ranking resumes based on job relevance.
- Reduce bias in resume screening by using objective evaluation criteria.
- Provide a user-friendly interface for recruiters to process resumes.

## Techniques Used
- **Natural Language Processing (NLP):** Used for text extraction and processing from resumes and job descriptions.
- **Machine Learning (ML):** Implements classification and ranking algorithms to score resumes.
- **TF-IDF (Term Frequency-Inverse Document Frequency):** Extracts relevant keywords from resumes and job descriptions.
- **Word Embeddings (Word2Vec, BERT, or SpaCy):** Captures semantic meaning for better text comparison.
- **Similarity Measurement (Cosine Similarity, Jaccard Similarity):** Compares resumes with job descriptions.
- **Data Visualization:** Uses graphs and tables to present ranked candidates effectively.

## Features
- Parses and processes resumes in various formats (PDF, DOCX, etc.).
- Extracts key features such as skills, experience, education, and certifications.
- Uses NLP to compare resumes with job descriptions.
- Implements a ranking algorithm to score resumes based on relevance.
- Generates a ranked list of candidates for easy shortlisting.
- Provides visualizations and insights on candidate suitability.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/resume-ranking.git
   cd resume-ranking
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
1. Open the Jupyter Notebook:
   ```sh
   jupyter notebook Resume_Ranking.ipynb
   ```
2. Run the notebook step by step to process resumes and generate rankings.
3. Upload resumes and job descriptions as inputs.
4. View the ranked list of candidates with scores.

## Dependencies
- Python 3.x
- Jupyter Notebook
- Pandas
- Scikit-learn
- NLTK or SpaCy (for NLP processing)
- PyPDF2 (for extracting text from PDFs)
- Docx (for processing Word documents)

## Conclusion
This project provides an automated approach to resume screening using NLP and ML techniques. By ranking resumes based on relevance, it reduces the time recruiters spend manually reviewing applications while improving the quality of candidate selection. Future improvements may include deep learning-based NLP models and integration with applicant tracking systems.

