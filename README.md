# nlp-getting-started

Kaggle competition: [Natural Language Processing with Disaster Tweets](https://www.kaggle.com/competitions/nlp-getting-started)

🎯 **Goal**: Classify tweets as real disasters (1) or not (0).

📊 **Public Score**: `0.76`

---

## 🧰 Approach

- Basic text feature engineering (length, caps, punctuation counts)
- TF-IDF vectorization (5000 features, n-grams 1-2)
- CatBoost classifier with keyword as categorical feature
- Trained offline in Kaggle Notebook (no internet)

---

## 📁 Files

- `notebook.ipynb` — main training and prediction notebook
- `submission.csv` — submission file (F1 ~0.76)

---

## 🚀 How to Reproduce

1. Run the notebook in Kaggle.
2. Submit `submission.csv` to the competition.

---

## 📈 Next Steps

- Add BERT embeddings → target: 0.83+
- Hyperparameter tuning with Optuna
- Model ensembling

---
