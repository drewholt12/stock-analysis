# VBA_Challenge
Steve needs to evaluate stock performance to ensure his parents have made educated decisions for investments.  This project uses collected stock data from 2017 and 2018 showing daily prices and volume for twelve different stock ticker ID’s.  Prices are separated into open, close, high, and low for each day recorded.

## Overview of Project
    
Using VBA code, a macro will be created to utilize a click button for Steve to run an analysis on the supplied data.  The information collected and quantitated results in the annual volume and annual return for each stock.   Initial execution of the code showed a lengthy processing time.  To reduce the time needed to run the code, we refactored the code and utilized array’s to improve those run times.  

## Results

  This project focused on writing VBA code to perform an analysis on a large data set.  Then refactoring that code to perform the same analysis more quickly.  The initial analysis had the following results from 2017 and 2018 respectfully.  The time necessary to run the code was near 1 second for each year. 
  
![Green_Stocks_2017](https://user-images.githubusercontent.com/79231355/112048782-c4adc600-8b1c-11eb-8d74-9a2a372482de.png)

![Green_Stocks_2018](https://user-images.githubusercontent.com/79231355/112048789-c6778980-8b1c-11eb-80b2-034687d9bcf2.png)
  
  
  Refactoring the data, utilizing arrays, improved the processing time for the code.  Reprocessing eliminates unnecessary code and makes the code easier to follow for anyone that may need to work with it later.  Steve will be able to get results much quicker, and the analyst will be able to write less code.  In the following images, note the run times for both years is just over 1/10th of a second.  Nearly 90% faster processing time.
  
  
![VBA_Challenge_2017](https://user-images.githubusercontent.com/79231355/112049223-54ec0b00-8b1d-11eb-8f5b-4cb5fef43124.png)

![VBA_Challenge_2018](https://user-images.githubusercontent.com/79231355/112049228-561d3800-8b1d-11eb-876d-4fe46a694ecf.png)

 ## Summary
 
 Refactoring code is important to enable faster processing time.  Code is more concise, has improved logic, uses less memory, and easier to follow.  Refactoring code can also lead to mistakes or bugs in the code and increase analyst labor costs.  In some cases, refactoring may not improve run time for the code.  In this example, refactoring code to utilize arrays instead of excessive loops created a significant performance increase, improved logic, and allows for even greater data sets without additional changes to the code if the same outputs are desired. 
