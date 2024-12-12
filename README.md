# Data-analysis-and-reviews-prediction-for-Zomato-Bengaluru-Restaurants
- Built a sentiment analysis and logistic regression classification model achieving 92.25% accuracy for Zomato Bengaluru Restaurants reviews.
- The data was wrangled and cleaned with Python with predefined steps, found in (data wrangling steps.txt)
- The data analysis process contains ( Univariate - Bivariate) analysis with predifend questions, found in (Univarite and Bivariate analysis questions.txt)
- Used tools: python, pandas, Numpy, seaborn , re and Sklearn
- Dataset link: https://www.kaggle.com/datasets/himanshupoddar/zomato-bangalore-restaurants

# Univariate Analysis Conclusion:
- almost of the restaurants have the option to online order by (58.84%) and (41.16%) haven’t.
- big percentage of the restaurants haven't the option to book table by (87.54%) and (12.46%) can.
- The most appeared type of restaurant is delivery then dine out restaurants, the other types are rarely appeared, we can conclude that they are not preferred or liked by people, they focus on delivery and dine out
- The rates are left skewed, the most frequent rates varies from more than 2 and less than 5, and 0 rates they are outlier but it's important as it's more than 2000 zero rates
- Almost the median cost is 350, There's a big difference between the IQR 2 and max value.
  
# Bivariate analysis conclusion:
- There's no correlation between the columns, they are independent somehow.
- If the restaurant has option to order online, it increases the cost somehow.
- If the restaurant has option to book table, it increases the rating as it's appeared in the orange box plot, it increased over 4
- The greater number of votes doesn't affect the rating we receive.
- The option of online order affects the rate of restaurant but with very small influence
