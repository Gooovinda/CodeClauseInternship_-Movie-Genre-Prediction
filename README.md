# Movie Genre Prediction Based on Plot Summaries 🎥🔍

This project predicts a movie's genre using NLP and machine learning based on its plot summary.

## 📌 Project Objective
Build a text classification model to predict the main genre of a movie from its plot description.

## 🧠 Technologies Used
- Python
- Pandas
- NLTK
- Scikit-learn

## ⚙️ Workflow
1. Loaded and merged TMDB Movies and Credits datasets
2. Extracted and cleaned the plot summaries
3. Mapped genre lists to the **main genre** (first genre)
4. Preprocessed the plot text:
   - Cleaned, tokenized, and lemmatized
5. Converted text to numerical data using TF-IDF
6. Trained a Logistic Regression model for multi-class classification
7. Evaluated using accuracy and f1-score

## 📈 Results
- **Accuracy:** ~44%
- Model performed well for common genres like Drama, Comedy, and Action
- Future improvements: Try Word2Vec or BERT for better text understanding

## 📂 Datasets
- [🔗 TMDB Movies Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
- [🔗 TMDB Credits Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

## 🚀 How to Run

1. Clone this repository
2. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
3. Place the `.csv` files into a folder named `data/`
4. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   Open and run the notebook:
5.movie_genre_prediction.ipynb
