#  Resume Screening with Python

A simple Python project to automatically screen resumes. The notebook extracts text from resumes, cleans it, and matches with job requirements to rank candidates.

## Features

* Extract text from PDF resumes
* Preprocess text (tokenization, stopwords removal, lemmatization)
* Compare resumes with job description
* Rank candidates based on similarity score

## Tech Stack

* Python
* Libraries: `pandas`, `numpy`, `scikit-learn`, `nltk`, `PyPDF2`

## Project Files

* `Resume Screening with Python.ipynb` → Main notebook
* `data/` → Folder for resumes (PDFs)
* `requirements.txt` → Dependencies

## Setup

```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>
pip install -r requirements.txt
```

## Usage

1. Put resumes in the `data/` folder
2. Open the notebook:

   ```bash
   jupyter notebook "Resume Screening with Python.ipynb"
   ```
3. Run all cells to generate ranked candidates

## Output

* Ranked list of candidates with similarity scores


