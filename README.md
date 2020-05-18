# Disease Diagnosis Model
A prediction model to determine if an individual is suffering from the disease.

## Dataset
The dataset consists of two parts - labeled and unlabeled data. The labeled dataset or the training dataset has 49,000 rows and includes 12 attributes such as age, height, weight, blood pressure, cholesterol, glucose, etc. This dataset will be used to classify records in the testing dataset which consists of 21,000 instances.

## Approach
- Exploratory data analysis
- Data preprocessing (deduplication, handling missing values, dirty data and outliers; one-hot encoding)
- Classification using logistic regression
- Classification using a artificial neural network with 0 hidden layers
- Classification using a artificial neural network with 1 hidden layer
- Classification using a artificial neural network with 2 hidden layers
- Classification using decision tree classifier

## Results
Algorithm | Accuracy | Area under the curve
--- | --- | ---
**Logistic regression** | 73.21% | 0.792
**ANN0** | 73.29% | -
**ANN1** | 73.45% | -
**ANN2** | 73.46% | -
**Decision tree** | 73.31% | 0.73
