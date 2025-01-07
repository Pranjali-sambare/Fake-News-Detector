## Tweet-Based Fake News Detector


Fake News Detection Using Machine Learning

This project aims to develop a machine learning model to predict whether a news article is real or fake using the `FakeNewsNet` dataset.

## Table of Contents
- [Introduction]
- [Dataset]
- [Installation]
- [Usage]
- [Model]
- [Results]
- [Contributing]
- [License]


## Introduction
Fake news is a significant problem in today's digital age, leading to misinformation and public confusion. This project utilizes machine learning to classify news articles as real or fake based on the number of tweets referencing the article.


## Dataset
The dataset used in this project is `FakeNewsNet.xlsx`, which contains columns like:
- `title`: Title of the news article.
- `news_url`: URL of the news article.
- `source_domain`: Domain of the news source.
- `tweet_num`: Number of tweets referencing the article.
- `real`: Binary label indicating real (1) or fake (0) news.


## Installation
To set up this project locally, follow these steps:


1. Clone the repository:
   ```bash
   (https://github.com/Pranjali-sambare/Fake-News-Detector)
   cd fake-news-detection


## Usage

Data Preprocessing: The dataset is preprocessed to handle missing values and extract relevant features.

Model Training: A Logistic Regression model is trained using tweet_num as the feature.

Prediction and Evaluation: The model's performance is evaluated using accuracy, precision, recall, and F1-score.

## Run the Model

(python model.py)


## Model

The model used for classification is Logistic Regression, which is suitable for binary classification tasks.


## Results

The model's performance is evaluated on the test set, providing metrics such as accuracy, precision, recall, and F1-score. The results demonstrate the model's effectiveness in predicting real vs. fake news based on tweet data.


## Contributing

Contributions are welcome! Please follow these steps to contribute:


## Fork the repository.

Create a new branch.

Commit your changes.

Push to the branch.

Open a pull request.

## License

This project is licensed under the MIT License.
