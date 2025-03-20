# 📰 News Article Classification Project

## 📖 Project Overview
This project focuses on building a robust machine learning pipeline to classify news articles into five categories: **Business, Entertainment, Politics, Sport, and Tech**. We used **Logistic Regression**, **SVM**, and **Linear SVC** models to identify the best-performing solution. The final deployment-ready solution leverages Logistic Regression with TF-IDF vectorization.

---

## 📂 Dataset
- **Source:** Provided as a ZIP file containing text articles categorized by folders.
- **Categories:** Business, Entertainment, Politics, Sport, Tech.

---

## 🔎 Exploratory Data Analysis (EDA)
- Verified category distribution.
- Analyzed article lengths and content structure.
- Visualized the balance and frequency of articles per category.

---

## ✏️ Data Preprocessing
- Lowercased text.
- Removed special characters and numbers.
- Stopwords removal using NLTK.
- Lemmatization with WordNet.
- Applied **TF-IDF Vectorization**.
- Explored distance metrics for understanding text similarity.

---

## 📊 Model Training
### ✅ Logistic Regression
- Used `max_iter=1000`.
- Performed feature selection with different feature counts.
- Achieved **96.85% accuracy** on test data.

### ✅ Support Vector Machine (SVM)
- Hyperparameter tuning using GridSearchCV.
- Final accuracy: **96.17%**.

### ✅ Linear SVC
- Accuracy: **96.4%**, but considered redundant.

| Model                     | Test Accuracy |
|---------------------------|---------------|
| Logistic Regression       | **96.85%**    |
| Tuned SVM (RBF Kernel)    | 96.17%        |
| Linear SVC                | 96.4%         |

---

## ✅ Model Evaluation Metrics
- Accuracy, Precision, Recall, and F1 Score.
- Confusion matrix visualizations.
- ROC curve plots for each category.

---

## 💾 Model Saving & Deployment Readiness
- **logistic_regression_model.pkl**: Saved trained model.
- **tfidf_vectorizer.pkl**: Saved vectorizer.
- Successfully tested on 15 new sample articles.

---

👉 [View Full Project Report (PDF)](Project_Report.pdf)

---
## 🚀 How to Run
1. Clone the repository.
2. Install dependencies using `pip install -r requirements.txt`.
3. Run the notebook: `News_Articles.ipynb`.
4. Load models and classify your own text data.

---

## 🔮 Future Enhancements
- Explore models like **Random Forest**, **XGBoost**, and deep learning architectures (**LSTM**, **BERT**).
- Deploy via **Flask API** or **FastAPI**.
- Create **Streamlit-based interactive UI**.
- Integrate with cloud services like **AWS**, **Azure**, or **GCP**.
- Build ETL pipelines and add live data monitoring dashboards.

---

## 🤝 Acknowledgments
Special thanks to the course mentors and reviewers for continuous feedback and support.

> ⭐ *If you find this project helpful, feel free to star the repository and connect with me on [LinkedIn](https://www.linkedin.com).*

