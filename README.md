# SENTIMENT ANALYSIS WITH NLP & TRANSFORMERS

## AI Academia Internship | Om Jangam | May 2026

---

## ABOUT

This project performs end-to-end sentiment analysis on the IMDB Movie Reviews dataset using Natural Language Processing (NLP), Machine Learning, Deep Learning, and Transformer-based models.

The project compares multiple approaches ranging from traditional TF-IDF based models to advanced transformer architectures such as DistilBERT.

---

## MODELS BUILT

1. Logistic Regression (TF-IDF baseline)
2. Naive Bayes (TF-IDF baseline)
3. Artificial Neural Network (PyTorch)
4. DistilBERT Transformer (Hugging Face)

---

## DATASET

* IMDB Movie Reviews Dataset
* 50,000 movie reviews
* 25,000 training samples
* 25,000 testing samples
* Labels:

  * Positive (1)
  * Negative (0)

Source: Hugging Face datasets library

---

## KEY FINDINGS

### Finding 1

DistilBERT achieved approximately 93% accuracy, compared to 88% accuracy from Logistic Regression — an improvement of nearly 5%.

### Finding 2

Logistic Regression and Naive Bayes achieved strong baseline performance above 85% accuracy using only TF-IDF features.

### Finding 3

The ANN training loss consistently decreased across epochs, showing convergence during training.

### Finding 4

Words such as “great”, “excellent”, “worst”, and “boring” strongly influenced sentiment predictions in classical models.

### Finding 5

DistilBERT produced high-confidence predictions with confidence scores often above 95%.

---

## RESULTS SUMMARY

* Logistic Regression: 88%
* Naive Bayes: 86%
* ANN: 90%
* DistilBERT: 93%

---

## HOW TO RUN

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
pip install transformers torch datasets
```

Open the notebook:

```bash
jupyter notebook
```

Then open:

```bash
Sentiment_Analysis_Final.ipynb
```

Run all cells from top to bottom.

---

## AUTHOR

Om Jangam — AI Academia AI/ML Internship 2026
