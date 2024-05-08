# Stroke
- Objective: To predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status.  
- Data:   
	- 11 attributes, 1 stroke class, 5110 records  
	- Numerical variable (4): id, age, avg_glucose_level, bmi  
	- Categorical variable (7): gender, hypertension, heart_disease, ever_married, work_type, Residence_type, smoking_status  
	- Stroke class: 0 = No stroke, 1 = Stroke
 	- [stroke_data.csv](https://github.com/Teemyteem/BK21_technical_porfolio/blob/main/%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EC%8B%AC%EA%B0%81%ED%99%94/stroke_data.csv) 	
  <img width="684" alt="image" src="https://github.com/Teemyteem/BK21_technical_porfolio/assets/129394136/fc64df28-1215-41c8-9265-bc9bc7798dc1">  
- Preprocessing:	
  - Remove 'ID' column	
  - Replace 'bmi' column with mean value = 28.9	
  - Remove 'Other' value in column 'gender'	
  - Remove 'Unknown' value in column 'smoking_status'	
  - Convert categorical variable to numerical variable (column: 'ever_married', 'Residence_type', 'gender', 'work_type', 'smoking_status')	
- EDA (Exploratory Data Analysis)	
  - ## Data visualization: histogram, box plot, kde plot, bar plot, and scatter plot.		
  - Histogram: showing the frequency of each variables (age, )		
    <img width="634" alt="image" src="https://github.com/Teemyteem/BK21_technical_porfolio/assets/129394136/496be019-500c-4f51-8d7a-403d9ff0830f">
	
  - Box plot:
  - kde plot:
  - Bar plot:
  - Scatter plot:
- Model: Decision Tree, Color Decision Tree, Logistic Regression, Random Forest, Gradient Boosting, Naive Bayes, K-NN  
- Result:   
	- Decision tree: accuracy = 0.917  
	- Logistic regression: accuracy = 0.929  
	- Random Forest: accuracy = 0.928  
	- Gradient Boosting: accuracy = 0.929  
	- Naive Bayes: accuracy = 0.872  
	- K-NN: accuracy = 0.928  
- Link: [Code](https://github.com/Teemyteem/BK21_technical_porfolio/blob/main/%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EC%8B%AC%EA%B0%81%ED%99%94/22512087_Stroke.ipynb) [PPT slide](https://github.com/Teemyteem/BK21_technical_porfolio/blob/main/%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EC%8B%AC%EA%B0%81%ED%99%94/22512087_Stroke.pdf) 
