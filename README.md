# 📰 Fake News Detection Using Multi-Model NLP

## 🚀 Overview  
This project compares multiple NLP models for binary classification of news articles as **fake** or **real**, using the popular "Fake and Real News" dataset. We implement and evaluate **LSTM**, **BERT**, and **RoBERTa** models.

---

## 🧠 Models
- 🔁 LSTM (Long Short-Term Memory)
- 🤖 BERT (Bidirectional Encoder Representations from Transformers)
- 🚀 RoBERTa (A robustly optimized BERT variant)

---

## 📊 Dataset
We use the publicly available Kaggle dataset:

🔗 https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset

Make sure to download and place `Fake.csv` and `True.csv` inside the `data/` folder.

---

## 🧪 Results

| Model   | Accuracy | F1-Score | Precision | Recall |
|---------|----------|----------|-----------|--------|
| LSTM    | 84%      | 0.83     | 0.84      | 0.83   |
| BERT    | 91%      | 0.90     | 0.90      | 0.90   |
| RoBERTa | 93%      | 0.92     | 0.93      | 0.92   |

🏆 **RoBERTa** delivered the highest performance.

---

## 📝 How to Run


#### 1️⃣ Clone the repository
```bash
git clone https://github.com/yourusername/fake-news-detection-nlp.git
cd fake-news-detection-nlp
```
#### 2️⃣ Install requirements
```bash
pip install -r requirements.txt
```
#### 3️⃣ Launch Jupyter Notebook
```bash
cd notebooks
jupyter notebook Fake_News_Detection.ipynb
```

---

## 📚 Tools & Libraries
- `transformers`
- `tensorflow`, `keras`
- `scikit-learn`
- `matplotlib`, `seaborn`
- `pandas`, `numpy`

---

## 👤 Credits
- **Author:** [Botirjon Salokhiddinov](https://github.com/botirjon05)
---

*Happy networking! If you have questions or want to suggest improvements, feel free to open an issue or fork the repo!* 😄
