# 🎬 IMDB Sentiment Classifier with BERT and Hugging Face 

This project fine-tunes a BERT-based transformer model to classify movie reviews from the IMDB dataset as **positive** or **negative**.

##  Features

- Uses Hugging Face Transformers and Datasets
- Fine-tunes `bert-base-uncased` model
- Simple accuracy evaluation
- Accepts custom English reviews for real-time classification
- Ready to run on Google Colab

##  Requirements

Install the required packages with:

```bash
pip install -r requirements.txt
```
##  Installation Notes

This notebook includes `pip install` commands at the top to ensure compatibility when run in **Google Colab**.

If you're running this project locally or outside Colab, it's recommended to install all dependencies using the `requirements.txt` file:

```bash
pip install -r requirements.txt
```
##  How to Run

Download the notebook and open it with [Google Colab](https://colab.research.google.com/).

### ⚠ Important: Use GPU

Before running, go to:

> Runtime > Change runtime type > Set Hardware Accelerator to **GPU**

##  Model

- Base model: `bert-base-uncased`
- Dataset: `IMDB` (via Hugging Face Datasets)
- Binary classification: Positive / Negative sentiment

---

##  Example

```text
Input:  "This movie was surprisingly good and the performances were excellent."
Output: Positive 
```

---

##  Files

- `imdb_sentiment_classifier.ipynb`: Main training notebook
- `requirements.txt`: Python dependencies
- `README.md`: Project overview

---

##  Author

Created by Alejandro Galindo Valencia.  
Feel free to fork or contribute!
