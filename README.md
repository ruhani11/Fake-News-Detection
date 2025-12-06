# Fake News Detection using Deep Learning (Transformers)

## Overview
This project implements a transformer-based deep learning model for classifying news articles as **Real** or **Fake**. The model is trained on the **WELFake Dataset** and achieves **99% accuracy**, **0.991 F1-score**, and **AUC 0.9997**.

---

## Dataset
We use the publicly available **WELFake Fake News Classification Dataset**.

**Dataset Link:**  
https://www.kaggle.com/datasets/saurabhshahane/fake-news-classification

The dataset contains over **72,000** labeled news articles.

---

## Features
- Transformer-based fake news classifier  
- Text preprocessing pipeline  
- Tokenization using HuggingFace  
- Fine-tuning on WELFake dataset  
- Evaluation using Accuracy, Precision, Recall, F1-score  
- Visualizations:
  - ROC Curve  
  - Precision–Recall Curve  
  - Confusion Matrix  
  - Training vs Validation Loss Curve  

---

## Model Performance

| Metric     | Score    |
|------------|----------|
| Accuracy   | 99.08%   |
| Precision  | 99.15%   |
| Recall     | 99.07%   |
| F1 Score   | 99.11%   |
| AUC ROC    | 0.9997   |

---

## Project Structure
.
├── fake_news_detection.ipynb # Colab notebook with all source code
├── dataset from kaggle
└── README.md # Project documentation

---

## Installation

```bash
pip install transformers datasets scikit-learn matplotlib seaborn
How to Run
1. Train the Model
trainer.train()

2. Evaluate the Model
trainer.evaluate()

3. Generate Visualizations

Run the visualization code blocks in the notebook:

ROC Curve

PR Curve

Confusion Matrix

Training Loss Curve

Methodology

Load and clean dataset

Merge title and text fields

Tokenize text using transformer tokenizer

Convert to HuggingFace dataset format

Fine-tune transformer model

Evaluate using standard metrics

Visualize results

Save model for deployment

##Technologies Used

Python

PyTorch

HuggingFace Transformers

Scikit-Learn

Matplotlib

Seaborn

Google Colab

Conclusion

The transformer model achieves near-perfect accuracy on the WELFake dataset, proving its effectiveness for real-world fake news detection and misinformation analysis.

License

This project is licensed under the MIT License.
