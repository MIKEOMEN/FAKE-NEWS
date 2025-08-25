# 📰 Fake News Detection using NLP & Machine Learning

This project uses **Natural Language Processing (NLP)** and **Machine Learning** to classify news headlines as **REAL** or **FAKE**. It demonstrates how misinformation can be detected using a combination of text processing and classification algorithms.

---

## 📌 Project Highlights

* 📑 Input: News headline (short text)
* 🎯 Output: Predicted label – `REAL` or `FAKE`
* 🔧 Techniques used:

  * Text preprocessing (cleaning, stopwords removal)
  * Feature extraction (TF-IDF / CountVectorizer)
  * Supervised machine learning (e.g., Logistic Regression)

---

## 🧠 Algorithms Used

* Logistic Regression

---

## 🗃️ Dataset

Sample of the dataset:

| Text                                                    | Label |
| ------------------------------------------------------- | ----- |
| The moon landing was staged in a Hollywood studio.      | FAKE  |
| NASA confirms presence of water on the moon.            | REAL  |
| COVID-19 vaccine contains microchips for tracking.      | FAKE  |
| The Prime Minister announced a new infrastructure plan. | REAL  |

* Format: CSV with `text` and `label` columns

---

## 📁 Project Structure

```
├── Fake News Detection.ipynb         # Jupyter notebook with model and evaluation
├── dataset.csv                       # Sample dataset with text and labels
├── README.md                         # Project documentation
```

---

## 🚀 How to Run

1. **Clone the repository**

   ```bash
   git clone https://github.com/MIKEOMEN/Fake-News-Detection-.git
   cd fake-news-detection
   ```

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the notebook**

   * Open `Fake News Detection.ipynb` using Jupyter Notebook or VS Code
   * Execute cells step by step

---

## 📈 Model Performance

You can evaluate the model using:

* Accuracy
* Confusion Matrix
* Precision, Recall, F1-score

---

## 💡 Future Improvements

* Add more real-world data for training
* Deploy as a web app using Flask or Streamlit
* Use deep learning models like LSTM or BERT

---

## 🙌 Acknowledgements

* Scikit-learn
* Pandas & NumPy
* Jupyter Notebook
* Dataset inspired by examples of fake and real news

