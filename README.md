# Factor Timing Using Machine Learning
We wish to come up with a dynamic strategy to allocate between Factor-based ETFs such as Momentum, Value, Low Volatility etc. We will incorporate machine learning algorithms to help us in creating a systematic strategy to decide the portfolio weights at each rebalance frequency with the aim to beat the broad market benchmark.

# Plan Of Action:

We shall approach the problem in the following way:
1.	Data Curation: The first step to solving this problem would be to get reliable data for factors as well as the macroeconomic indicators we wish to use for the project. We have identified the following sources for getting the data related to factors:
a.	Kenneth R. French Data Library – US Factor Returns Data Updated and Shared by Professor Fama and French considered the gold standard for US Factor Data https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html
b.	Global Factor Data - https://jkpfactors.com/ 
c.	AQR Factor Data Sets - https://www.aqr.com/Insights/Datasets
d.	Yahoo Finance Api – For getting the ETF Historical Price Data
e.	FRED Api – Macroeconomic and Interest Rate Data Points
2.	Exploratory Data Analysis: Once we have the data from the First Step, the second step would be to analyse the data sets for efficacy/missing values or any other potential problems with the data. 
3.	Defining the Problem Statement – Once the Data Curation and EDA is complete, we would focus on the problem statement which is two-fold:
a.	Predict factor returns
b.	Allocate Weights to your ETFs
4.	Model Development – At this stage we hypothesize regarding the model needed to address the problem statement. We would test a bunch of ML algorithms such as XGBoost, LightGBM, Linear Regression, Neural Networks or an ensemble model to best address the problem. 
5.	Model Testing and Hyperparameter Tuning – We will train the model and tune the hyperparameters to give us the most appropriate model for our use case.
6.	Testing The Model Out Of Sample – We will test our proposed model out of sample. 
7.	Backtesting: Based on the proposed model we will Backtest our strategy and report the results.
8.	Reporting Findings and Conclusion

# How does the project help in the context of current Financial Engineering:

We saw in the competitor analysis that most of the current investment strategies rely on qualitative active management or simple heuristics such as Factor Momentum to time Factors. Through this project, we will propose a novel way to incorporate cutting-edge Machine Learning Algorithms to solve this problem. 
The usual disdain among industry practitioners is the black box label attached to any ML strategy. We will try to make it as simple and interpretable as possible.
Possible Obstacles and Impediments:

# Other Real-life applications:
Although the project is based on factors, the concept of timing can be extended to:
1.	Stock markets – Size Segments – Timing the cycles in Large, Mid and Small Cap Segments
2.	Thematic/Sectoral Fund Categories – This can also be extended to predict the movement in thematic funds or sectors.
3.	Commodity Prices – It can help in deciding the interplay of different commodity prices like crude oil, metals etc and can serve as a valuable guide for companies dependant on commodities an major costs for business. 

# References
a.	1.       Kenneth R. French Data Library – US Factor Returns Data Updated and Shared by Professor Fama and French considered the gold standard for US Factor Data https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html
b.	Global Factor Data - https://jkpfactors.com/ 
c.	AQR Factor Data Sets - https://www.aqr.com/Insights/Datasets
d.	Yahoo Finance Api – For getting the ETF Historical Price Data
e.	FRED Api – Macroeconomic and Interest Rate Data Points

# Bibliography
1.       Validea Factor Rotation ETF Portfolios https://www.validea.com/factor-rotation-etf-portfolios
2.       Pacer Lunt Large-Cap Multi-Factor Alternator ET https://www.paceretfs.com/media/palc.pdf
3.       DYNF BlackRock U.S. Equity Factor Rotation ETF https://www.blackrock.com/americas-offshore/en/literature/prospectus/p-blackrock-us-equity-factor-rotation-etf.pdf

