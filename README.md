# Women Clothing Review Sentiment Analysis

## 📌 Project Overview
This project focuses on **predicting customer sentiment** based on reviews from a **Women Clothing E-Commerce** dataset. The goal is to classify reviews based on their sentiment (ratings) using **Multinomial Naive Bayes**, a common text classification algorithm.

## 📊 Dataset
- **Source:** Women Clothing E-Commerce Review dataset
- **Features Used:**
  - `Review` (text data) – Input feature (X)
  - `Rating` (1 to 5) – Target variable (Y)
- **Preprocessing:**
  - Handled missing values by replacing empty reviews with "No Review"
  - Converted text data into numerical format using **CountVectorizer** (bigrams & trigrams)

## 🛠️ Tech Stack
- **Python**
- **Pandas, NumPy** – Data handling
- **Scikit-learn** – Machine Learning (Naive Bayes Classifier)

## 🚀 Steps Involved
1. **Data Cleaning** – Handle missing values.
2. **Feature Engineering** – Convert text reviews into numerical vectors.
3. **Model Training** – Train a **Multinomial Naive Bayes** model.
4. **Evaluation** – Measure accuracy and visualize results.

## 🔥 Final Output
- The trained model predicts the **sentiment (rating) of a given review**.
- Performance is evaluated using accuracy and a confusion matrix.

## 📂 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/women-clothing-sentiment.git
   cd women-clothing-sentiment
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open `women_cloth_project.ipynb` and execute the cells.

## 📌 Future Enhancements
- Improve accuracy using **TF-IDF** vectorization.
- Experiment with **Deep Learning models (LSTMs, Transformers)**.
- Deploy as a **Web API or Dashboard** for real-time sentiment analysis.

## 🏆 Contributing
Feel free to fork and improve the project! PRs are welcome. 

## 📜 License
This project is open-source under the **MIT License**.

