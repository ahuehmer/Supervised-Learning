# Supervised-Learning

This model is trained on a dataset of lending activity to be able to identify the creditworhtiness of a borrower, which can help banks determine if they want to lend money to a certain customer. The model trained on oversampled data offers promising insights into whether a loan is a high-risk loan. 

---

- The accuracy of the model is at 99%, meaning that the model is making correct predictions 99% of the time. 
- The precision score for healthy loans is at 100%, which is perfect! The precision score for predicting high-risk loans is at 84%, meaning that 84% of predicted high-risk loans are actually high-risk, while the rest is actually healthy. 
- The recall score for both healthy and high-risk loans is at 99%, meaning that 99% of high-risk loans are correctly identified and 99% of all healthy loans are also identified correctly. 

---

This model minimizes false negatives, which is good, since predicting a high-risk loan as healthy is less chaotic than vice versa. However, it is still not ideal. Therefore, I would only recommend this model to predict high-risk loans but not for identifying healthy loans.