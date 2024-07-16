# MachineLearning2024 - HomeWork 1 - Question 2
## Fault Detection Dataset
1. **Dataset Familiarization:** Investigate the CWRU Bearing dataset, identifying various features and states.
2. **Data Preparation:** Download and preprocess the normal and faulty data, creating a labeled matrix.
3. **Feature Extraction:** Extract features using at least 8 methods listed in the project document. Form a new dataset.
4. **Data Shuffling:** Explain the importance of shuffling and split the data into training and evaluation sets.
5. **Data Normalization:** Normalize the data using at least two methods. Discuss the process and its importance.
6. **Model Training:** Train a classifier without using pre-built libraries. Evaluate the results and analyze the loss function.
### Introduction to the CWRU Bearing Dataset
The CWRU (Case Western Reserve University) Bearing dataset is widely used for bearing fault detection and diagnosis. The dataset includes various states of bearings such as normal and faulty conditions with defects like inner race, outer race, and ball faults. The data is collected at sampling rates of 12,000 samples/second and 48,000 samples/second .
### Steps to Access Data:
- Visit the [page](https://engineering.case.edu/bearingdatacenter/normal-baseline-data) for healthy data and download the normal class data (X_Normal) .
- Visit the [page](https://engineering.case.edu/bearingdatacenter/12k-drive-end-bearing-fault-data) for faulty data and download the faulty class data for condition k12 (X_007IR) .
