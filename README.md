# Classifications
It was created to obtain the certification of Machine Learning with Python from Coursera(IBM)

## Methods
  - KNN 

## Results
| Algorithm          | Jaccard | F1-score | LogLoss |
|--------------------|---------|----------|---------|
| KNN                | 0.79    | 0.78     | NA      |
| Decision Tree      | 0.79    | 0.78     | NA      |
| SVM                | 0.77    | 0.76     | NA      |
| LogisticRegression | 0.7428  | 0.7199   | 0.56    |

Overfitting happens when a model learns the detail and noise in the training data to the extent that it negatively impacts the performance of the model on new data. This means that the noise or random fluctuations in the training data is picked up and learned as concepts by the model. 

It seems the better method to classificate my data is KNN and Decision Tree.It is not overfitting because the data test and thee data train have similar accuracy.
