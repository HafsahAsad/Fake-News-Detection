# Fake News Detection

This project is a **Fake News Detection system** built in Python using machine learning and natural language processing (NLP). The goal of the project is to classify news articles as **REAL** or **FAKE** based on the text content.

---

## 📝 Project Overview

- **Dataset**: Contains two CSV files: `Fake.csv` (fake news) and `True.csv` (real news).  
- **Objective**: Build a machine learning model to classify news articles.  
- **Techniques Used**:
  - Data preprocessing (cleaning, tokenization, vectorization)
  - Feature extraction using TF-IDF
  - Classification using machine learning models (Logistic Regression, Random Forest)
  - Model evaluation using accuracy, confusion matrix, and classification report
- **Outcome**: A trained ML model that predicts the authenticity of news articles.

---

## 💻 Project Structure

Fake-News-Detection/
│
├── Fakenews.ipynb # Main Jupyter notebook with all code
├── Fake.csv # Dataset: fake news articles
├── True.csv # Dataset: real news articles
├── requirements.txt # Python dependencies
└── README.md # Project overview and instructions


---

## ⚙️ Setup Instructions

1. **Clone the repository:**

```bash
git clone https://github.com/HafsahAsad/Fake-News-Detection.git
cd Fake-News-Detection

2. Create a virtual environment (recommended):
python3 -m venv env
source env/bin/activate       # For Mac/Linux
env\Scripts\activate          # For Windows

3. Install dependencies:
pip install -r requirements.txt

4. Open the Jupyter notebook:
jupyter notebook Fakenews.ipynb

How To Use:
-Load the datasets (Fake.csv and True.csv) into the notebook.
-Follow the notebook step-by-step:
  1. Data preprocessing
  2. Feature extraction
  3. Model training

-Evaluation
-Modify the notebook to test new news articles for classification.

Notes:
-Some dataset files are large (>50MB). If you encounter issues pushing to GitHub, consider using Git LFS.
-This project is designed as a portfolio piece to showcase AI/ML skills, including data preprocessing, feature engineering, and machine learning modeling.

Outcome:
-By completing this project, you will have:
-A fully functional Fake News Detection system
-Experience with Python, pandas, scikit-learn, and NLP
-A portfolio-ready project to share on GitHub and LinkedIn

License:
-This project is open-source and available for learning and portfolio purposes.

