# Disease Diagnosis Model
A prediction model to determine if an individual is suffering from a disease.

## Dataset
The dataset contains information and symptoms about 70,000 patients collected from different hospitals. Each patient has 11 attributes including age, height, weight, blood pressure, cholesterol, glucose, etc. The data for 49,000 of these patients is labeled, and is used to classify the remaining 21,000 unlabeled instances.

## Approach
- Exploratory data analysis
- Data preprocessing (deduplication, handling missing values, dirty data and outliers; one-hot encoding)
- Classification using logistic regression
- Classification using a artificial neural network with 0, 1 and 2 hidden layers
- Classification using a decision tree classifier

## Results
Algorithm | Accuracy | Area under the curve
--- | --- | ---
**Logistic regression** | 73.21% | 0.792
**ANN0** | 73.29% | -
**ANN1** | 73.45% | -
**ANN2** | 73.46% | -
**Decision tree** | 73.31% | 0.73
