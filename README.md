# Everyday Sound Classification

Classifies everyday sounds into 12 categories using SVM, Random Forest, and Gradient Boosting. The best model is also evaluated on my own recordings.

## Run locally

From the repository directory, run:

```bash
python -m pip install jupyter pandas numpy soundfile librosa matplotlib seaborn scikit-learn
unzip dataset.zip -d .
unzip my_recordings.zip -d my_recordings
jupyter notebook audio_classification.ipynb
```

Run all cells. The notebook expects `metadata.csv` beside it and a second `metadata.csv` inside `my_recordings/`, with an `audio/` folder alongside each CSV.
