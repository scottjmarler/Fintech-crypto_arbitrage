> # Crypto Arbitrage Application

[<img src="https://img.shields.io/badge/language-Python-orange.svg?logo=LOGO">](https://www.python.org/)
[<img src="https://img.shields.io/badge/platform-dev-orange.svg?logo=LOGO">](<LINK>)
[<img src="https://img.shields.io/badge/libraries-3-orange.svg?logo=LOGO">](<LINK>)
[<img src="https://img.shields.io/badge/license-GNU General Public License v3.0-blue.svg?logo=LOGO">](COPYING.txt)


---

## Technologies

*The technologies required for the program to run are as follows:*

### Languages:   

### [Python](python.org)

### Libraries:  

>pandas  https://pandas.pydata.org/

>pathlib  https://docs.python.org/3/library/pathlib.html

>matplotlib  https://matplotlib.org/

---

## Usage


*The datasets used in the program are:


> 1. `bitstamp_sliced` and `coinbase_sliced` to extract `Close` price from  DataFrame for 2018-02-22

> 2. `arbitrage_spread_early`, `arbitrage_spread_middle`, `arbitrage_spread_late` to extract data from the DataFrame for the following dates: 2018-01-01(early), 2018-02-10(middle), 2018-03-25(late) and discplay the spread of the two exchanges based on the dates chosen.

> 3. `profitable_trades_early`, `profitable_trades_middle`, `profitable_trades_late` to return the data from the arbitrage thats (>0).

> 4. `spread_return_early`, `spread_return_middle`, `spread_return_late` dividing the instances when the arbitrage spread is positive (> 0) by the price of Bitcoin from the exchange you are buying on (the lower-priced exchange) to gice you a return on your trade. 

> 5. `profit_early`, `profit_middle`, `profit_late` is is used to represent the profit made from each transaction based on  `profitable_trades_ * coinbase['Close'].loc['2018-02-10'].

> 6. `coinbase.csv`, and `bitstamp.csv` dataframes used to create the spread from index selected. 
   
---

## Contributors

Scott J. Marler


> ### LinkedIn Profile:     [https://www.linkedin.com/in/scott-marler-212040b6/](https://www.linkedin.com/in/scott-marler-212040b6/)



---

## Licenses

> [GNU General Public License v3.0](COPYING.txt)




