Cardiovascular Disease Prediction using Machine Learning
--------------------------------------------------------

This project builds a machine learning model to predict the presence of cardiovascular (heart) disease using clinical patient data. The approach includes data preprocessing, visualization, correlation analysis, comparison of multiple ML algorithms, and final model selection based on performance.

Dataset
-------
The dataset contains medical attributes such as:
- Age
- Sex
- Chest pain type
- Resting blood pressure
- Cholesterol level
- Fasting blood sugar
- Resting ECG results
- Maximum heart rate
- Exercise-induced angina
- ST depression (oldpeak)
- Slope, CA, and Thal values
- Target "cardio" (1 = heart disease, 0 = healthy)

The "cardio" target column is the output label used for prediction.

Project Workflow
----------------
1. Load and inspect the dataset  
2. Handle missing values and preprocess data  
3. Visualize important relationships and distributions  
4. Generate a correlation heatmap  
5. Split data into training and testing sets  
6. Train multiple ML models:  
   - Logistic Regression  
   - KNN  
   - SVM  
   - Decision Tree  
   - Random Forest  
7. Compare performance of all models  
8. Select the best-performing model  
9. Analyze feature importance (if Random Forest selected)

Technologies Used
-----------------
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

Results
-------
The best model is selected based on accuracy and classification metrics.  
Random Forest often performs strongly due to its ensemble approach and robustness.

How to Run
----------
1. Open the project in Jupyter Notebook or Google Colab  
2. Upload the dataset (heart.csv)  
3. Run each cell step-by-step  
4. Visualizations and metrics will appear automatically  

File Structure
--------------
- cardio_train.csv  
- Minor_Cardio_Project.ipynb  
- README.txt  

Conclusion
----------
Machine learning provides powerful tools for identifying heart disease risk by analyzing medical patterns. This project demonstrates how multiple algorithms can be evaluated and refined to build an effective prediction model.

--------------------------------------------------------
Project by: **Manaswi Priya Maddu**
--------------------------------------------------------
