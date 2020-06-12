# Challenge

UTDA Module 2 Challenge Submission

## Description

The included excel file includes the Refactored code for the Challenge Assignment.

Both of the subroutines give the same results.  The refactored code runs significatly faster than the original code.  This is due to the fact that rather than using one array to track the ticker and gathering the data for each output by looping through the data 12 times, the data is stored in arrays and the data is gathered with one loop through it.  Please note this code will only work if the data is grouped by ticker and sorted by date.

Without modification nine additional tickers could be added to the data sheet and added to the analysis because the arrays have 21 values (0 to 20).  If more than nine tickers were added the code could be adjusted by increasing the size of the arrays and increasing the number of loops done on the totalVolume loop that initializes a zero value for each value in the array.
