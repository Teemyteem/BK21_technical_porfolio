 ## Predicting condominium prices in Bangkok  
  
- Objective: 
  - To predict the sales price per square meter of a condominium in Bangkok.    
- Background:   
  - In Bangkok, condominiums are becoming the first home for many people who prefer a convenient lifestyle  
  - Apartment prices are one of the most important factors in buyers' decision-making
  
- Data: 
  - The program used Selenium as a web crawling tool to collect data from www.hipflat.co.th
  - Additional features is shown as in red box below.
  - Y = price per square
<img width="565" alt="image" src="https://github.com/Teemyteem/BK21_technical_porfolio/assets/129394136/5d120bae-8a3d-4591-9922-f9bbedfc20d3"> 

- Model:
  - Linear Regression, Regression Tree, Random Forest Regression, Gradient Boosting Regression  
  
- Result:  
  - For the existing variables, 'No_floor', 'Price_chg_from_lastyr', and 'Price_chg_prev_quart' are important variables.  
  - For the additional variables, 'Price_for_sale', and 'Price_for_rent' are important variables.  
  - Adding more characteristics gives you better performance.  
  - Random forest regression is the best forecasting model
- Link: [Code](https://github.com/Teemyteem/BK21_technical_porfolio/blob/main/%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EC%88%98%EC%A7%91%20%EB%B0%8F%20%EC%A0%95%EC%A0%9C/Condo%20price%20per%20square%20meter%20prediction.ipynb) [PPT slide](https://github.com/Teemyteem/BK21_technical_porfolio/blob/main/%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EC%88%98%EC%A7%91%20%EB%B0%8F%20%EC%A0%95%EC%A0%9C/Predicting%20condominium%20price%20in%20Bangkok.pdf)
