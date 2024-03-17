# MGTA415 24 Spring Final Project
## Do deep learning models always achieve higher accuracy in multi-class prediction, comparing to traditional machine learning models?

In this study, we tried to explore whether deep learning models always performs better than traditional machine learning algorithms, including tf-idf and Word2Vec.

With **deep learning** models, we combined embedding with classification task into one neural network. For **machine learning** algorithms, we built classification models (e.g. logistic regression and random forest) trained by embedded vectors using tf-idf or Word2Vec.

The dataset is used in Kaggle Competition.

- For LSTM model, see the file ```dl.ipynb```
- For NN model, BERT and tf-idf, see ```traditional.ipynb```
- For Word2Vec model, see ```w2v.ipynb```

### Result

| Model | Type  | Test set accuracy | 
| ---------- |------| ------------ | 
| Word2Vec + Logistic Regression | Traditional | 77% |
| tf-idf + Logistic Regression  | Traditional | 76.49%    |
| BERT + NN + Logistic  | Deep learning | 74.02%    | 
| LSTM + Softmax | Deep Learning | 72.00% |
