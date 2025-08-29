# 📝 NLP Sentiment Analyser

A Natural Language Processing (NLP) project to perform **sentiment analysis** on user reviews.  
This application classifies text into **Positive, Neutral, or Negative** categories using machine learning techniques.

---

## 🚀 Features
- Preprocesses raw text (tokenization, stopword removal, lemmatization).
- Converts text into numerical features using **TF-IDF**.
- Trains a **Logistic Regression / Naïve Bayes / ML model** for classification.
- Interactive app (`app.py`) to test custom text inputs.
- Jupyter Notebook (`nlp.ipynb`) for end-to-end training and analysis.
- Well-structured project with modular code and datasets.

---

## 📂 Project Structure


NLP_Sentiment_Analyser/
│── data/ # Dataset files
│── model/ # Saved model files
│── app.py # Streamlit/Flask app for sentiment prediction
│── nlp.ipynb # Jupyter Notebook (EDA, training, evaluation)
│── requirements.txt # Python dependencies
│── README.md # Project documentation


---

## ⚙️ Installation

1. Clone the repository:
   ```bash
       git clone https://github.com/VigneshEilik/NLP_Sentiment_Analyser.git
       cd NLP_Sentiment_Analyser


Create a virtual environment (optional but recommended):

python -m venv venv
source venv/bin/activate   # On Mac/Linux
venv\Scripts\activate      # On Windows


Install dependencies:

pip install -r requirements.txt

# ▶️ Usage

* 1. Run Jupyter Notebook (Training/EDA)
* jupyter notebook nlp.ipynb

# 2. Run the App

* streamlit run app.py

Streamlit’s local link.

# 📊 Example Output

* Input:

"This ChatGPT app is really helpful and fun to use!"


* Output:

* Sentiment: Positive ✅

# 📦 Requirements

All dependencies are listed in requirements.txt
.

# 📌 Future Improvements

Add transformer-based models (BERT, RoBERTa).

Extend to multi-class emotion classification.

Deploy on Heroku / AWS / HuggingFace Spaces.

# 🤝 Contributing

Contributions are welcome!

Fork this repo

Create a feature branch (git checkout -b feature-name)

Commit changes (git commit -m 'Add feature')

Push to branch (git push origin feature-name)

Create a Pull Request

# 📜 License

This project is licensed under the MIT License - see the LICENSE
 file for details.





