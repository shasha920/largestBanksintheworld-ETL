# largestBanksintheworld-ETL

*dataset:<br>*
*wikipedia webpage https://en.wikipedia.org/wiki/List_of_largest_banks , provides information about largest banks in the world by various parameters.*
*https://exchangeratesapi.io/ , provides currency exchange rate data.*



*Process:*
*1.Scrape the data from wikipedia, the table 'By market capitalization' and store it in a JSON file.*
*2.Using ExchangeRate-API extract currency exchange rate data*
*3.Run the ETL process*
*4.Extract bank and market cap data from the JSON file bank_market_cap.json*
*5.Transform the market cap currency using the exchange rate data*
*6.Load the transformed data into a seperate CSV*
