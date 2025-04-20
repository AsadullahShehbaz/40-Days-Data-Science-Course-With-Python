Sensitivity and specificity are important concepts in machine learning and medical testing.

# Sensitivity (True Positive Rate):

Refers to the proportion of actual positives that are correctly identified as such.
### Calculates the percentage of sick people who are correctly identified as having the condition.
> Sensitivity = TP / (TP + FN)
# Specificity (True Negative Rate):

Refers to the proportion of actual negatives that are correctly identified.
### Calculates the percentage of healthy people who are correctly identified as not having the condition.
> Specificity = TN / (TN + FP)
# The key differences between them:

> Sensitivity focuses on avoiding false negatives, while specificity focuses on avoiding false positives.

## High sensitivity means fewer sick people will be missed. But it may misclassify some healthy people as sick.

## High specificity means fewer healthy people will be misclassified. But some sick people may be missed.
# Trade-off:
There is usually a tradeoff – one cannot be increased without decreasing the other.
# Optimal Point : 
The optimal point depends on the application and cost of false positives vs false negatives.
# Conclusion:
So in summary, sensitivity measures model ability to correctly detect positives, while specificity measures ability to correctly detect negatives. Both are important metrics for classification tasks.