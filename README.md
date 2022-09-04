# Feature-Based-Machine-Translation-Evaluation

--Here we had been provided with a translated text dataset Consisting of Hindi Sentences and their corresponding English Translated Sentences along with thier gold standard english translation(By Human)

--We had to evaluate the quality of translation based on features like lexical features, semantic features, morphological features.

--We are first calculating F1 Score for each individual sentences for each individua; features and calculating their mean F1 score to feed it as a feature in our machine learning models.

We tried our regression model with SVR, Decision tree, Random forest regressor,Ada Boost, XgBoost ensemble learning models, then we go forward to LSTM, BiLSTM, Deep ANN. We got best performance from Ada Boost and LSTM model with fast text embedding of sentences. We measure the evaluated score of the model with our own given score to test sentences with the help of Pearson correlation coefficient.

#Tools and Technologies used
--Python Version - 3.9
● TensorFlow Version - 2.9
● Pip Version - 22.1.2
● PyTorch Version - 21.02
● GPU - Nvidia K80/T4
● GPU Memory - 12 GB
● Platform - Google Colab, Kaggle
● Embedding - FastText Embedding
● Evaluation Metric (Gold Standard) - COMET

-- for further understanding of project please refer project report and code
