# Heart-Disease-Analysis-Using-ML-models


INTRODUCTION

This report presents the outcomes of our project, which focuses on predicting the presence of heart disease in individuals and analyzing the mean blood pressure difference between patients with and without heart disease. We address two primary research questions:

Research Question 1:
Which classification method achieved the highest accuracy in predicting the presence of heart disease in individuals?

To answer this question, we evaluated the performance of four machine learning models: Logistic Regression, K-Nearest Neighbors (KNN), Random Forest Classification, and Decision Trees Classification. The accuracy scores and confusion matrices for these models are as follows:

Logistic Regression accuracy: 0.83

KNN accuracy: 0.83

Random Forest Classification accuracy: 0.99

Decision Trees Classification accuracy: 0.84


Research Question 2: Is there a significant difference in mean blood pressure between patients with and without heart disease?

To address this question, we conducted a t-test to compare the mean blood pressure between these two groups. The t-test results are as follows:

t-Statistic: -4.465215

p-value: 8.922492e-06

These results indicate a statistically significant difference in mean blood pressure, with patients without heart disease having slightly higher blood pressure on average. The calculated Cohen's d effect size was approximately -0.2800787, indicating a small effect size.

DISCUSSION

Research Question 1

Our analysis revealed that Random Forest Classification achieved the highest accuracy (0.99) in predicting the presence of heart disease, outperforming the other methods. This suggests that Random Forest Classification is a robust choice for this task.

Research Question 2

The t-test results provide strong evidence of a significant difference in mean blood pressure between patients with and without heart disease. Although statistically significant, the small effect size (Cohen's d = -0.2800787) suggests that the difference, while meaningful, is relatively small.

VISUALIZATION

We used a bar plot to present the mean and standard error for each group, visually emphasizing the difference in mean blood pressure between patients with and without heart disease. The absence of overlap in the error bars underscores the significant distinction.

CONCLUSION

In conclusion, our analysis indicates that Random Forest Classification is the most accurate method for predicting the presence of heart disease in individuals. Additionally, there is a statistically significant but relatively small difference in mean blood pressure between patients with and without heart disease. These findings have important implications for healthcare and may aid in early detection and management of heart disease.

RECOMMENDATIONS

Future research can explore other machine learning algorithms and additional features for heart disease prediction. Furthermore, investigating the clinical implications of the observed difference in blood pressure can provide valuable insights for medical practitioners.
