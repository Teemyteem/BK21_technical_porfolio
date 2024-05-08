# Stroke project
- Objective:
	- To predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status.  
- Data:   
	- 11 attributes, 1 stroke class, 5110 records  
	- Numerical variable (4): id, age, avg_glucose_level, bmi  
	- Categorical variable (7): gender, hypertension, heart_disease, ever_married, work_type, Residence_type, smoking_status  
	- Stroke class: 0 = No stroke, 1 = Stroke
 	- Data file: [stroke_data.csv](https://github.com/Teemyteem/BK21_technical_porfolio/blob/main/%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EC%8B%AC%EA%B0%81%ED%99%94/stroke_data.csv)	 	
  <img width="684" alt="image" src="https://github.com/Teemyteem/BK21_technical_porfolio/assets/129394136/fc64df28-1215-41c8-9265-bc9bc7798dc1">  
- Preprocessing:	
  - Remove 'ID' column	
  - Replace 'bmi' column with mean value = 28.9	
  - Remove 'Other' value in column 'gender'	
  - Remove 'Unknown' value in column 'smoking_status'	
  - Convert categorical variable to numerical variable (column: 'ever_married', 'Residence_type', 'gender', 'work_type', 'smoking_status')	
- EDA (Exploratory Data Analysis)	
  ## Data visualization: histogram, box plot, kde plot, bar plot, and scatter plot.
  - Using python's matplotlib to visual the data		
  - Histogram:
  	- shows the frequency of each features (column: gender, age, hypertension, heart_disease, ever_married, work_type, Residence_type, avg_glucose_level, bmi, smoking_status, stroke)			
    <img width="584" alt="image" src="https://github.com/Teemyteem/BK21_technical_porfolio/assets/129394136/0e295bcb-d67d-4373-9863-ed9f1a5c5b9d">
    <img width="584" alt="image" src="https://github.com/Teemyteem/BK21_technical_porfolio/assets/129394136/ea6d3db0-f50f-4c5c-ba31-937fa8988261">
    
  - Box plot:
  	- shows min, Q1, median, Q3, max, and outlier of numerical variables (column: age, avg_glucose_level, bmi)			
    <img width="572" alt="image" src="https://github.com/Teemyteem/BK21_technical_porfolio/assets/129394136/76345ab4-53b8-4c37-83e8-08f7cdd28517">

  - kde plot:
  	- show the distribution of variable using a smooth curve (column: age, avg_glucose_level, bmi)		
    <img width="626" alt="image" src="https://github.com/Teemyteem/BK21_technical_porfolio/assets/129394136/5b320a53-9b63-4075-8277-1cf7cbb7e65b">

  - Bar plot:
  	- show the frequency or count of each category in the categorical variable (column: gender, age, hypertension, ever_married, work_type, Residence_type, smoking_status)		
    <img width="506" alt="image" src="https://github.com/Teemyteem/BK21_technical_porfolio/assets/129394136/e7e00c0a-e019-40cb-80a5-3881140df9dd">
    <img width="695" alt="image" src="https://github.com/Teemyteem/BK21_technical_porfolio/assets/129394136/582bce4c-656a-40d5-8c77-38550211fe1a">

  - Scatter plot:
  	- show relationship between two numerical variables (column: age, avg_glucose_level, bmi)		
    <img width="699" alt="image" src="https://github.com/Teemyteem/BK21_technical_porfolio/assets/129394136/b737b2ba-09a8-47f7-a8d6-34e50c065b82">

- Model:
	- Decision Tree, Color Decision Tree, Logistic Regression, Random Forest, Gradient Boosting, Naive Bayes, K-NN  
- Result:   
	- Decision tree: accuracy = 0.917  
	- Logistic regression: accuracy = 0.929  
	- Random Forest: accuracy = 0.928  
	- Gradient Boosting: accuracy = 0.929  
	- Naive Bayes: accuracy = 0.872  
	- K-NN: accuracy = 0.928  
- Link: [Code](https://github.com/Teemyteem/BK21_technical_porfolio/blob/main/%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EC%8B%AC%EA%B0%81%ED%99%94/22512087_Stroke.ipynb) [PPT slide](https://github.com/Teemyteem/BK21_technical_porfolio/blob/main/%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EC%8B%AC%EA%B0%81%ED%99%94/22512087_Stroke.pdf) 
