# 🤖 Arabic Sentiment Analysis using AraBERT

# 📌 Project Overview
This repository features an NLP project that fine-tunes the **AraBERT (v0.2-base)** model for binary sentiment analysis on Arabic text. Using transfer learning, the model is trained to classify inputs as either **Positive (إيجابي)** or **Negative (سلבי)** with high precision.

This project was developed for the Mining and Machine Learning course at **Braude Academic College**.

## 🛠️ Tech Stack & Libraries
* **Language:** `Python`
* **Deep Learning Framework:** `TensorFlow` / `Keras`
* **NLP & Transformers:** Hugging Face `transformers` (`AutoTokenizer`, `TFAutoModelForSequenceClassification`)
* **Data Science:** `Pandas`, `NumPy`, `Scikit-learn`
* **Visualization:** `Matplotlib`
* **Dataset:** Arabic Jordanian General Tweets (AJGT)

## 📂 Repository Structure
* **`Arabic Sentiment Analysis using AraBERT.ipynb`**: The primary Jupyter Notebook featuring the full pipeline: preprocessing, fine-tuning, training, and evaluation.
* **`Final Word.docx`**: Technical report detailing the methodology, architecture, and academic results.


## 🚀 Model Architecture & Pipeline
1. [cite_start]**Preprocessing:** Leveraged the `arabert_preprocess` library to handle Arabic-specific challenges like tashkeel removal, tatweel removal, and character normalization[cite: 1, 2].
2. [cite_start]**Fine-Tuning:** Specifically utilized **AraBERT v0.2-base**, which is pre-trained on a massive 77GB Arabic corpus, allowing for deep contextual understanding[cite: 1, 3].
3. [cite_start]**Training:** Fine-tuned on the **AJGT dataset** (1,800 annotated tweets) using a 10% validation split and a reproducible random seed (42)[cite: 1, 2].
4. [cite_start]**Optimization:** Implemented a Learning Rate of $2 \times 10^{-5}$ and the Adam optimizer for stable convergence[cite: 2, 3].

## 📊 Results & Performance
The model achieves exceptional performance on the AJGT test set:
* [cite_start]**Accuracy:** ~94% [cite: 2, 3]
* [cite_start]**Loss:** ~0.19 [cite: 3]
* [cite_start]**Key Finding:** AraBERT significantly outperforms traditional RNN/LSTM architectures in Arabic sentiment tasks due to its transformer-based attention mechanism[cite: 2].
  
## 💻 How to Run
To run this notebook locally or in Google Colab:
1. Clone the repository:
   ```bash
   git clone [https://github.com/rober-saliba/Arabic-Sentiment-Analysis-Arabert.git](https://github.com/rober-saliba/Arabic-Sentiment-Analysis-Arabert.git)
2.Ensure you have the required libraries installed:
   ```bash
   pip install transformers tensorflow pandas numpy scikit-learn matplotlib
```
3. Open the `.ipynb` file in Jupyter or upload it directly to Google Colab and run the cells sequentially.







