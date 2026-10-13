# IMDB Sentiment Classification (Assignment 6)

Binary sentiment classification of movie reviews comparing two models:

| Model | Type | Input |
|---|---|---|
| TF-IDF MLP | Neural network | 20k TF-IDF uni+bi-gram vector |
| BiLSTM | Deep learning | Learned word embeddings, 256-token sequences |

**Dataset:** https://www.kaggle.com/datasets/columbine/imdb-dataset-sentiment-analysis-in-csv-format  
**Metrics:** Precision, Recall, F1, AUC-ROC (+ accuracy, confusion matrix)

## Run
Open `imdb_sentiment_classification.ipynb` in Google Colab (GPU runtime) and run all cells,
or locally: `pip install -r requirements.txt` then `jupyter notebook`.

Outputs (plots + `metrics.csv`) are saved to `results/`.
