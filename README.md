# Stock-Trading-Platform
A Stock Trading Platform collaboratively designed and coded by a team of 4.

Made use of the Left Leaning Red Black Tree to represent the stored data and to efficiently perform auxiliary operations on the data.

Operations that can be performed are:
- logTransaction(record):adds a newly completed transaction record to those logged so far.
- sortedTransactions(stockName): returns all transactions of a given stockName completed so far, sorted by increasing trade value. The trade value of a transaction is defined as the price per stock multiplied by the quantity of stocks traded in such transaction.
- minTransactions(stockName): returns the transaction(s) of a given stockName with minimum trade value seen so far.
- maxTransactions(stockName): returns the transaction(s) of a given stockName with maximum trade value seen so far.
- floorTransactions(stockName, thresholdValue): returns the transaction(s) of a given stockName with largest trade value seen so far below a given thresholdValue.
- ceilingTransactions(stockName, thresholdValue): returns the transaction(s) of a given stockName with smallest trade value seen so far above a given thresholdValue.
- rangeTransactions(stockName, fromValue, roValue): returns the transactions of a given stockName seen so far whose trade value is within the range [fromValue, toValue].
