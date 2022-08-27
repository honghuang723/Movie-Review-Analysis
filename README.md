# Movie-Review-Analysis

Frist, for every review of audience, I have used sentiment mining to complete sentiment analysis. By 
SentimentIntensityAnalyzer function from NLTK of python, I applied this function to each review
and got the score of positive, neutral, and negative for each row. Those three scores are all between 0 and 1 point, the 
higher the point means the higher the corresponding sentiment.


![Capture](https://user-images.githubusercontent.com/80186041/187047066-da203827-fd8c-40c5-9dae-892186835a7a.PNG)

Linear Regression with OLS model

![Capture2](https://user-images.githubusercontent.com/80186041/187047096-00bb6aca-9e61-474e-85c6-ca9263d7e873.PNG)
![3](https://user-images.githubusercontent.com/80186041/187047097-e2760fc1-240c-455a-9c15-c46486fff9d0.PNG)

From picture above, we can get our linear model:
 y = 2.2218x1 +3.5282x2 +4.0416x3
 
x1 is Neg, x2 is Neu, x3 is Pos and y is rate. Through the result of analysis, the score of R2
scores is 0.874, which states that the actual point is close to the predict regression line.
The AIC and BIC scores are small.The variables of all p values are smaller than 0.05. 
Therefore, we can conduct that this model is suitable to predict.
