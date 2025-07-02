## 📦 Codsoft-SPAM-SMS-DETECTION

This project classifies text messages as **spam or ham (non-spam)** using machine learning.

### 🔧 Workflow:
- Dataset is loaded and preprocessed (lowercasing, punctuation removal).
- **TF-IDF Vectorization** is used to convert text into numerical features.
- Labels are encoded using **LabelEncoder**.
- Model is trained using **Multinomial Naive Bayes**.

### 📊 Model Evaluation:
- Accuracy Score
- Precision, Recall, F1-score
- Confusion Matrix

The model effectively detects spam messages based on their textual features.

---