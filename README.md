# 🎬 Movie Review Sentiment Analysis

An end-to-end Natural Language Processing (NLP) and Machine Learning project that classifies movie reviews as **Positive** or **Negative** using **Multinomial Naive Bayes** with an interactive **Streamlit** web application.

---

## 📌 Features

- **Interactive Web App**: Built with [Streamlit](https://streamlit.io/) for real-time sentiment prediction.
- **NLP Preprocessing Pipeline**:
  - Stopwords removal using NLTK
  - Tokenization
  - Word stemming with Porter Stemmer
- **Machine Learning Model**: Multinomial Naive Bayes (`MultinomialNB`) trained on vectorized text features.
- **Text Vectorization**: Bag-of-Words representation using `CountVectorizer`.

---

## 📁 Project Structure

```text
Movie_Review_Analysis/
├── Deployment_code/
│   ├── main.py              # Streamlit web application
│   ├── model.pkl            # Trained MultinomialNB model
│   ├── vectorizer.pkl       # CountVectorizer model
│   └── Untitled.py.ipynb    # Model training and exploration notebook
├── Movie project/
│   ├── Untitled.py.ipynb    # Training notebook
│   ├── model.pkl
│   └── vectorizer.pkl
├── requirements.txt         # Project dependencies
├── .gitignore               # Ignored files and directories
└── README.md                # Project documentation
```

---

## 🚀 Getting Started

### 1. Prerequisites
Ensure you have Python 3.9+ installed on your system.

### 2. Clone the Repository
```bash
git clone https://github.com/BesthaMahesh/movie_review_analysis.git
cd movie_review_analysis
```

### 3. Create and Activate a Virtual Environment
```bash
# Windows
python -m venv venv
venv\Scripts\activate

# macOS / Linux
python3 -m venv venv
source venv/bin/activate
```

### 4. Install Dependencies
```bash
pip install -r requirements.txt
```

### 5. Download NLTK Data (First-time setup)
```bash
python -c "import nltk; nltk.download('stopwords'); nltk.download('punkt'); nltk.download('punkt_tab')"
```

---

## 💻 Running the Application

Navigate to the `Deployment_code` directory and start the Streamlit server:

```bash
cd Deployment_code
streamlit run main.py
```

Once started, open your browser and navigate to:
```
http://localhost:8501
```

---

## 🛠️ Technology Stack

- **Language:** Python
- **Libraries & Frameworks:**
  - `Streamlit` - Web interface
  - `scikit-learn` - Machine learning model and vectorization
  - `NLTK` - Natural language processing and text cleaning
  - `pandas` - Data manipulation
  - `pickle` - Model serialization

---

## 👤 Author

- **Mahesh Bestha** - [GitHub Profile](https://github.com/BesthaMahesh)
