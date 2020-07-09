# NASDAQ-Stock-App-Tkinter
A simple stock app, showing all companies and their stocks in NASDAQ.

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [py to exe](#py-to-exe)
* [License](#license)

## General info
This project is a simple Stock app showing stocks of all companies in NASDAQ. You'll be needing some modules. The live stock price has also been added to the ```get_quote_table``` function, which pulls in additional information about the current trading day’s volume, bid / ask, 52-week range etc. — effectively all the attributes available on Yahoo’s [quote page](https://finance.yahoo.com/quote/AAPL?p=AAPL).

![Screenshot (17)](https://user-images.githubusercontent.com/67178624/87005597-df354e80-c1dc-11ea-933d-cb118402ee43.png)

![Screenshot (16)](https://user-images.githubusercontent.com/67178624/87005604-e2303f00-c1dc-11ea-8bc8-0f3f35bb6acb.png)
		
## Technologies
Project is created with:
* Python version: 3.8.3
* Tkinter version: 8.5
* yahoo_fin package.
	
## Setup
### To run this project,
#### Install Tkinter
```
pip install tkinter
```
#### Install Wikipedia Api
```
pip install yahoo_fin
```
#### Install other packages for yahoo_fin to operate.
```
pip install ftplib
pip install io
pip install pandas
pip install requests
pip install requests_html
```
#### Or use the requirements.txt
```
pip install -r requirements.txt
```
## yahoo_fin methods
### The yahoo_fin package has two modules. These are called stock_info and options. 
* Stock_info has the below primary methods.
```
get_analysts_info
get_balance_sheet
get_cash_flow
get_data
get_day_gainers
get_day_losers
get_day_most_active
get_holders
get_income_statement
get_live_price
get_quote_table
get_top_crypto
get_stats
get_stats_valuation
tickers_dow
tickers_nasdaq
tickers_other
tickers_sp500
```
* The methods for options are listed below
```
get_calls
get_expiration_dates
get_options_chain
get_puts
```
## Customization
### Customize the App according to your desire.
* Customize the app on your desire.
* Add the above methods.
* You can get Crypto prices as well using the above module. 
* You can also use tickers as an input.

## .py to .exe
### Convert .py file to .exe file
#### Install the pyinstaller module
* ```pip install pyinstaller```
#### Instructions
* Open your cmd and change your directory to the .py file.
* Choose an Icon. Icon must be in .ico format.
* Type ```pyinstaller -w -F -i (Your icon directory with file name) (filename.py)``` and hit enter.
* Open the directory and go to Dist folder where you can find the App.

## License
* MIT licensed. See the [License](LICENSE) file for full details. 
