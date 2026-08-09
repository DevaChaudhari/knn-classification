# KNN Classification Lab

Coursework for Flinders University Master of Data Science — Module 2 Worksheet (Chapter 4).

Implements k-nearest neighbours (KNN) classification across three different datasets, covering model training, prediction, and evaluation.

## Contents

- **Checkpoint 1 — Iris Classification**: KNN classifier on the classic Iris dataset (sklearn built-in).
- **Checkpoint 2 — Digit Classification**: KNN classifier on the handwritten digits dataset.
- **Checkpoint 3 — Customer Classification**: KNN classifier on a real-world customer dataset (`att.csv`), predicting customer categories from demographic and usage features.

## Files

```
├── notebooks/
│   └── Module_2_Worksheet.ipynb   # Main worksheet with all three checkpoints
├── data/
│   └── att.csv                    # Customer dataset used in Checkpoint 3
├── requirements.txt
└── README.md
```

## Setup

```bash
pip install -r requirements.txt
jupyter notebook notebooks/Module_2_Worksheet.ipynb
```

## Tech Stack

- Python
- scikit-learn (KNeighborsClassifier)
- pandas / numpy
- Jupyter Notebook

## Author

Devendra Chaudhari — Master of Data Science (AI Specialisation), Flinders University
