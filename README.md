# Product Categorization

## Multi-Class Text Classification of bugs based on their description

General info

RCCA of customer reported bugs often takes longer period of time if the number of bugs are high.
It would be time taking to understand the cause of a feature specific issues (such as memory_leaks, config, interoperability, etc) repeatedly seen in customer environment.
It needs a lot of efforts and time to understand the series of events that trigger the problem as reported in the bug.


## ML Approach
The aim of the project is multi-class text classification of PR based on their description and categories.
Based on given text as an input, we have predicted what would be the category. 
We have 6 types of categories as configuration, generic, rekey, memory,Ipsec_routing and NATT
We used different machine learning algorithms to get more accurate predictions and choose the most accurate one for our issue. 
The following classification algorithms have been used: Logistic Regression, Multinomial Naive Bayes, Linear Support Vector Machine (LinearSVM), Random Forest and Gradient Boosting as well.
For analysis we used python and their libraries: pandas, matplotlib, NLTK and scikit-learn.

## Dataset
The dataset is extracted usig internal tool whcih has confidential information and hence could not be shared.
The dataset structures in csv format with the real descriptions/synopsis/notes/fix/root-casue all collected under a cell as a input corpus.
For test we had 120+ bugs categorized manually into 6 categories, hence we will be applying supervised learning techniques. 


## Sample Distribution:

1. configuration    29
2. generic          25
3. rekey            14
4. memory_issue      8
5. IPsec_routing     5
6. NATT              5

## Summary

![image](https://user-images.githubusercontent.com/8717020/204483016-d218f5ab-2b09-4f6a-8564-25383e84da67.png)


