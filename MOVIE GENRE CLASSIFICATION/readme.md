## 🎬 Codsoft-MOVIE-GENRE-CLASSIFICATION

This project predicts the **genre of a movie** from its plot summary using machine learning.

### 🔧 Workflow:
- Plots are cleaned: lowercased, punctuation removed, stopwords filtered.
- Feature extraction via **TF-IDF Vectorizer**.
- Genre labels are encoded using **LabelEncoder**.
- **Logistic Regression** is trained on the plot features.

### 📊 Model Evaluation:
- Accuracy: ~87%
- Classification Report (Precision, Recall, F1-score)
- Confusion Matrix
- ROC-AUC Curve

This model performs well in identifying the movie genre from the description.

---