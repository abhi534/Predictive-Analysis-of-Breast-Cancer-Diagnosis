**Breast Cancer Classification Project**

This project aims to classify breast cancer tumours as benign or malignant using machine learning techniques. The Breast Cancer Wisconsin dataset, containing features computed from digitized images of fine needle aspirates of breast masses, is utilized for analysis and modelling.

**Dataset Overview:**
- The dataset consists of 569 instances and 30 features, including mean radius, mean texture, mean perimeter, mean area, and more.
- The target variable is binary, with 0 representing benign tumours and 1 representing malignant tumours.

**Project Components:**
1. **Data Analysis and Exploration:** Basic information about the dataset, summary statistics, and visualizations are generated to understand the data distribution and feature correlations.
2. **Feature Selection:** Important features are selected based on their correlation with the target variable to enhance model performance.
3. **Data Preprocessing:** The dataset is split into features and the target variable, and further divided into training and testing sets.
4. **Model Building:** A Random Forest Classifier is trained on the training data to predict tumour classification.
5. **Model Evaluation:** The trained model is evaluated using an accuracy score, classification report, and confusion matrix.

**Challenges Faced and Solutions:**
- **Imbalanced Data:** Techniques such as oversampling, undersampling, and appropriate evaluation metrics are employed to address data imbalance.
- **Feature Selection:** Correlation analysis and domain knowledge are utilized to select informative features from a large set.
- **Model Tuning:** Grid search and random search for hyperparameter tuning are applied to optimize model performance.

**Conclusion and Future Scope:**
The project successfully classifies breast cancer tumours with high accuracy, providing insights for future research and improvement. Future work could involve further fine-tuning of model parameters, exploration of alternative classification algorithms, and incorporation of additional features for enhanced performance.

**Dependencies:**
- Python 3
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

**Usage:**
1. Open the Jupyter notebook file: [Breast Cancer Diagnosis.ipynb](https://github.com/abhi534/Predictive-Analysis-of-Breast-Cancer-Diagnosis/blob/main/Breast%20Cancer%20Diagnosis.ipynb)

**Contributing:**
Contributions are welcome! Feel free to open issues or pull requests for any suggestions or improvements.
