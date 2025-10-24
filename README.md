# TrueNews: Fake News Detection Project

## About
TrueNews is a machine learning project for detecting fake news using natural language processing (NLP) techniques. It leverages Python libraries such as pandas, scikit-learn, and spaCy to analyze news statements and classify them as true, false, or somewhere in between. The project includes data exploration, feature engineering, and model training in a Jupyter notebook.

## Setup Instructions

1. **Clone or download the repository**
2. **Create and activate a Python virtual environment**
   ```bash
   python -m venv truenews-venv
   # Activate the environment:
   # On Windows:
   truenews-venv\Scripts\activate
   # On macOS/Linux:
   source truenews-venv/bin/activate
   ```
3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
4. **Download the spaCy English language model**
   ```bash
   python -m spacy download en_core_web_sm
   ```
5. **Start Jupyter Notebook**
   ```bash
   jupyter notebook
   ```
6. **Open and run `RealNews.ipynb`**

## Notes
- Make sure you have Python 3.8 or newer installed.
- The dataset should be present in the `data` directory as referenced in the notebook.
- If you encounter missing package errors, double-check your virtual environment is activated and all dependencies are installed.
