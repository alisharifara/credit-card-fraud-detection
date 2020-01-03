# Credit card fraud detection
This project is for credit card fraud detection based on a dataset which is available on Kaggle.com

The dataset heavily contains imbalanced data. In other words, there are two different classes: Fraud (1) and Non-Fraud (0) transactions. The percentage of Fraud transactions is 99.83 and 0.17 Non-Fraud Transactions.

If we create our classification model based on this data, most probably the model overfits or it will become biased.

One solution to solve this issue is Resampling whcih itself consists of "Under-sampling" and  "Over-Sampling"

In the first case, we need to find out the size of the smallest class and the other classes must match the same size. (Dataset will become smaller)

In the over-sampling, we need to recreate the smallest to have the same size as the class which has more values.


