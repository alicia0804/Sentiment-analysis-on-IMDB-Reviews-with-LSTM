This project "Sentiment analysis on IMDB Reviews" ties in my passion for Psychology and Computer Science and my desire to learn as I navigate towards different fields. 
I built this project by choosing the dataset "IMDB Dataset of 50k Movie Reviews" on Kaggle (which has 25,000 postivie and 25,000 negative reviews), cleaned the data, prepared text for the neural network and built the LSTM model.


These are my results: 
Final Training Accuracy : 97.8%
Validation Accuracy     : 86.9%
Test Accuracy           : **87.3%** 
Test Loss               : 0.430


This project taught me a lot overall and it was such an amazing experience to be able to combine my passions for different domains.
I learnt:
1) The importance of Data Preprocessing - the quality of data cleaning and text preprocessing removing stopwords, tokenization, and sequence padding) significantly impacts model performance.
2) Balancing Model Complexity and Overfitting - with an LSTM model, I saw how easily a model can overfit — my training accuracy was near perfect, but validation accuracy dropped. Regularization techniques (like dropout) and careful tuning of epochs were crucial
  to maintain generalization.
3) Understanding Sequential Models- I gained hands-on experience with how LSTM networks handle sequential dependencies and how word embeddings capture semantic meaning better than one-hot encodings.

4) Evaluation Beyond Accuracy - I realized accuracy isn’t always enough to judge a sentiment model. In future iterations, I plan to analyze precision, recall, F1-score, and confusion matrices to better understand model bias.
