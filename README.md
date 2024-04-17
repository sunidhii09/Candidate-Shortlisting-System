# Candidate Shortlisting System

## Overview

The Candidate Shortlisting System is a Python-based application designed to parse, summarize, rate and rank resumes using natural language processing (NLP) techniques. It leverages machine learning models to predict the category of each resume and generates concise summaries highlighting key information such as skills, experience, and education. Additionally, the system calculates a rating for each resume based on various linguistic features and presents a ranking list.

## Features

- **Resume Summarization**: Automatically summarizes resumes using the BART model.
- **Category Prediction**: Predicts the category of each resume, such as HR, Mechanical Engineer, Sales, etc.
- **Resume Rating**: Calculates a rating for each resume based on linguistic features including average word length, vocabulary richness, and semantic richness.
- **Ranking List**: Generates a ranking list of resumes based on their ratings, allowing users to quickly identify top candidates.

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/resume-summarization-system.git
    ```

2. **Download the pre-trained models for NLP tasks** (e.g., BART model from Hugging Face Transformers) and place them in the appropriate directories.

## Usage

1. **Prepare your resumes:**
   - Place your resume files in the `Resumes_Input` directory.
   - Supported formats: PDF.

2. **Run the main script:**

    ```bash
    Resume_Screening.ipynb
    ```

3. **View the results:**
   - Summarized information will be saved to the `Candidate Summary_Output` directory as CSV files.
   - The ranking list of resumes will be displayed in the console.


## Acknowledgments

- [Hugging Face Transformers](https://huggingface.co/transformers/) for the pre-trained NLP models.
- [pdf2docx](https://pypi.org/project/pdf2docx/) for PDF to DOCX conversion.
- [NLTK](https://www.nltk.org/) for natural language processing.
