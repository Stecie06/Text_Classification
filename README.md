## Project Overview

This project focuses on classifying spam email using multiple modeling approaches. It includes classical machine learning baselines and neural sequence models to compare performance, interpretability, and training complexity on a processed email dataset.

## Dataset Notes

- Source file: [Data/spam_email_dataset_processed.csv](Data/spam_email_dataset_processed.csv)
- Contents: Preprocessed email text with a label column for spam/ham classification.
- Typical fields: cleaned text, optional metadata/features, and a binary label.
- Usage: Loaded directly in the notebooks for feature engineering, training, and evaluation.

## Quick Usage

1. Open a notebook from [Notebooks/](Notebooks/).
2. Run the cells top to bottom to reproduce preprocessing, training, and evaluation.
3. Compare metrics across notebooks to choose the best approach.

## Notebooks

The [Notebooks/](Notebooks/) folder contains exploratory notebooks for spam email detection. Each notebook applies a different modeling approach so you can compare results and understand tradeoffs.

- [Notebooks/Spam_Email_Classification.ipynb](Notebooks/Spam_Email_Classification.ipynb): End-to-end pipeline from cleaning and vectorization to model training, evaluation, and basic error analysis.
- [Notebooks/traditional_model.ipynb](Notebooks/traditional_model.ipynb): Classical ML baselines with feature extraction (e.g., bag-of-words or TF-IDF) and standard metrics.
- [Notebooks/RNN_model.ipynb](Notebooks/RNN_model.ipynb): `RNN` sequence model using embeddings to learn temporal patterns in email text.
- [Notebooks/GRU.ipynb](Notebooks/GRU.ipynb): `GRU` sequence model that improves training stability and handles long-range dependencies more efficiently.

Use these notebooks as concise, working references for exploring the dataset and validating model performance.
