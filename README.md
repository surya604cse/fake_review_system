# Fake Review Detection System

## Overview

The Fake Review Detection System is a machine learning-based project that identifies whether a product review is genuine or fake. This project uses Natural Language Processing (NLP) techniques and a classification algorithm to analyze textual data and make predictions.

This system is useful for e-commerce platforms to detect spam or misleading reviews and improve trust among users.

---

## Features

* Detects fake and genuine reviews
* Uses NLP techniques for text processing
* Implements machine learning classification
* Provides real-time prediction for user input
* Works with a dataset of 1000 reviews
* High accuracy with optimized model

---

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Natural Language Processing (NLP)

---

## Dataset

The dataset contains 1000 product reviews with labels:

* 0 → Genuine Review
* 1 → Fake Review

Each record consists of:

* Review text
* Label

---

## Project Structure

```
FakeReviewProject/
│
├── fake_reviews_1000_dataset.csv
├── main.ipynb
└── README.md
```

---

## Installation

1. Clone the repository:

```
git clone https://github.com/your-username/fake-review-detector.git
```

2. Navigate to the project folder:

```
cd fake-review-detector
```

3. Install required libraries:

```
pip install pandas scikit-learn
```

---

## Usage

1. Open Jupyter Notebook:

```
jupyter notebook
```

2. Run the notebook file:

```
main.ipynb
```

3. Execute all cells to train the model and test predictions.

---

## How It Works

1. Load dataset using Pandas
2. Convert text into numerical format using TF-IDF
3. Train model using Naive Bayes algorithm
4. Evaluate accuracy
5. Predict whether a review is fake or genuine

---

## Example Output

```
Review: This is a scam product
Result: Fake Review

Review: Very good quality product
Result: Genuine Review
```

---

## Accuracy

The model achieves high accuracy (around 95%–99%) on the dataset used.

---

## Future Improvements

* Use deep learning models (LSTM, BERT)
* Add real-world datasets (Amazon/Yelp reviews)
* Build a web application using Flask or React
* Improve model generalization

---

## Author

Surya

---

## License

This project is for educational purposes.
