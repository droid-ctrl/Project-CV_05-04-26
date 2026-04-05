# Project-CV_05-04-26
This a collection of the projects outlined in my CV. Please explore. If you have any questions, feel free to contact me on LinkedIn(www.linkedin.com/in/angus-kennedy-ab9660299)


Binomial Tree (Excel): 
This was made to price both American and European options for the S&P 100 index. I am aware that the Black-Scholes model is optimal for European options, due to their fixed exercise timing and so that will be my next project (regarding derivatives pricing). I used OEX, XEO and VIX data from the Chicago Board Options Exchange, the dividend yield comes from Bloomberg. The time to maturity is represented in years. For this example I used a 3 month maturity.

K-means (Python): 
This project uses PWT.11 data. I was inspired to use a k-means clustering for my econometrics project after reading 'Advanced Statistics for Researchers'. This algorithm is part of 4500-word econometric analysis on the determinants of economic growth. We used a linear regression model based on an augmented Solow growth model (includes human capital). The purpose of this algorithm was to identify outliers for robustness checks with regards to the regression models. Which it did successfully, clustering India, China and the United States together. However the results overall were underwhelming, I believe this was due to the inclusion of RGDP per capita and Population within the features, leading to data leakage. Furthermore, I believe we could improve on this by using fertility rates as a proxy for GDP-per capita as the two have a very strong negative correlation. 

Trading Algorithm (Python): 
This algorithm was one of about a dozen gradually evolving to machine learning utilizing logistic regressions. The reason these more complex algorithms are not included in this repository is due to my increasing reliance on AI generated code and thus they became increasingly removed from my actual capabilities (also some of the bugs are horrendous especially with MCMC) 

To properly use this, you need to:  

1: Test for positive autocorrelation. I used a Durbin-Watson test. 

2: If the time series exhibits properties of positive autocorrelation, you can apply it through interactive brokers API. 

3: As this algorithm has a tick rate of about 0.1 seconds the gains are very minor so you would need huge liquidity, admittedly I used a paper trading account as I am a university student and not a billionaire. 

Overall: The biggest short coming of the algorithm is that it uses yahoo finance data which has a 20-minute delay. Meaning 
that all the gains that I did manage to get were from pure luck. 

Finally: This algorithm was built out of academic curiosity NOT because I thought I could compete with firms like Hudson-river trading. 



A Note on Methodology: 
All these projects are AI assisted. Though each project is associated with around 30-60 prompts depending on the task. Since building these I have experienced multiple issues with AI especially with python, mainly emerging from a lack of context and bad debugging (also on my part). To combat this, I have re-enrolled in DataCamp and have chosen the associate data science career track. I will be finishing this course by the end of May 2026.
