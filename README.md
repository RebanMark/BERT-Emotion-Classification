# 🧠 Emotion Classification Using BERT

This project uses a fine-tuned BERT model to classify emotions in text such as **joy, sadness, anger, fear, love**, and **surprise**. It also includes model explainability using LIME and SHAP, along with an optional web interface for user input and prediction.

---

## 📁 Dataset

- Format: Text-label pairs
- Emotions: `joy`, `sadness`, `anger`, `fear`, `love`, `surprise`,`suicidal`
---

## 🔍 Model Overview

- **Base Model**: BERT (`bert-base-uncased`)
- **Classifier**: Uses `[CLS]` token for emotion prediction
- **Output**: Softmax layer giving probabilities for each emotion
- **Libraries**: PyTorch, Hugging Face Transformers

---

## 🧪 How to Use

### 1. Install Dependencies
```bash
pip install -r requirements.txt
```

## 🧾 Explainability

- **LIME**: Highlights which words influence the prediction
- **SHAP**: Provides local/global feature importance

---

## 🧠 Technologies Used

- BERT (via Hugging Face)
- PyTorch
- Scikit-learn
- LIME / SHAP
- CUDA (GPU support)
- Streamlit / Flask (for web UI)

---

## 🚀 Future Work

- Multilingual support  
- Larger datasets  
- Real-time API deployment  
- Emoji/slang handling
