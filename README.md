# finance_app
The goal of this app is to email me when a company I invest in files new financial documents with the SEC

The objective of this application is to 1. take structured data from the Securities and Exchange Commission (SEC) through its RSS feed; 2. turn that feed into a table using Pandas in Python; 3. match a specific cell and row, row by row of that table to a seperate list of stock tickers representing my investments; 4. when there is a match, email me the related row from the table. 

I would also write code to run this program every day. To do this, the program would need to refresh daily — I'm not sure what that entails, but RSS feeds are dynamic, so they update on their own. 
