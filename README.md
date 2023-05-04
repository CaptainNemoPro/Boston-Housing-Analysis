# Boston-Housing-Analysis

![alt text](https://media.istockphoto.com/vectors/set-of-wide-panoramas-the-urban-landscape-vector-id623205168?k=6&m=623205168&s=612x612&w=0&h=Kk5W6LY5WHz2BOP-4Z7aaMlVAL2AHAP95iIv5Ibegoc=)

Greetings and welcome to the Boston housing exploratory data analysis and modeling. We hope that you find this work beneficial in some way.

# About Dataset

This dataset give a blow by blow account of the housing conditions in Boston, a city located in the United States of America. The dataset considers various housing parameters as the availability of radical highways which can ease the transportation. The proportion of black in the locality, the student teacher ratio, crime rate and details about the number of employment centers is also been given. This is just a soundbite of the information that the dataset contains. For you ease here are all the variable along with their meanings.

1.CRIM - per capita crime rate by town

2.ZN - proportion of residential land zoned for lots over 25,000 sq.ft.

3.INDUS - proportion of non-retail business acres per town.

4.CHAS - Charles River dummy variable (1 if tract bounds river; 0 otherwise)

5.NOX - nitric oxides concentration (parts per 10 million)

6.RM - average number of rooms per dwelling

7.AGE - proportion of owner-occupied units built prior to 1940

8.DIS - weighted distances to five Boston employment centres

9.RAD - index of accessibility to radial highways

10.TAX - full-value property-tax rate per 10,000

11.PTRATIO - pupil-teacher ratio by town

12.B - 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town

13.LSTAT - % lower status of the population

14.MEDV - Median value of owner-occupied homes in $1000's

# Ideal user of this project.

![alt text](https://th.bing.com/th/id/OIP.fvsFLYPKm6H6LR7l9NstlgHaFj?pid=ImgDet&rs=1)

1. The appropriate user for this would be the authorities responsible for public welfare in Boston, as they can utilize the provided visualizations and valuable insights to prompt them to take appropriate actions towards improving housing facilities and ultimately enhance them.

2. Additionally, individuals interested in real estate and investments could also benefit from this, as it provides an understanding of the current state of housing conditions in Boston.

# Insights

![alt text](https://th.bing.com/th/id/OIP.kdCIsn5Yd62N39BDos6PiQHaFj?pid=ImgDet&rs=1)

1. In areas where the distance to employment centers is within 2-3km, the proportion of black residents varies, with some areas having a lower and others a higher concentration of black residents.

2. Areas farther from employment centers tend to have better air quality due to lower nitrogen oxide concentration compared to those closer to employment centers.

3. The population with a lower-class percentage between 10% and 36% is responsible for the majority of crimes.

4. The index of accessibility to radial highways varies greatly among different areas, with some having an index below 5 and others close to 25, indicating regional disparities.

5. The pupil-teacher ratio in most suburbs falls between 17 and 22, with a peak around 20, but some schools have significantly higher ratios, which may indicate underfunding or overcrowding.

6. Affordable housing is available in all areas regardless of air quality, while expensive housing is only found in areas where the air quality falls within an acceptable range, specifically between 0.4 and 0.65.

7. Areas with a high pupil-teacher ratio tend to have a higher crime rate than those with a lower pupil-teacher ratio.

8. The distribution of median home values in suburbs is roughly bell-shaped, with most suburbs having median home values between 10,000 and 40,000.

# Multiple linear regression model.

![alt text](https://miro.medium.com/max/2872/1*k2bLmeYIG7z7dCyxADedhQ.png)

Multiple linear regression is a statistical technique used to examine the relationship between a dependent variable and two or more independent variables. It is a linear approach to modeling the relationship between a dependent variable and several explanatory variables, often called predictors or covariates.

Using all the other variables in the dataset as input, I have developed a model that can forecast the median value of owner-occupied houses.


