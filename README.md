## Pricing King County Homes

- Analysis of the homes sold in King County 2014 -2015

Author: Deja Prade

## Overview

In this project, I analyzed the homes sold in King County 2014-2015. My findings were transformed to find recommendations for home sellers pricing new builds based on previously built similar homes. My analysis revealed that bathrooms, floors and sqft living all increase value in a home.  

## Business and Data Understanding

Home sellers have expressed an interest in properly pricing homes so I dove into the Kings County data set to see what features were significant in adding value to a property. From the data i observed i chose basic variables to base adding value and add more variables as i went.

## Modeling

I created 7 models based on the variables i found relevant. The first model looked at sqft lot and how it added value to the home, i got an r-squared value of 8%. The second i used sqft lot, bedrooms, and bathrooms and i got an r-squared of 25%. My third model included sqft lot, sqft living, bathrooms, bedrooms and floors which gave me an r-squared value of 45%. My fourth model i added water front to get a r-squared of 46%. My fifth model i added in all of the conditions to get an r-squared of 47%. My sixth model i added in grade to get an r-squared of 54%. my seventh and final model gave me my best r-squared at 55% which i added zipcode. although the last model had the highest rsquared it still wasnt a good model because of the high rmse. 

<img width="1028" alt="Screen Shot 2021-11-21 at 5 03 29 PM" src="https://user-images.githubusercontent.com/92389914/142785127-9ce6582a-84e1-4405-9d42-cc6c68a5b7a9.png">


## Regression Results
My predictions were accurate according to my test model. The model with an 55% r-squared showed the zip code a home is in having the biggest affect on the homes pricing with an estimated $550 added as zip codes changed. I need to go back in and add variables to attempt a better r-squared and to correct the coef. that should be positive.

<img width="506" alt="Screen Shot 2021-11-21 at 5 16 51 PM" src="https://user-images.githubusercontent.com/92389914/142785139-58a5caa4-b754-4f86-98ed-f214b4a795a3.png">
<img width="1042" alt="Screen Shot 2021-11-21 at 5 32 49 PM" src="https://user-images.githubusercontent.com/92389914/142785150-5a425e66-d261-410a-b2d2-75c830dff3d8.png">


## Conclusion

Of all the models I created my seventh and final was my best according to the R- squared, which was 55%, but most of the features didnt actually add value. I also got a rmse of 172022.53 which indicates my model is terrible. I recommend that I have more time to go back to the drawing board to get better predictions.

For More Information

Please review our full analysis in our Jupyter Notebook or our presentation.

For any additional questions, please contact Deja Prade - Deja.Prade@gmail.com
