# Twitter Sentiment Analysis

## Introduction
This project aims to analyze the emotional tone or sentiment in tweets using machine learning techniques. It includes a Jupyter Notebook (`Ocenka_Twiiter.ipynb`) demonstrating data preprocessing, training a machine learning model, and evaluating its performance. The dataset used for training (`Train.csv`) is also part of this repository.

## Project Features
- Comprehensive data preprocessing for Twitter data.
- Application of machine learning techniques for sentiment analysis.
- Detailed evaluation of model performance.

## Getting Started

### Prerequisites
To run this project, you will need:
- Python 3.x
- Jupyter Notebook
- Libraries: pandas, NumPy, scikit-learn, matplotlib (for installation, follow the instructions below)

### Installation and Setup
1. Clone the repository to your local machine:

git clone https://github.com/erema0324/twitter-sentiment-analysis.git

2. Install the required Python libraries:

pip install pandas numpy scikit-learn matplotlib

### Running the Notebook
1. Navigate to the cloned repository's directory.
2. Open Jupyter Notebook: win+R -> cmd -> jupyter notebook
3. In the Jupyter interface, open `Ocenka_Twiiter.ipynb`.
4. Execute the notebook cells in order to see the analysis and model training process.

## Dataset
The `Train.csv` file includes the training data for the sentiment analysis model. It contains the following columns:
1)tweet_text - the text of the tweet.
2)emotion_in_tweet_is_directed_at - an indication of where the emotion in the tweet is directed.
3)is_there_an_emotion_directed_at_a_brand_or_product - the presence of an emotion directed at a brand or product.

## Contributing
Contributions to this project are welcomed.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments
- Dataset provided by https://www.kaggle.com/
