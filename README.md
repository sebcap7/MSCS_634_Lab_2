# # MSCS 634 - Lab 2
## K-Nearest Neighbors (KNN) and Radius Neighbors (RNN) Classification

### Purpose

The purpose of this lab was to explore and compare the performance of K-Nearest Neighbors (KNN) and Radius Neighbors (RNN) classifiers using the Wine Dataset from the sklearn library. The lab focused on understanding how different parameter values affect classification accuracy and how those changes impact model performance.

### Files Included

- MSCS_634_Lab_2.ipynb
- README.md

### KNN Results

| K Value | Accuracy |
|----------|----------|
| 1 | 0.7778 |
| 5 | 0.7222 |
| 11 | 0.7500 |
| 15 | 0.7500 |
| 21 | 0.7778 |

### RNN Results

| Radius | Accuracy |
|----------|----------|
| 350 | 0.7500 |
| 400 | 0.7222 |
| 450 | 0.7222 |
| 500 | 0.7222 |
| 550 | 0.7222 |
| 600 | 0.7222 |

### Key Insights and Observations

The KNN model achieved the highest accuracy of 0.7778 when using k values of 1 and 21. The lowest KNN accuracy was 0.7222 at k = 5. Overall, the KNN model showed relatively stable performance across the tested values.

The RNN model achieved its best accuracy of 0.7500 with a radius value of 350. All larger radius values produced an accuracy of 0.7222. This indicates that increasing the radius did not improve performance for this dataset.

Based on the results, KNN performed slightly better than RNN because it achieved the highest overall accuracy. The results suggest that KNN is a stronger choice for classifying observations in the Wine Dataset.

### Challenges and Decisions

One challenge during the lab was selecting and testing multiple parameter values for both models to compare their performance. Another issue encountered was ensuring all required libraries were properly imported before running the notebook cells.

A decision made during the lab was to use the parameter values provided in the instructions for both KNN and RNN. The performance of each model was then evaluated using accuracy scores and visualized using line plots.

### Conclusion

This lab demonstrated how parameter selection can affect classification performance. While both models were able to classify the wine data, KNN produced slightly better results than RNN on the test dataset. The exercise provided practical experience with model evaluation, parameter tuning, and performance comparison.
