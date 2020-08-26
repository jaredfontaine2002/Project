# Project
Udacity Project

Since Apple has become a 2 trillion dollar company and there is a social problem with social inequality, I wanted to see if there is a linear relationship with the United States Unemployment rate and the tech industryI really want to see if the Tech sector and the stock market is completely independent from mainstream America. 

Also, the Federal Reserve is buying billions of dollars of assets to help the stock market.  I added the monthly change in total assets held by the federal reserve as a variable. I used the change in assets to keep the model accurate.  

I used the monthly returns for all the variables for 10 years starting in August 2010.  We will use the Buearu of Labor Statistics U3 Unemployment rate as the variable we are looking for. Our independent variables are the Vanguard Tech ETF.  

I choose this ETF becauseit follows the overall market trend for the tech sector.  The next variable I used was the stock monthly Stock Returns for Apple. I really want to see if there is a relationship with the world's first $2 Trillion dollar company.  

Note: This would create some multicollinearity with the the AAPL close and the Tech Vanguard ETF since the ETF tracks, Apple, Microsoft etc.  I used the visualization tool to see the multicollinearity and found there was some.  I decided to continue with the analysis.  

I used the SKlearn's linear regression from Python to conduct my analysis.  I looked for the R^2 to see if there is a relationship between the market and the unemployment statistic.
