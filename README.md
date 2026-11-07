# TextAnalysisVEYM

## Textual analysis of VEYM training camp evaluations

This repository adapts the code from
[TextAnalysisVatican](https://github.com/thatswhatsimonsaid/TextAnalysisVatican)
(linguistic shifts in papal encyclicals before and after Vatican II) to a new
corpus: student and leader evaluations of VEYM (Vietnamese Eucharistic Youth
Movement) training camps, 2019 to 2026.

**This repository contains code only.** The evaluation data is confidential
and is never committed. The `.gitignore` in this repo was written before the
first commit and excludes all data files, spreadsheets, pickles, name and
roster tables, and every result derived from the reviews. 

## Repository contents

- `Code/`: Python code copied from TextAnalysisVatican and being adapted
  - `Code/Encyclicals.ipynb`: original Vatican notebook, kept as the
    reference starting point for the new camp notebook
  - `Code/utils/Encylicals/`: scraping and loading (to become review loading)
  - `Code/utils/Council/`: Vatican council document loaders (reference only)
  - `Code/utils/Main/`: core analysis functions (text cleaning, word
    frequency, topic modelling, cosine similarity)
  - `Code/utils/Plots/`: visualisation functions
- `Data/`: local only, empty in git (see Confidentiality)
- `Results/`: local only, empty in git

## Requirements

Python 3.8+. See `requirements.txt` (BeautifulSoup4, NLTK, spaCy, Gensim,
NumPy, SciPy, pandas, scikit-learn, matplotlib, seaborn, openpyxl).
