# MachineLearning2024 - HomeWork 2 - Question 2
## Fault Detection with Extended Dataset
1. **Dataset Extension:** Extend the previous mini project dataset by adding two more classes from the CWRU Bearing dataset. Analyze and provide a brief explanation of the faults related to each class.
2. **Feature Extraction and Data Preparation:** Implement the previous steps of data preparation and feature extraction on the new dataset. Add a validation set alongside training and test sets.
3. **MLP Model Training:** Train a simple Multi-Layer Perceptron (MLP) with two hidden layers. Evaluate the model using appropriate metrics and visualize the results.
4. **Optimizer and Loss Function Comparison:** Compare the results using different optimizers and loss functions. Analyze the impact of these changes on the model's performance.
### Introduction to the CWRU Bearing Dataset
The CWRU (Case Western Reserve University) Bearing dataset is widely used for bearing fault detection and diagnosis. The dataset includes various states of bearings such as normal and faulty conditions with defects like inner race, outer race, and ball faults. The data is collected at sampling rates of 12,000 samples/second and 48,000 samples/second .
### Steps to Access Data:
- Visit the [page](https://engineering.case.edu/bearingdatacenter/normal-baseline-data) for healthy data and download the normal class data (X_Normal) .
- Visit the [page](https://engineering.case.edu/bearingdatacenter/12k-drive-end-bearing-fault-data) for faulty data and download the faulty class data for condition k12 (X_007IR) .
