# NLP_realFakeNewsDetetcion

This project aims to build a NLP model that can distinguish between real and fake news articles. The system uses various classification algorithms and is evaluated on a labeled dataset of news articles.

## Project Structure

- `True.csv` and `Fake.csv`: Datasets containing real and fake news articles, respectively.
- `fake_news_detection.ipynb`: Jupyter Notebook containing the code for data preprocessing, model training, and evaluation.
- `README.md`: Project description and usage instructions.

## Features

- Preprocessing of text data to clean and prepare it for modeling.
- Vectorization of text using TF-IDF.
- Training of multiple classification models:
  - Logistic Regression
  - Decision Tree
  - Random Forest
- Evaluation of models using accuracy, precision, recall, and F1-score metrics.
- Predictive capability on new samples.

## Usage

1. **Clone the repository:**

   ```bash
   git clone https://github.com/narendrasaisatish/NLP_realFakeNewsDetetcion.git
   cd NLP_realFakeNewsDetetcion
