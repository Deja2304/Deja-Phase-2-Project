## Pricing King County Homes

- Analysis of the homes sold in King County 2014 -2015

Author: Deja Prade

## Overview

In this project, I analyzed the homes sold in King County 2014-2015. My findings were transformed to find recommendations for home sellers pricing new builds based on previously built similar homes. My analysis revealed that bathrooms, floors and sqft living all increase value in a home.  

## Business and Data Understanding

Home sellers have expressed an interest in properly pricing homes so I dove into the Kings County data set to see what features were significant in adding value to a property. From the data i observed i chose basic variables to base adding value and add more variables as i went.

## Modeling

I created 3 models based on the variables i found relevant. The first model looked at sqft lot and how it added value to the home, i got an r-squared value of 8%. The second i used sqft lot, bedrooms, and bathrooms and i got an r-squared of 25%. My last model included sqft lot, sqft living, bathrooms, bedrooms and floors which gave me my best r-squared value of 45%.

<img width="540" alt="Screen Shot 2021-11-19 at 1 15 48 PM" src="https://user-images.githubusercontent.com/92389914/142679141-58cc56ff-95e6-4543-aa23-5b3ebbac30e2.png">
<img width="521" alt="Screen Shot 2021-11-19 at 1 15 58 PM" src="https://user-images.githubusercontent.com/92389914/142679160-1217d6b8-37d8-4d69-a234-29fb08e54c39.png">
<img width="510" alt="Screen Shot 2021-11-19 at 1 16 21 PM" src="https://user-images.githubusercontent.com/92389914/142679173-f1e4f2c1-651a-4236-bd0d-477b879ce584.png">


<img width="519" alt="Screen Shot 2021-11-19 at 10 22 18 AM" src="https://user-images.githubusercontent.com/92389914/142666383-699c6a93-5db1-4149-8d9a-66cac710bb40.png">

## Regression Results
My predictions were accurate according to my test model. The model with an 45% r-squared showed bathrooms, floors, and sqft living adding value to homes while sqft lot and bedrooms decreased value if more are added. I need to go back in and add variables to attempt a better r-squared and to correct the bedrooms coef. that should be positive.

<img width="532" alt="Screen Shot 2021-11-19 at 10 20 38 AM" src="https://user-images.githubusercontent.com/92389914/142666536-43ee28ab-ed65-4696-9868-7f2782efbfa1.png">
<img width="367" alt="Screen Shot 2021-11-18 at 12 42 14 PM" src="https://user-images.githubusercontent.com/92389914/142666696-17fe5ebd-08b7-4175-8a8c-38eada68d034.png">


<img width="358" alt="Screen Shot 2021-11-18 at 1 24 49 PM" src="https://user-images.githubusercontent.com/92389914/142666569-d9eda926-c49f-4c24-9fe2-9c2bfde81e52.png">

## Conclusion

Of the models i created more bathrooms, floors, and sqft living help to add value to a home but they also say adding bedrooms decrease the value so i have a model that needs more work. More factors like condition, grade,  need to be looked at to give a proper analysis and help price homes.

For More Information

Please review our full analysis in our Jupyter Notebook or our presentation.

For any additional questions, please contact Deja Prade - Deja.Prade@gmail.com
