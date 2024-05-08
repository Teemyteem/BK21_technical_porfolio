 # Predicting condominium prices in Bangkok  
  
- Objective: 
  - To predict the sales price per square meter of a condominium in Bangkok.    
- Background:   
  - In Bangkok, condominiums are becoming the first home for many people who prefer a convenient lifestyle  
  - Apartment prices are one of the most important factors in buyers' decision-making
  
- ## Data: 
  - The program open a Chrome browser instance and navigating to a specific web page [www.hipflat.co.th](https://www.hipflat.co.th/en/search/sale/condo_y/TH.BM_r1/any_r2/any_p/any_b/any_a/any_w/100.6244261045141,13.77183154691727_c/12_z/list_v)
  <img width="586" alt="image" src="https://github.com/Teemyteem/BK21_technical_porfolio/assets/129394136/b11f9832-ac17-4216-852a-070c43e05459">
 
  - The program used Selenium as a web scraping tool to scrape data from www.hipflat.co.th 
  <img width="560" alt="image" src="https://github.com/Teemyteem/BK21_technical_porfolio/assets/129394136/0a2c70b7-14df-408d-be94-5b14953168bd">
  
  - All features are shown as below. 
  - Y = price per square 
  <img width="565" alt="image" src="https://github.com/Teemyteem/BK21_technical_porfolio/assets/129394136/5d120bae-8a3d-4591-9922-f9bbedfc20d3">

- Data preprocessing:
 - Remove row in column "title" if it has null value 
 - Remove row in column "Price_per_sqm" if it has 0 value  
 - Replace null with 0 value 
 - Convert object type to numerical type in column "Year_built","No_floor","Dist_bts","Dist_mrt"
 - Do correlation heatmap 

- Model:
  - Training: Testing = 80:20 
  - Develop and train Linear Regression, Regression Tree, Random Forest Regression, and Gradient Boosting Regression model
  - Evaluate performance with accuracy score  
  
- Result:  
  - For the existing variables, 'No_floor', 'Price_chg_from_lastyr', and 'Price_chg_prev_quart' are important variables.  
  - For the additional variables, 'Price_for_sale', and 'Price_for_rent' are important variables.  
  - Adding more characteristics gives you better performance.  
  - Random forest regression is the best forecasting model
- Link: [Code](https://github.com/Teemyteem/BK21_technical_porfolio/blob/main/%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EC%88%98%EC%A7%91%20%EB%B0%8F%20%EC%A0%95%EC%A0%9C/Condo%20price%20per%20square%20meter%20prediction.ipynb) [PPT slide](https://github.com/Teemyteem/BK21_technical_porfolio/blob/main/%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EC%88%98%EC%A7%91%20%EB%B0%8F%20%EC%A0%95%EC%A0%9C/Predicting%20condominium%20price%20in%20Bangkok.pdf)
