## 1. 데이터 활용 및 분석 (Melting tank)  
- Objective: To develop melting quality prediction modeling.  
- Background:  
	- Since the quality of the melting process has a large impact on the quality of the post-process and finished product, it is important to predict the quality well.  
	- Multiple raw materials are put in at the same time, and people cannot check whether the quality is good or not. Therefore, a quality prediction model is required to reduce cost and time.  
- Data:  
	- Independent variable (MELT_TEMP, MOTORSPEED, MELT_WEIGHT, INSP)  
	- Dependent variable (TAG)  
  
- Model: Classification decision tree, Logistic regression, Support Vector Machine, XGBoost classification, Random Forest Classification  
- Result:   
	- Decision tree: accuracy = 0.7256  
	- Logistic regression: accuracy = 0.7229  
	- Support Vector Machine: accuracy = 0.7827  
	- XGBoost: accuracy = 0.6679  
	- Random Forest: accuracy = 0.7827  
- Link: [PPT slide]()  
  
## 2. Stock Price Prediction by Using Long Short-Term Memory Model With Multiple Look Back Periods  
- Objective: Proposed a developed closing price prediction model by using three stocks from the Thai SET50 index (CPALL, AOT, LH).  
- Background:   
	- The stock market has long been a favorite among investors.  
	- To increase their profits, many investors would like to be able to anticipate stock prices, but this is challenging given the uncertain movement of stock prices.  
- Data:   
	- Collecting 2 date range data from the yfinance library  
	- CPALL stock (CP ALL PUBLIC COMPANY LIMITED)   
	- AOT stock (AIRPORTS OF THAILAND PUBLIC COMPANY LIMITED)  
	- LH stock (LAND AND HOUSES PUBLIC COMPANY LIMITED)  
  
- Model: CNN, LSTM  
- Result:   
	- In general, the results showed that LSTM outperformed CNN with high-performance  
- Link: [PPT slide]()  
