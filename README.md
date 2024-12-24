# **Products Recommendation Project**

## **Project Overview**
This project showcases my ability to handle real-world data problems using advanced machine learning and analytics techniques. The focus is on predicting product ownership changes for bank clients based on their historical financial and demographic data. The project includes data preprocessing, feature engineering, advanced analytics, and machine learning modeling.

## **Dataset Description**
The dataset consists of **12,000 bank clients** with their monthly financial status and demographic information. The data is structured in a tabular format, with each row representing a client.  
- **Client Features**: The first 24 columns capture client-specific details such as age, country of residence, and the joining channel.  
- **Product Features**: The last 24 columns indicate the products owned by the client during a specified month (`Status_Dt`).  

The objective is to forecast which products a client will add or remove in the following month based on their historical data.

## **Key Components**
### **1. Data Preprocessing**
- Imported and cleaned the dataset using pandas.
- Handled missing values with imputation techniques.

### **2. Feature Engineering**
- Created new features to capture trends in product ownership over time.
- Encoded categorical variables using label encoding and one-hot encoding where appropriate.
- Generated interaction features to identify relationships between client attributes and products.

### **3. Exploratory Data Analysis (EDA)**
- Performed statistical analysis to understand feature distributions and relationships.
- Visualized data trends using histograms, box plots, and scatter plots.
- Identified key patterns in product ownership changes across different client segments.

### **4. Advanced Machine Learning**
- Built and evaluated a **Random Forest model** to address a **multi-output classification problem**, where clients could change more than one product in a given month.
- Trained the model on the `train_features` and `train_labels` datasets, and tested it on the `test_labels` dataset.
- Utilized metrics such as **confusion matrix** and **classification report** to evaluate model performance for each output.
- Employed efficient computation with multi-threading support using `n_jobs=-1` to handle the complexity of multi-output predictions.

### **5. Advanced Analytics**
- Conducted time-series analysis to forecast product ownership trends.
- Used SHAP (SHapley Additive exPlanations) for model interpretability, identifying the most influential features in predictions.
- Performed scenario analysis to explore how changes in client demographics impact product recommendations.

## **Skills Demonstrated**
- Data Cleaning and Preprocessing
- Feature Engineering and Selection
- Advanced Machine Learning Modeling
- Model Interpretability and Explainability
- Data Visualization and Insight Extraction

## **Libraries and Tools Used**
- Python (version 3.x)
- **pandas** and **NumPy** for data manipulation and preprocessing.
- **Matplotlib** and **Seaborn** for data visualization.
- **scikit-learn** for machine learning models and evaluation.
- **SelectFromModel** for feature importance and model interpretability.

## **Conclusion**
This project highlights my expertise in end-to-end machine learning pipelines, from data preprocessing to advanced analytics and modeling. It demonstrates my ability to tackle complex, real-world problems and derive actionable insights using advanced techniques.