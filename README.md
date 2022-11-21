# largestBanksintheworld-ETL

*dataset:<br>*
*wikipedia webpage https://en.wikipedia.org/wiki/List_of_largest_banks , provides information about largest banks in the world by various parameters.<br>*
*https://exchangeratesapi.io/ , provides currency exchange rate data.<br>*



*Process:<br>*
*1.Scrape the data from wikipedia, the table 'By market capitalization' and store it in a JSON file.<br>*
*2.Using ExchangeRate-API extract currency exchange rate data<br>*
*3.Run the ETL process<br>*
*4.Extract bank and market cap data from the JSON file bank_market_cap.json<br>*
*5.Transform the market cap currency using the exchange rate data<br>*
*6.Load the transformed data into a seperate CSV<br>*
