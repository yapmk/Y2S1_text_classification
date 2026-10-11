# Toxicity Classifier

A Streamlit app for testing toxicity classification models (Naive Bayes, SVM, and BERT). Includes a training notebook for Naive Bayes and SVM.

## Dataset

[Jigsaw Unintended Bias in Toxicity Classification](https://www.kaggle.com/datasets/julian3833/jigsaw-unintended-bias-in-toxicity-classification/data?select=train.csv)

## File Purpose

| File | Purpose |
|------|---------|
| `main.py` | Streamlit UI for all models to test the function |
| `NaiveBayes_SVM.ipynb` | Train, save, and evaluate Naive Bayes and SVM models |

## Python Version

- `NaiveBayes_SVM.ipynb` → Python 3.12.7
- `main.py` → Python 3.11.9

## Setup

Follow the steps below to create a virtual environment (`venv`) for `main.py`:

```bash
# Create virtual environment
python -m venv venv

# Activate
venv\Scripts\activate

# Install requirements
pip install -r requirements.txt

# Run Streamlit
streamlit run main.py
```

### Deactivate venv
deactivate

### Change to venv in VS Code
Ctrl + Shift + P
Python: Select Interpreter
