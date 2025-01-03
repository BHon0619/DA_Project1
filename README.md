# DA_Project1
CSV manipulation
## Project Overview
OBJECTIVE: Determine various data points about the passengers aboard the Titanic.
## Source
https://www.kaggle.com/datasets/vinicius150987/titanic3
## Questions
Question 1: Did passenger class have an impact on survival rate?
Question 2: Did the price of the ticket correlate to survival rate?
Question 3: Did more males or females survive?
## Read in the Data
Data was imported from Kaggle.  It was an excel spreadsheet which I converted to a CSV file.
## Data Cleaning
Replaced the NaN values in the boat(lifeboat) column with DNB.  This the acronym for 'did not board'.
Converted the 'fare' column to currency format.  
Converted age to years and months verses a float.  I found this was not a really good change as it was dificult to determine median age.
Added a column to categorize the age of the passengers as child, adult, senior.
## Exploratory Data Analysis
Provided mean, median, min, max for the 'fare'.
Provided bar graphs for 'Survival Counts By Gender' and 'Survival Counts By Passenger Class'.
Provided a scatter plot of 'Age vs Fare with Survival Rates'.
Provided pair plot of numeric features colored by survival rates.
## Analysis and Insights
Refer to titanic_data.ipynb
## Conclusions and Recommendations
Passenger class had a significant correlation to survival.  First class passengers were the only class to have more survivors than deaths.  The number of survivors decreased as the class of the passenger decreased.
The price of had an impact on survival.  However, the most interesting information was that the few passengers with the highest fare rate all survived.
Female passengers had a significantly higher survival rates by percentage.  However, it should be noted that there were significantly fewer females on board to begin with so a percentage made the data more clear.
Further pursuit in this data would consider the port of call and the impact on survival.  
While the sibling and parent information was removed, after the analysis, it would be interesting to determine sole survivors, loss of total family, etc.   
<<<<<<< HEAD
It would also be interesting to know about the crew survival rates.
=======
It would also be interesting to know about the crew survival rates.
>>>>>>> 56cdf73021f31e42f62370e000d9b827b0aa6561
