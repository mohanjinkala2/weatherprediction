# weatherprediction Using DecisionTree
# Introduction:
Weather type classification is an important task in the field of environmental data analysis, with applications in meteorology, agriculture, transportation, 
and disaster management. Traditionally, weather forecasting has relied on complex physical models and manual observations. However, with the increasing 
availability of large-scale weather datasets, machine learning has emerged as a powerful approach for automating the classification of weather conditions.

Machine learning models can learn patterns and relationships from historical weather data—such as temperature, humidity, wind speed, and atmospheric pressure—to classify current or future weather into categories like sunny, rainy, cloudy, snowy, etc. This approach not only enhances accuracy but also allows for faster and more scalable solutions compared to traditional methods.

 In this project, we explore the use of supervised machine learning techniques to build a weather type classification model. By training the model on labeled weather data, the goal is to predict the correct weather category for a given set of atmospheric features. This work demonstrates the potential of data-driven approaches in supporting more efficient and intelligent weather prediction systems.
# **Process:**

**Data Preprocessing:**
*   **Loading Data:** The dataset is loaded and initial exploration is conducted to understand its structure.
*   **Handling Missing Values:** We check for any missing values and handle them appropriately to ensure data quality.
*   **Encoding Categorical Variables:** Categorical variables such as 'Location' and 'Season' are encoded to numerical values for model compatibility.
*   **Feature Scaling:** Continuous variables are standardized to improve model performance.
*   **Outlier Detection and Handling Using IQR Method**:Removing outliers if present to improve model performence.
# **Models Used:**
   * Various models are used here to find Best One Out ,This Models are 1)**LogisticRegression-Multinomial**,2)**Navie_Bayes-GaussianNB**
    ,3)**KNN-KNeighborsClassifier**,4)**SVM-Classifier**,5)**DecisionTree-Classifier**.
# **Final Results:**
   * Out Of This Five Models **DecisionTree-Classifier** Performed Best With **Accuracy: 97.3766752209866** At Max_depth=6 and Critiria=Entropy
   * **f1_score: 97.38656506695207**
   * **precision_score: 97.40733074064329**
   * **recall_score: 97.3766752209866**
# **Conclusion:**
* This project demonstrated the potential of using a Decision Tree Classifier for real-world weather type classification. By analyzing key weather features—such as temperature, humidity, and wind speed—the model was able to accurately categorize weather conditions into distinct types like sunny, rainy, or cloudy.

* In real-world applications, such a system can be highly valuable. Accurate and automated weather classification can support better decision-making in sectors like agriculture, aviation, transportation, and event planning. For example, farmers can use weather insights to plan irrigation and harvesting Which improves Production, while logistics companies can optimize delivery routes based on predicted weather conditions which saves Money.
