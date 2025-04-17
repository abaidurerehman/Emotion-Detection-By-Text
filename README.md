# Multi-Label Emotion Recognition from Text 🎭🧠

This project focuses on building a robust system to classify **multiple emotions** (e.g., joy, sadness, anger) from **textual input** using state-of-the-art transformer models.

---

## 📌 Task Objective

Develop a system to accurately **detect and classify multiple emotions** present in a given text, enabling applications like sentiment analysis, customer feedback interpretation, and social media monitoring.

---

## 📂 Dataset

- **GoEmotions** by Google
- Contains over 58k English Reddit comments labeled with 27 emotion categories + neutrality.
- [GoEmotions Dataset on HuggingFace](https://huggingface.co/datasets/go_emotions)

---

## 🧪 Methodology

### 1. Data Preprocessing
- Cleaned and tokenized text
- Handled **imbalanced data** using class reweighting or resampling techniques

### 2. Model Training
- Fine-tuned a **BERT-based model** for **multi-label classification**
- Used sigmoid activation in the output layer to allow for multiple labels per input

### 3. Evaluation Metrics
- **Hamming Loss**: Measures the fraction of incorrect labels
- **F1 Score (Micro & Macro)**: Balances precision and recall across all classes

### 4. Real-World Testing
- Tested on real-world textual inputs such as:
  - Customer reviews
  - Social media posts
  - User-submitted feedback

---

## ✅ Outcome

- A trained model capable of recognizing **multiple emotional tones** in a single piece of text
- Fine-tuned BERT model with high F1 performance on validation data
- Ready to integrate into applications requiring **emotional understanding from text**

---

## 🚀 How to Run

```bash
# Install dependencies
pip install -r requirements.txt

# Train the model
python train.py

# Predict emotions on new text
python predict.py --text "I'm so happy but also a bit nervous!"
```


---

## ✨ Future Work

- Integrate into a **web app** for real-time emotion detection
- Expand to multilingual emotion recognition
- Combine with speech/text pipelines for multi-modal analysis

---

## 📬 Contact

For questions or collaborations:  
**AbaidUr-E-Rehman**  
📧 [LinkedIn](https://www.linkedin.com/in/abaidur-e-rehman-03748a272/)

---

## 📜 License

This project is licensed under the MIT License.
```
