## Sentiment Analysis "Honor Of Kings" Reviews from Google Play Store

**Overview**

This project explores sentiment analysis to understand user reviews and opinions on famous game "Honor Of Kings" on the Google Play Store. By automatically identifying whether reviews are positive, negative, or neutral, this project can provide valuable insights for app developers to improve user experience and make better decisions.

**Data**

The project focuses on analyzing user reviews for the "Honor of Kings" app. Text processing techniques are applied to clean the data, including:

* Removing mentions, hashtags, URLs, numbers, and punctuation.
* Converting text to lowercase.
* Tokenizing text (splitting into words).
* Removing stopwords (common words like "the" and "a").
* Stemming words (reducing words to their root form).

**Model**

A Long Short-Term Memory (LSTM) neural network model is used to classify sentiment. Here's a simplified view of the model architecture:

1. **Embedding Layer:** Converts text tokens into numerical vectors.
2. **LSTM Layer:** Captures sequential information in the text.
3. **Batch Normalization:** Improves model stability and training speed.
4. **Dropout Layers:** Reduce overfitting.
5. **Dense Layers:** Process information from the LSTM layer.
6. **Global Average Pooling:** Summarizes the output from the previous layer.
7. **Output Layer:** Uses softmax activation for multi-class classification (positive, negative, neutral).

**Conclusion**

By leveraging sentiment analysis techniques, this project provides a framework to analyze user reviews and gain insights into user perception. This information can be crucial for improving apps and user experience.

**Next Steps**

* Train and evaluate the LSTM model on the cleaned dataset.
* Analyze the sentiment distribution of user reviews.
* Visualize the results to understand user opinions in more detail.
* Explore additional techniques like TF-IDF for feature extraction.

