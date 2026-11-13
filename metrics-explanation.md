### Metrics Explanation

The following metrics are calculated separately for each label:

- **Accuracy:** The percentage of images where the model correctly predicted whether the label was present or absent.
- **Baseline:** The accuracy that would be achieved by always predicting that the label is absent.
- **Improvement (pp):** The difference between the model's accuracy and the baseline, measured in percentage points.
- **Balanced Accuracy:** The average of recall (percentage of images with the flaw correctly identified) and specificity (percentage of images without the flaw correctly identified).
It gives equal weight to correctly identifying images with the label and images without it, so uncommon flaws don't have as much of an effect on the results.
- **Precision:** Of the images predicted to have the label, the percentage that actually have it.
- **Recall:** Of the images that actually have the label, the percentage correctly identified by the model.
- **F1 Score:** The harmonic mean of precision and recall. Harmonic mean is a form of averaging that penalizes large differences between two numbers. They both need to be high for a good score.
It helps measure how well the model balances correctly identifying flaws with avoiding false positives.

The `OTH` (Other) label is excluded from the displayed results.
