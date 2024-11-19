# Predicting-Movie-Success-Based-on-Sentiment-Analysis-

  ## Final Project for CMPSC 446 - Data Mining
  
## Findings and Insights

### Model Performance Overview

#### Classification Metrics:

##### Accuracy: Overall model accuracy is 87%.

##### Precision/Recall: Balanced metrics for both classes, with F1-scores of 0.86 (class 0) and 0.87 (class 1), indicating good performance.

#### Training Results:

Training accuracy reached 95.13%, showing strong learning capacity.
Validation accuracy plateaued at ~87.81% after epoch 2, signaling overfitting.
Loss:
Training loss decreased consistently, from 0.46 to 0.13.
Validation loss increased after epoch 2, further highlighting overfitting.
Graphs
Model Loss (First Graph):
Training loss steadily decreases as the model learns the data.
Validation loss increases after epoch 2, showing the model struggles to generalize.
Model Accuracy (Second Graph):
Training accuracy increases with each epoch, reaching ~95%.
Validation accuracy plateaus at ~87%, diverging from training accuracy, confirming overfitting.
Conclusion
The model performs well on the training data but shows limited generalization to the validation set due to overfitting.
Next Steps:
Implement regularization (Dropout, L2) or early stopping (after epoch 2) to mitigate overfitting.
Consider hyperparameter tuning and expanding the dataset for better validation performance.
Validate results using additional metrics like AUC-ROC for robustness.
