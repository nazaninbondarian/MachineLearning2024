# MachineLearning2024 - HomeWork 3
Welcome to the official GitHub repository for the "Machine Learning" course for the Spring 1403 at **Khaje Nasir Toosi University of Technology (KNTU)**. This project builds upon the skills developed in the previous projects and explores advanced topics in machine learning, particularly in Support Vector Machines (SVM), and neural networks for fraud detection.

## Introduction
This repository includes the code, datasets, and reports for the second mini project. The project is divided into several sections, each focusing on different aspects of machine learning. Detailed instructions and requirements for each part are provided below.
### Important Dates
- **Project 3 Submission Deadline:** 18:00, Monday, June 20, 2024
### Project Requirements
1. **Report:** A comprehensive textual report is required, covering all aspects of the project. This includes explanations and results for each section.
2. **Code Submission:** All code must be uploaded to both the university portal and GitHub.
3. **Structured Presentation:** The report should follow a structured format, with clear explanations for each question and section.
4. **Google Colab Integration:** Ensure your Colab notebooks are set to Public access and include all necessary outputs and code cells.

**Links:**
- [Google Drive](https://drive.google.com/drive/folders/1jGEaYzkplmLxT9eO_XlBQrmlBCEkRECb)

## Project Tasks
### Question 1: SVM on Iris Dataset
1. **Dataset Exploration:** Load the Iris dataset and provide details such as mean, variance, number of samples, and dimensions. Perform dimensionality reduction (e.g., using t-SNE) and analyze whether it is useful for this dataset.
2. **SVM Implementation:** Use SVM with linear and kernel methods to classify the data. Visualize decision boundaries and confusion matrix. Explain the methods and reasons for choosing them.
3. **Kernel Comparison:** Experiment with different kernels (up to degree 10 for polynomial kernels) and compare the results. Create a GIF showing the decision boundaries for each kernel and degree.
4. **SVM from Scratch:** Implement the SVM algorithm without using pre-built libraries. Include methods for fitting, predicting, and using polynomial kernels. Compare the results with the scikit-learn implementation and provide a GIF of the decision boundaries.
### Question 2: Generalized Multiclass SVM
1. **Paper Study:** Summarize the paper "GenSVM: A Generalized Multiclass Support Vector Machine". Highlight the innovative ideas, problem statement, and proposed solutions.
2. **Implementation and Comparison:** Implement the methods discussed in the paper using available libraries and tools. Compare the results with those provided in the paper, using the Iris dataset.
### Question 3: Credit Card Fraud Detection Using Autoencoder Neural Networks
1. **Problem Analysis:** Identify the major challenges in developing models for fraud detection. Discuss the methods used in the paper to address these challenges.
2. **Network Architecture:** Provide a brief description of the network architecture used in the paper.
3. **Model Implementation:** Implement the autoencoder model, ensuring it is trained to avoid overfitting. Use validation error to restore the best model weights.
4. **Model Evaluation:** Evaluate the model using confusion matrix, precision, recall, accuracy, and F1 score. Discuss the suitability of these metrics for imbalanced datasets.
5. **Threshold Analysis:** Analyze the effect of different thresholds on model performance and plot Recall & Accuracy graphs similar to figure 7 in the paper.
6. **Model Comparison:** Compare the results of the model trained on noisy and imbalanced data with the model trained on cleaned data.

## Tools and Libraries
- **Python:** Ensure Python is installed.
- **Libraries:** `numpy`, `pandas`, `scikit-learn`, `matplotlib`, `seaborn`, `tensorflow`, `keras`
- **Google Colab:** For running and sharing notebooks.
- **GitHub:** For code versioning and sharing.

## Contribution Guidelines
1. **Fork the Repository:** Make a copy of this repository on your GitHub account.
2. **Clone the Repository:** Download your copy to your local machine.
3. **Create a New Branch:** Work on a separate branch for your changes.
4. **Commit and Push:** Save your changes and push them to your GitHub.
5. **Pull Request:** Submit a pull request to merge your changes into the main repository.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
- [scikit-learn Documentation](https://scikit-learn.org/stable/api/index.html)
- [Google Colab](https://colab.research.google.com/)
- [Generalized Multiclass SVM Paper](https://jmlr.org/papers/volume17/14-526/14-526.pdf)
- [Credit Card Fraud Detection](https://arxiv.org/pdf/1908.11553)

***
This README provides a comprehensive guide for anyone looking to understand, contribute to, or use the course projects. Ensure all links and information are up to date before finalizing the document.
