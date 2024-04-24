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
- Link: [PPT slide](https://github.com/Teemyteem/BK21_technical_porfolio/blob/main/%EB%8D%B0%EC%9D%B4%ED%84%B0%20%ED%99%9C%EC%9A%A9%20%EB%B0%8F%20%EB%B6%84%EC%84%9D/2022-2%20%EC%A0%84%EC%9E%90%EC%A0%9C%EC%A1%B0%EB%8D%B0%EC%9D%B4%ED%84%B0%EB%B6%84%EC%84%9D/%EC%9A%A9%ED%95%B4%ED%83%B1%ED%81%AC%20%EC%A0%9C%EC%A1%B0%20%EB%8D%B0%EC%9D%B4%ED%84%B0%EB%A5%BC%20%EC%9D%B4%EC%9A%A9%ED%95%9C%20%ED%92%88%EC%A7%88%20%EC%9D%B4%EC%83%81%20%ED%83%90%EC%A7%80%20%EB%B0%8F.pdf)  
  
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
- Link: [PPT slide](https://github.com/Teemyteem/BK21_technical_porfolio/blob/main/%EB%8D%B0%EC%9D%B4%ED%84%B0%20%ED%99%9C%EC%9A%A9%20%EB%B0%8F%20%EB%B6%84%EC%84%9D/%5B%EB%8C%80%ED%95%9C%EC%82%B0%EC%97%85%EA%B3%B5%ED%95%99%ED%9A%8C%5D%20Stock%20Price%20Prediction%20by%20Using%20Long%20Short-Term%20Memory%20Model%20With%20Multiple%20Look%20Back%20Periods/Stock%20Price%20Prediction%20by%20Using%20Long%20Short-Term%20Memory%20Model%20With%20Multiple%20Look%20Back%20Periods.pdf)  
