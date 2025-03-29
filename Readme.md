# SMS Spam or Ham Classifier

## 📌 Project Overview
This project is a machine learning-based SMS spam classifier that determines whether a given message is spam or ham (not spam). It leverages Natural Language Processing (NLP) techniques and classification algorithms to enhance accuracy.

## 📊 Dataset
- **File:** `spam.csv`
- **Description:** The dataset consists of 5,574 SMS messages labeled as spam or ham.
- **Columns:**
  - `Target`: Label (spam/ham)
  - `Text`: The message content
- **Preprocessing:**
  - Removed duplicates and missing values.
  - Performed text cleaning (stopword removal, stemming, lemmatization).
  - Converted text into numerical format using TF-IDF vectorization.

## 🔍 Exploratory Data Analysis (EDA)
### Techniques Used:
- **Word Clouds & Frequency Analysis:** Identified most common words in spam and ham messages.
- **Message Length Distribution:** Spam messages tend to be longer and contain more promotional keywords.

## 🤖 Machine Learning Models Used
- **Naïve Bayes Classifier (Best Performing Model)**
- **Logistic Regression**
- **Support Vector Machine (SVM)**
- **Random Forest Classifier**

## 📈 Evaluation Metrics
- **Accuracy:** Measures correct classifications.
- **Precision:** Percentage of messages predicted as spam that are actually spam.
- **Recall:** Percentage of actual spam messages correctly identified.
- **F1-Score:** Balances precision and recall.

## 🔬 Key Findings
- Spam messages have repetitive patterns (e.g., “Win now!”, “Limited offer”).
- Feature engineering (stopword removal, n-grams) improves classification accuracy.
- Naïve Bayes performed best due to its probabilistic text classification approach.

## 🛠️ Technologies Used
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, NLTK)
- **Jupyter Notebook**
- **Machine Learning & NLP techniques**

## 🚀 Future Improvements
- Implement deep learning models (LSTMs, transformers) for better accuracy.
- Train on multilingual datasets to expand usability.
- Deploy the model as a real-time SMS filter.

## 🏆 Contributions
Contributions are welcome! Feel free to open issues or submit pull requests.

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### 📬 Contact
For queries, feel free to reach out via kamalagrahari2003@gmail.com.

