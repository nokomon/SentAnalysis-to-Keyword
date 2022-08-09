# SentAnalysis-to-Keyword

We tried a handful of DNN-based approaches for sentiment analysis of Korean texts. Attempted algorithms were: **CNN, RNN, LSTM, Bi-LSTM, GRU, CNN-LSTM. Tensorflow(Keras BE)** was used for modeling.  

Meanwhile during preprocessing, we wanted to check whether raw texts that were corrected, in terms of spacing and correcting spelling mistakes, were influential to the model's performances. We've reached the conclusion that such corrections were not significantly influential, and decided to not implement those approaches, as it took too much time for processing.

After comparing each model's performances, we concluded that a CNN-based approach was the best, and linked it to a **TextRank** algorithm to check which words triggered the model to properly/improperly classify a text as positive or negative.

I was responsible for modeling sentimental analysis models, and comparing their performances.  


### References
- Dataset: https://github.com/e9t/nsmc/
