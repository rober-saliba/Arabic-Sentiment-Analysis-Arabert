# 🤖 Arabic Sentiment Analysis using AraBERT

## 📌 Project Overview
This repository contains a Machine Learning project focused on Natural Language Processing (NLP). It fine-tunes the **AraBERT** (Arabic Bidirectional Encoder Representations from Transformers) model to perform binary sentiment analysis on Arabic text, classifying inputs as either **Positive (إيجابي)** or **Negative (سلبي)**.

This project was developed as part of the Mining and Machine Learning course at Braude Academic College.

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Machine Learning Framework:** TensorFlow / Keras
* **NLP & Transformers:** Hugging Face `transformers` (AutoTokenizer, TFAutoModelForSequenceClassification)
* **Data Processing:** Pandas, NumPy, Scikit-learn (`train_test_split`)
* **Visualization:** Matplotlib
* **Environment:** Jupyter Notebook / Google Colab

## 📂 Repository Structure
* `Arabic Sentiment Analysis using AraBERT.ipynb`: The main Jupyter Notebook containing the data preprocessing, model fine-tuning, training loops, and evaluation metrics.
* `Final Word.docx`: Comprehensive project report detailing the methodology, architecture, and academic findings.
* `Fine-tune BERT model for Sentiment Analysis in Google.pptx`: Slide deck summarizing the project execution and results.

## 🚀 Model Architecture & Pipeline
1. **Data Preprocessing:** Handled Arabic text tokenization using AraBERT's specialized tokenizer to properly manage complex Arabic morphology and dialect nuances.
2. **Dataset Splitting:** Divided the data into training and testing sets utilizing a reproducible random seed (`42`).
3. **Fine-Tuning:** Adapted the pre-trained BERT architecture for sequence classification, leveraging transfer learning to achieve high accuracy on a specific Arabic dataset.
4. **Evaluation:** Assessed model performance utilizing standard ML metrics including validation accuracy and loss.

## 📊 Results & Performance
The model was evaluated on a dedicated testing set to measure its classification accuracy. By leveraging the pre-trained AraBERT architecture, the fine-tuned model successfully achieved high accuracy in distinguishing between positive and negative Arabic sentiment. 

* **Key Finding:** The model demonstrated a strong capability in the contextual understanding of Arabic sentence structures, effectively differentiating between positive ('إيجابي') and negative ('سلبي') sentiment markers.

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







