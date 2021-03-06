This readme describes the 6 files needed to create the data figures used in The Global Economy textbook written by the Global Economy working group and New York University Stern School of Business.  The latest version of these codes, as well as the textbook are available at www.stern.nyu.edu/GEMatter.

Kim J. Ruhl
September 7, 2012

 
There are 5 chapters with figures.  Each chapter has an associated STATA do-file that downloads the most up-to-date data from the St. Louis Federal Reserve's FRED database, processes the data, and creates encapsulated postscript files of the figures.   

1.  The Solow Growth Model associated file: "figures_solow_2012.do"	(Does not need to be updated --- no data in this chapter.)
2.  Business Cycle Properties associated file: "figures_byprops_2012.do"  (Four figures.)
3.  Business Cycle Indicators associated file: "figures_indicators_2012.do"
4.  Monetary Policy and Inflation associated file: "figurs_inflation_2012.do"
5.  Exchange rate fluctuations associated file: "figures_fx_2012.d0"

The comma separated file "ge_data.csv" contains a few data series that are not directly accessed from FRED through STATA.
The comma separated file "sp500.csv" contains the sp500 data, which is no longer available from FRED.  Download it from Yahoo Finance, instead (historical prices on the left-hand sidebar). 

The STATA do-files are written for STATA 11, and make use of the STATA user-written program "freduse."  This program can be installed by issuing the command "ssc install freduse."

Update August 14, 2015
Stata for Windows can now save figures in pdf format.  Life is a little simpler now. 

Did we drop the Greek interest rate - inflation figure from the book?

 