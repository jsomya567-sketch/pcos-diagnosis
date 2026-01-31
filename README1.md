PCOS Prediction and Analysis using Weka

Overview  
This project focuses on the analysis and prediction of Polycystic Ovary Syndrome (PCOS) using machine learning techniques in Weka Explorer. The dataset contains medical attributes such as Age, BMI, Menstrual Irregularity, Testosterone Level, and Antral Follicle Count, which are used to predict PCOS diagnosis.

The project demonstrates data preprocessing, attribute analysis, visualization, and classification using Weka’s built-in algorithms.


Dataset Description  
The dataset consists of 1000 instances with the following attributes:

- Age  
- BMI  
- Menstrual_Irregularity  
- Testosterone_Level (ng/dL)  
- Antral_Follicle_Count  
- PCOS_Diagnosis (Class Label)
All attributes are numeric and used for analysis and prediction.


Methodology  
1. Loaded the dataset into Weka Explorer using ARFF/CSV format.  
2. Performed preprocessing to check for missing values and analyze attribute distributions.  
3. Visualized attributes using Weka’s visualization tools.  
4. Applied classification algorithms such as:
   - J48 Decision Tree  
   - Random Forest  
   - Naive Bayes  
5. Evaluated model performance using percentage split or cross-validation.



Results and Performance  
- The classification model successfully predicted PCOS diagnosis based on medical attributes.  
- Random Forest provided the highest accuracy compared to other classifiers.  
- Important contributing features included BMI, Testosterone Level, and Antral Follicle Count.  

(Accuracy and evaluation metrics can be added here.)


Tools & Technologies  
- Weka Explorer  
- Machine Learning (Classification)  
- ARFF / CSV Dataset  
- Java-based Weka Framework  


How to Run the Project  
1. Install Weka Explorer  
2. Open Weka → Explorer  
3. Load the dataset file (`pcos_dataset.arff` or `pcos_dataset.csv`)  
4. Go to the Preprocess tab to analyze attributes  
5. Go to the Classify tab and select a classifier (e.g., Random Forest or J48)  
6. Run the model and view results  



## 📂 Project Structure  

