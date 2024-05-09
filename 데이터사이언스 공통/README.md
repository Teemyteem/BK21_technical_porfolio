# Stock Price Prediction by Using Long Short-Term Memory Model With Multiple Look Back Periods  
- Objective:
	- Proposed a developed closing price prediction model by using three stocks from the Thai SET50 index (CPALL, AOT, LH).  
- Background:   
	- The stock market has long been a favorite among investors.  
	- To increase their profits, many investors would like to be able to anticipate stock prices, but this is challenging given the uncertain movement of stock prices.  
- Data:   
	- Collecting 2 date range data from the python's yfinance library (yahoo finance API)
   	- (2001.01.01 to 2018.12.31, 2011.01.01 to 2018.12.31)	
   	  
	<img width="350" alt="image" src="https://github.com/Teemyteem/BK21_technical_porfolio/assets/129394136/14c71f0b-bd83-4785-92a7-e80cb1f69bad">	



  <img width="278" alt="image" src="https://github.com/Teemyteem/BK21_technical_porfolio/assets/129394136/f57f3305-ebe1-4051-b25e-18bc9c1f6124">	
     
  	- There are three Thai stocks data:
		- CPALL stock (CP ALL PUBLIC COMPANY LIMITED)   
		- AOT stock (AIRPORTS OF THAILAND PUBLIC COMPANY LIMITED)  
		- LH stock (LAND AND HOUSES PUBLIC COMPANY LIMITED)	
  	- CPALL and AOT is stable stock, LH is volatile stock
  	- Using only "Close" column to be predicted		
 	- Classify into training : testing data = 80 : 20
  	- Do the scaling data
  	- Apply look back (window size) = 30, 60 in x_train, y_train data

  
- ## Model:
	- CNN
 		- Use python's keras to develop CNN model
   		- Use 1D Convolutional Neural Network
     	- Use multiple optimizer (adam, sgd, rmsprop) to compare performance
       - Use multiple epoch (10, 20, 30, 100, 200, 300) to compare performance	 
   		- Use python's numpy to perform mathematical operations (square root, mean, absolute value) to evaluate performance with RMSE, MAPE
     	- Use python's matplotlib to plot graph of prediction data 

	
     	<img width="509" alt="image" src="https://github.com/Teemyteem/BK21_technical_porfolio/assets/129394136/181b1d4d-a2d7-47b3-9e3f-89878909b22b">	
   
 	- LSTM
  		- Use python's keras to develop LSTM model
    	- Use 3-layer stacked LSTM
       	- Use multiple optimizer (adam, sgd, rmsprop) to compare performance
      	- Use multiple epoch (1, 10, 20, 30) to compare performance	
    	- Use python's numpy to perform mathematical operations (square root, mean, absolute value) to evaluate performance with RMSE, MAPE
     	- Use python's matplotlib to plot graph of prediction data 

	
      <img width="455" alt="image" src="https://github.com/Teemyteem/BK21_technical_porfolio/assets/129394136/a0db9d8b-5099-475b-8b89-4118201d5c11">
 
- Result:   
	- In general, the results showed that LSTM outperformed CNN with high-performance.
 	- In some cases, CNN is outperform LSTM.
  	- LH stock in LSTM model with optimizer = adam, epoch = 1, look-back = 30 is the best performance amoung of other stocks.
  	- In case of volatile historical data (LH stock), look back = 30 got higher performance that look back = 60
- Link: [Code](https://github.com/Teemyteem/BK21_technical_porfolio/blob/main/%EB%8D%B0%EC%9D%B4%ED%84%B0%EC%82%AC%EC%9D%B4%EC%96%B8%EC%8A%A4%20%EA%B3%B5%ED%86%B5/Stock.ipynb) [PPT slide](https://github.com/Teemyteem/BK21_technical_porfolio/blob/main/%EB%8D%B0%EC%9D%B4%ED%84%B0%EC%82%AC%EC%9D%B4%EC%96%B8%EC%8A%A4%20%EA%B3%B5%ED%86%B5/Stock%20Price%20Prediction%20by%20Using%20Long%20Short-Term%20Memory%20Model%20With%20Multiple%20Look%20Back%20Periods.pdf)  

