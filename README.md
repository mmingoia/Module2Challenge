# Challenge

UTDA Module 2 Challenge Submission

## Description

The included excel file includes the original code for the lesson that is used on the "All Stocks Analysis" Tab as well as the Refactored code used on the "All Stocks Analysis Refactor" Tab.

Both of the subroutines give the same results.  The refactored code runs significatly faster.  This is due to the fact that rather than using one array to track the ticker and gathering the data for each output by looping through the data 12 times, the data is stored in an array and the data is gathered with one loop through it.  Please note this code method will only work if the data is grouped by ticker and sorted by date.

Additional tickers could be added to the data sheet and added to the analysis by increasing the size of the arrays and increasing the size of the loop for setting the totalValue to zero and the output loop.
