# Lecture-2
 Types and Structures - Python Iterative and Conditional Constructs

'''Exercice 1.1 : Stock Information
Problem : Create variables to store the following information about a stock :
- Ticker : "AAPL"
- Opening prince : 145.5
- Closing price : 146.3
- Volume of shares traded : 100000'''
#solution :
ticker = "AAPL"
opening_price = 145.5
closing_price = 146.3
volume = 100000
print("Ticker :", ticker, "Opening Price :", opening_price, "Closing Price :", closing_price, "Volume :", volume)


'''Exercice 1.2 : Currency Exchange
Problem : Create variables to store the following information about a currency exchange rate :
Currency pair : EUR/USD
Buying rate : 1.1825
Selling rate : 1.1830'''
#Solution :
currency_pair = "EUR/USD"
buying_rate = 1.1825
selling_rate = 1.1830
variables = [currency_pair, buying_rate, selling_rate]
print(variables)


'''Exercice 1.3 : Portfolio list
Problem : Given a list of stocks, create a new list that adds Tesla to this portfolio. Print the new list.'''
#Solution :
stocks = ["APPL", "MSFT", "GOOGL"]
stocks.append("TSLA")
print(stocks)


'''Exercice 1.4 : Adding more stocks
Problem : Given the previous list of stocks, add Tesla, IBM, and General Electric to the portfolio.'''
#Solution :
stocks = ["APPL", "MSFT", "GOOGL"]
new_stocks = ["TSLA", "IBM", "GE"]
stocks.append(new_stocks)
print(stocks)


'''Exercice 1.5
