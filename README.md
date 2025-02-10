Twitter Sentiment Analysis
This project performs sentiment analysis on a dataset of tweets to classify them as positive or negative. 
The dataset is sourced from Kaggle, and the analysis involves preprocessing the text using Porter Stemmer, vectorizing the text using TF-IDF, and training a machine learning model to predict sentiment.

Steps Overview
1. Dataset:
  * The dataset is downloaded from Kaggle using the kagglehub library.
  * It contains tweets labeled as positive or negative.

2. Preprocessing:
  * Porter Stemmer is used to stem words (e.g., "running" → "run").
  * Stopwords are removed to focus on meaningful words.
  * The tqdm library is used to track progress during preprocessing.

3. Vectorization:
  * The preprocessed text is converted into numerical features using TF-IDF Vectorization.

4. Model Training:
  * A machine learning model (e.g., Logistic Regression, Random Forest) is trained on the vectorized data.
  * The model achieves an accuracy of 77.6%.

5. Sentiment Prediction:
  * The model predicts whether a tweet is positive or negative.
