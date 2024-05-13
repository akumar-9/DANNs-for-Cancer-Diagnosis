# Project Title: Deep Artificial Neural Networks for Cancer Diagnosis

### Authors:

+ Akshay Kumar - akumar9@umbc.edu
+ Keerthi S Kopparaju - keerthk2@umbc.edu
+ Sina M Kaviri - sinam1@umbc.edu
+ Srikar Jarugula - jsrikar1@umbc.edu
## Abstract
Early detection of diseases such as breast cancer is crucial for effective treatment and improved patient outcomes. This project leverages the power of Deep Artificial Neural Networks (DANNs) alongside other machine learning techniques to address the challenge posed by imbalanced medical datasets in disease diagnosis.

## Introduction
The application of DANNs in healthcare, particularly for cancer diagnosis, shows promising avenues for enhancing the accuracy and speed of medical diagnostics. This project aims to develop a model capable of analyzing clinical data to predict cancer diagnoses efficiently.

## Dataset Description
The dataset comprises 698 patient records, divided into training (70%), validation (15%), and testing (15%) sets. Attributes include Age, BMI, Glucose, Insulin, and various other biomarkers relevant to cancer diagnosis.

## Methodology
### Data Cleaning and Preparation
Normalization and PCA for feature extraction.
### Models Used
+ Logistic Regression
+ Linear Discriminant Analysis (LDA)
+ Support Vector Machines (SVM)
+ Random Forest
+ Gradient Boosting
+ Deep Neural Networks
## How to Run
Clone the repository:
`git clone https://github.com/akumar-9/DANNs-for-Cancer-Diagnosis.git`

Install required libraries:
`pip install -r requirements.txt` 

Run the Jupyter Notebooks provided in the repository:
`jupyter notebook DANNs\ for\ Cancer\ Diagnosis.ipynb`
## Results
Models were evaluated based on accuracy, precision, recall, and F1 score. The Neural Network and Random Forest models demonstrated high effectiveness in handling the imbalanced dataset, achieving significant predictive accuracy.

## Discussion
Comparative analysis of various models indicated that deep learning and ensemble methods outperform traditional machine learning approaches in complex diagnostic tasks.

## Future Work
Future enhancements include integrating more diverse datasets, refining model parameters, and developing real-time diagnostic tools.

## Citations
1. E. Yavuz and C. Eyupoglu, “An effective approach for breast cancer diagnosis based on routine blood analysis features,” Medical & Biological Engineering & Computing, vol. 58, pp.
1583–1601, 2020. DOI: https://doi.org/10.1007/s11517-020-02187-9.
2. A. Esteva, A. Robicquet, B. Ramsundar, and others, “A guide to deep learning in healthcare,” Nature Medicine, vol. 25, pp. 24–29, 2019. DOI: https://doi.org/10.1038/s41591-018-0316-z.
3. A. Rajkomar, E. Oren, K. Chen, and others, “Scalable and accurate deep learning with electronic health records,” npj Digital Medicine, vol. 1, p. 18, 2018. DOI: https://doi.org/10.1038/s41746-018-0029-1.
4. K. Kourou, T.P. Exarchos, K.P. Exarchos, M.V. Karamouzis, and D.I. Fotiadis, “Machine learning applications in cancer prognosis and prediction,” Computational and Structural Biotechnology Journal, vol. 13, pp. 8-17, 2014. DOI: https://doi.org/10.1016/j.csbj.2014.

### Contact Information 
For any queries, please reach out to the authors via the provided email addresses.