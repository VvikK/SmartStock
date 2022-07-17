# SmartStock
An app used for in-depth analysis and prediction of the stock market.
## Inspiration
Finance has always been a large part of our daily lives, and as students, we have always had an intrinsic passion for the field, whether it be the more quantitative statistics part of finance, or the more business side of it. We have participated in many mock stock market competitions, and even investing in stocks in real life. Through these experiences, we learned much about the stock market, and gained insight into the statistical trends that are evident in the data. This inspired us to create a stock market predictor based on statistical methods such as time series and fourier analysis. 

## What it does
The SmartStock application takes in a ticker symbol, the number of days in the future one wants the predicted graph for, and the number of years in the past one wants to base the prediction off of. This highly customizable system allows the user to gain much insight into different stocks, and use this insight to make an educated prediction on which stocks to buy and sell. The application gives both long-term and short-term predictions. For the long-term prediction, the application gives a prediction range for the percentage increase (or decrease) in the stock in the next month and the next year. There is also a graph to show the predicted trajectory of the stock for the number of days indicated. For the short-term prediction, the application gives a prediction for buying and selling, as well as whether the graph is currently going upwards or downwards. This information would be useful for frequent traders to determine whether it is the right time to buy or sell the stock.

## How we built it
We built the SmartStock application using Python, as well as many libraries that allowed us to use Machine Learning algorithms. We used time series analysis and Fourier series to create a model that could predict the future long-term trends in the stock price. We used quadratic interpolation to predict the future short-term trends in the stock price. We also used Yahoo Finance to retrieve all the stock data that we used to make our predictions.

## Challenges we ran into
In the process, we ran into many challenges. For example, we encountered the challenge of learning all of the statistics knowledge that we needed for this project in a very short amount of time. It was very hard to learn a large amount of knowledge in machine learning and time series analysis in such a short time, but we were able to persevere, and divide and conquer to face this challenge. Also, we had a challenge of displaying the graph on the screen. It was very hard to figure out how to display a graph of data, as well as how to resize and customize the graph to suit the needs of this project. In the end, we were able to persevere through these challenges to make the product we have today. Finally, we had a problem where the data that was outputting in the GUI was not matching our original data from just the backend. The graph was also not deleting itself when we needed it to. We were not able to solve the problems behind our front-end graphical interface, so we had to get rid of it.

## Accomplishments that we're proud of
We are very proud to have learned such a large amount of knowledge in such a large amount of time. We were able to effectively split our team into a front-end and a back-end team, and then combine our code together to create our final product. It was very fascinating to see the algorithm actually running and seeing the predictions it gave for many stocks in the future. Especially since this is our first hackathon, we were able to grow a lot as developers, and learned a lot as well in this short period of time.

## What we learned
Through this hackathon, we learned the importance of coordination and teamwork between front-end and back-end developers. There were some moments where there were issues in the linkages between the front-end and back-end, but we were able to resolve these very quickly through constant communication. We were able to learn a lot about developing applications and we were able to realize the huge amount of hard work that must be put into creating even the simplest of applications. This helped us learn to appreciate all of the cool and useful applications that we are able to access in the status quo. Finally, we learned a lot about statistics and machine learning through this project: in particular, time series analysis, regression, and the Fast Fourier Transform (FFT).

## What's next for SmartStock
There are many things that we could do to improve SmartStock.
1) It could be beneficial to look into different methods of extrapolating the stock data. A comparison could be drawn and this could lead to finding new and better ways of predicting the future stock data. It  could also be beneficial to look into what methods are actually being used in the industry to help gain an understanding of these methods.
2) There are many things in the application itself that could be improved. For example, being able to enter specific date ranges, and number of days for the data that is used to predict the future stock price (instead of number of years), would allow for a more customizable interface that could allow the user to gain even more insight into the future stock prices.
3) We could also incorporate factors like economic growth/recession, inflation rates, and overall trends in the stock market (ie. using the Dow Jones index) to create an even better prediction of the stock market. This would also allow the user to gain even more insight into future trends and predictions in stock prices.
4) One thing we were not able to figure out is how to fix the Graphical User Interface. If the two bugs that we were not able to solve are fixed, then it could drastically improve the quality of our application and the visual aesthetics.

## Modules Used in the project
numpy, 
pandas,
matplotlib.pyplot,
yfinance,
statsmodels.tsa.seasonal,
pylab,
scipy.optimize,
math,
