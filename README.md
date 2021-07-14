# Machine-Learning-Model-for-Weather-Forecasting
Purpose of this project is to predict the temperature using different algorithms like linear regression, random forest regression, and Decision tree regression. The output value should be numerically based on multiple extra factors like maximum temperature, minimum temperature, cloud cover, humidity, and sun hours in a day, precipitation, pressure and wind speed.

# USE OF ALGORITHMS: 

There are different methods of foreseeing temperature utilizing Regression and a variety of Functional Regression, in which datasets are utilized to play out the counts and investigation. To Train, the calculations 80% size of information is utilized and 20% size of information is named as a Test set. For Example, if we need to anticipate the temperature of Kanpur, India utilizing these Machine Learning calculations, we will utilize 8 Years of information to prepare the calculations and 2 years of information as a Test dataset. The as opposed to Weather Forecasting utilizing Machine Learning Algorithms which depends essentially on reenactment dependent on Physics and Differential Equations, Artificial Intelligence is additionally utilized for foreseeing temperature: which incorporates models, for example, Linear regression, Decision tree regression, Random forest regression. To finish up, Machine Learning has enormously changed the worldview of Weather estimating with high precision and predictivity. What's more, in the following couple of years greater progression will be made utilizing these advances to precisely foresee the climate to avoid catastrophes like typhoons, Tornados, and Thunderstorms.

# METHODOLOGY

The dataset utilized in this arrangement has been gathered from Kaggle which is “Historical Weather Data for Indian Cities” from which we have chosen the data for “Kanpur City”. The dataset was created by keeping in mind the necessity of such historical weather data in the community. The datasets for the top 8 Indian cities as per the population. The dataset was used with the help of the worldweatheronline.com API and the wwo_hist package. The datasets contain hourly weather data from 01-01-2009 to 01-01-2020. The data of each city is for more than 10 years. This data can be used to visualize the change in data due to global warming or can be used to predict the weather for upcoming days, weeks, months, seasons, etc.
Note: The data was extracted with the help of worldweatheronline.com API and we cannot guarantee the accuracy of the data.
The main target of this dataset can be used to predict the weather for the next day or week with huge amounts of data provided in the dataset. Furthermore, this data can also be used to make visualization which would help to understand the impact of global warming over the various aspects of the weather like precipitation, humidity, temperature, etc. 

In this project, we are concentrating on the temperature prediction of Kanpur city with the help of various machine learning algorithms and various regressions. By applying various regressions on the historical weather dataset of Kanpur city we are predicting the temperature like first we are applying Multiple Linear regression, then Decision Tree regression, and after that, we are applying Random Forest Regression.

Historical Weather Dataset of Kanpur City:
![image](https://user-images.githubusercontent.com/52596651/125589083-a7755810-3748-4087-a412-5b69301a7c20.png)
Plot for each factor for 10 years
![image](https://user-images.githubusercontent.com/52596651/125589135-ae1bb587-359c-4230-827d-c04f79619f9a.png)
Plot for each factor for 1 year
![image](https://user-images.githubusercontent.com/52596651/125589162-07544c53-1553-4970-a7ae-603e85743cec.png)

![image](https://user-images.githubusercontent.com/52596651/125589327-8dfe449d-edda-4d8e-b61d-f24bc32fb656.png)

# Multiple Linear Regression: 
This regression model has high mean absolute error, hence turned out to be the least accurate model. Given below is a snapshot of the actual result from the project implementation of multiple linear regression. 
 ![image](https://user-images.githubusercontent.com/52596651/125589488-ccf7afe4-25a5-4f86-be31-fed1e77a75bb.png)

# Decision Tree Regression: 
This regression model has medium mean absolute error, hence turned out to be the little accurate model. Given below is a snapshot of the actual result from the project implementation of multiple linear regression. 
![image](https://user-images.githubusercontent.com/52596651/125589533-3e4493cc-875f-4308-8900-ec5a96a9781c.png)


# Random Forest Regression: 
This regression model has low mean absolute error, hence turned out to be the more accurate model. Given below is a snapshot of the actual result from the project implementation of multiple linear regression. 
![image](https://user-images.githubusercontent.com/52596651/125589563-082ac697-da74-40ac-81d6-08ecb51f766a.png)


