# Disease_Classifier_256

## **Description**
The "Disease_Classifier_256" project involves predicting class labels for 256 meticulously labeled testing experiments, presenting a challenge due to the dataset's extensive scale of 257 columns and 3264 records. Employing advanced machine learning techniques and classification algorithms, the project seeks to uncover intricate patterns through innovative feature engineering, algorithm selection, and model optimization. The project holds the potential to revolutionize disease diagnosis and classification by enhancing accuracy in assigning labels to test cases, thereby advancing medical decision-making and patient care. 

## **Project Code:**
Steps:
1. Define Problem
2. Installing needed Libraries
3. Data Collection
4. Exploratory Data Analysis (EDA)
6. Data Visualization
7. Data Pre-Processing
   - Feature Selection
   - Splitting data
   - Fixed Outlier
   - Standard Scaler
   - Dimension reduction-PCA
8. Moddeling
    - Random Forest
    - Stacking model (random forest, SVC, K-Neighbors, Logistic regerssion)
9. Measure accuracy of models
10. Conclusion

## **Installation**
1. Clone the repository: `git clone https://github.com/Lexuz17/Sentiment_Education_Analysis_Clustering.git`
2. Install the required dependencies: `pip install -r requirements.txt`

## **Results and Findings**

From the results of this project, several crucial findings have been identified that can provide significant benefits:
1. **EDA analysis** revealed no clear trends in the dataset. Column-label correlations appeared scattered with a mix of low and high correlations, both positive and negative.
2. **Outliers were evident**, significantly distanced from other values, possibly affecting model performance.
3. **The stacking model** slightly outperformed the random forest with over 70% accuracy, showing potential in disease classification.
4. The stacking model's success might **stem from overfitting**, evident in both models achieving 100% accuracy on training data, warranting caution with new data.
5. **Further analysis** is crucial to determine if techniques like feature selection, dimension reduction, or outlier handling can improve model performance. Balancing accuracy and overfitting risk needs attention.

In conclusion, these findings shed light on the dataset's characteristics, model performance, and challenges encountered in the attempt to classify diseases based on the existing experiments.

## Contact
For any questions or inquiries, please contact jason.susanto1703@gmail.com
