# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
My goal is to create a regression model comparing bike stations around poi's. I will initially attempt to compare ratings across the different APIs. Even if this does not prove successful, i will attempt to make a regression and derive an insight from the data i obtain.

## Process
1. I will actually get the data i need via api calls and put it in the right form and place. This will all happen in part 1 and 2!

(A big challenge for me was finding out how to get 1000m around each individual latitude and longitude from the bike api... more on that in the challenges section)

2. After getting all this data ill need to put it together into one bigger final dataframe. i need to use this dataframe to preform a regression, along with storing the data in sqlite3.

3. Finally, i will take all of my work and make a regression model to see if i can make any predictions or derive anything from what i obtained! I will make inferences and note any relations i find important.

## Results
Yelp overall seemed to be a better place to get info from. The coverage was far better than foursquare. In fact, foursquare did not even give me the rating data i was waiting for...

I developed a regression model to predict the number of available bikes based on POI ratings. The model yielded promising results, with an R-squared value of 0.703 and an F-statistic of 18.91. These metrics indicate the relevance and significance of the model in explaining the variance in the number of available bikes.

Interpretation of Model Results:
The estimated intercept (const) of approximately 2.8389 suggests that when the rating is zero, we expect the number of available bikes to be around 2.8389. Additionally, the coefficient for the 'Rating' variable is approximately 1.3469, indicating that for every one-unit increase in the rating of POIs, we expect the number of available bikes to increase by about 1.3469.

Conclusion:
Overall, I am satisfied with the outcome of the analysis, especially considering my beginner status. Despite challenges with data discrepancies and missing rating data, the project provided valuable learning experiences and insights into the relationship between POI ratings and the availability of bikes.





## Challenges 
Many challenges every step of the way, from simple api calling to the actual model itself. I very much struggled with getting a 1000m radius around EVERY coordinate. At first i did it for one individual coordinate and continued, only realizing my data was super small too late. 

I initially chose London city as my location, but there was so many bike stations and i wanted to work with a bit of a smaller dataset so i can get used to working with them better.

Looking back and trying to remember how to interpret the values in the regression was tough as well.

## Future Goals
If i had more time, i would absolutley make sure the data was in better shape before running a regression. I have a feeling it isnt the best it could be, and i could have maybe gone back and tried to figure something out for the foursquare rating... next time ill make sure to complete my data.
# Final-Project-Statistical-Modelling-with-Python
