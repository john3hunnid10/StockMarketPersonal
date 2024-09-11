# StockMarketPersonal
My portion of an AI stock market predictor.
It was originally a personal project with a friend, but was not finished.
My portion functions on its own and therefore I'm uploading it as a seperate project. 
The predictable values are: ['HIGH', 'LOW', 'OPEN', 'CLOSE', 'ADJ CLOSE', 'VOLUME']
Date should be integers in the form: (Year, Month, Day)
Example input: ((2024,5,30),"INTEL","HIGH").
It then returns the predicted value, and if the prediction is of a day that has already happened, the function will return it's accuracy.
NOTE: Data ranges from 1/1/2023-8/4/24
