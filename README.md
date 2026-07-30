# Credit-Card-Fraud-Detection-By-Machine-Learning-

We first downloaded the **Credit Card Fraud Detection** dataset (`creditcardfraud.zip`) from Kaggle, extracted it, and loaded the `creditcard.csv` file for analysis.

Next, we performed **data exploration** and found that fraudulent transactions represented only a very small portion of the dataset, indicating a significant **class imbalance** problem. Since the **Time** and **Amount** features were not scaled like the PCA-transformed **V** features, we applied **StandardScaler** to normalize them.

To address the class imbalance, we used **RandomUnderSampler** to create a balanced dataset with an equal number of fraudulent and non-fraudulent transactions.

The balanced dataset was then split into **training** and **testing** sets. We trained a **Logistic Regression** model to classify transactions as either fraudulent or legitimate.

To evaluate the model's performance, we used metrics such as **Accuracy, Precision, Recall, and F1-score**. The model demonstrated strong performance in detecting fraudulent transactions while maintaining reliable classification accuracy.

Finally, we created a new hypothetical transaction to test the trained model. The model successfully identified the transaction as **fraudulent**, demonstrating its ability to detect suspicious activities effectively.

Overall, this project showcases the complete workflow of building, training, evaluating, and deploying a **Machine Learning-based Credit Card Fraud Detection System** capable of identifying fraudulent financial transactions.
