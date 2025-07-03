# Arabic-News-NLP
## Overview
A simple NLP system to:
- Collect Arabic news articles via RSS feeds
- Classify them into categories 
- Generate automatic summaries using pretrained transformers
- Display results in an interactive Streamlit app

## Tech Stack
- Python
- feedparser

## Project Structure
Arabic-News-NLP/
- ├── data/                # Raw and processed data
- ├── notebooks/           # Jupyter/Colab notebooks
- │   ├── data_collection.ipynb
- │   ├── preprocessing.ipynb
- │   ├── Zero-shot_Classification_Manual_Correction.ipynb
- │   ├── classification.ipynb
- │   └── summarization.ipynb
- ├── app/                 # Streamlit app code
- │   └── app.py
- ├── requirements.txt     # project dependencies
- └──  README.md

