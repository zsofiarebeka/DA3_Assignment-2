# DA3_Assignment-2

This report aims to present the findings for my analysis conducted for our partner company, focusing on small and mid-sized apartments for shorter rentals. The objective of this report is to provide insights into pricing strategies for [Airbnb listings in Toronto]("http://insideairbnb.com/toronto"). 

## Key findings:
Comparing the lowest RMSE values of the models tells us that the most complex OLS model with interactions has the best predictive performance. 
To compare if the feature importance values from RandomForest would actually have a better predictive power, I added another OLS model. Interestingly, regressing the price on the variables with the highest feature importance yielded worse results than expected. Comparing the RMSE value of the most complex linear regression with variables selected by hand (50.559) and the RF adjusted regression (54.705) shows us a significant difference. This indicates that while certain features may have high importance in RandomForest, their predictive power may not translate well to other types of models.

## Recommendations:
The company should adopt specific pricing strategies, emphasizing private rooms and adjusting guest and bed numbers. Price increases per additional guest should be limited to $50. For 2 guests, they should aim for $100, and around $200 for 6 guests. I would suggest higher prices for rental units accommodating 2 guests, and slight overpricing for houses hosting 6 guests should be acceptable. 
