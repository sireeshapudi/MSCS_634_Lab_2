# MSCS 634 Lab 2: Classification Using KNN and Radius Neighbors Algorithms

## Purpose

The purpose of this lab is to explore supervised classification techniques using the Wine dataset from sklearn. Two classification algorithms, K-Nearest Neighbors (KNN) and Radius Neighbors (RNN), were implemented and evaluated using multiple parameter values.

## Dataset

The Wine dataset contains chemical measurements from three different wine classes. The objective is to classify wine samples into their correct categories based on their chemical properties.

## Activities Performed

- Loaded and explored the Wine dataset
- Reviewed dataset structure and class distribution
- Split the dataset into training and testing sets
- Implemented KNN using multiple k values
- Implemented Radius Neighbors using multiple radius values
- Evaluated classification accuracy
- Visualized accuracy trends
- Compared classifier performance

## Key Findings

- Model performance changed noticeably as parameter values were adjusted.
- Certain k values produced better KNN accuracy than others.
- Radius selection directly affected RNN performance.
- Both classifiers successfully classified wine samples with high accuracy.
- Parameter tuning is essential for achieving optimal classification results.

## Challenges

One challenge was selecting parameter values that balanced model flexibility and stability. Another challenge was understanding how different neighborhood definitions affect classification behavior.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook