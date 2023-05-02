# Boston-housing-EDA-modelling.

![alt text](https://live.staticflickr.com/1957/43555391580_ea8259a894_b.jpg)

Welcome to the boston housing EDA and modelling. Hope this work can be of some use to you.

# About the dataset.

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

# Who would be an ideal user of this project.

![alt text](https://th.bing.com/th/id/OIP.NfQXJGQIFEdceeyi1sIW8AHaHa?pid=ImgDet&rs=1)

1.The authorities in charge of looking after the public welfare in Boston would be an apropos user. This can use such visualizations and valuable insights which can urge the authorities in charge to take appropriate action to provide better housing facilities and eventually improve on it.

2. This may also be used by any person will to go into real eatate and investments, who wants to understand the present case scenario of the housing conditions in Boston.

# Insights

![alt text](https://th.bing.com/th/id/OIP.fz5lzLbQT2ir0Vzmn0L0wAHaE7?pid=ImgDet&rs=1)

>Some key insights have been mentioned from the visualization made in the ipynb file. I would suggest to first have a look at that file before jumping into this one.

1.Areas where the distance to the employment centers is less in this case 2-3km , the proportion of blacks in those areas is diverse meaning that in some of these areas the proportion of blacks are less and in some other areas it is more. This can only be seem when the distance is between 2-3 km.

2.Areas which are at a distance from the employment centers have better air quality since they have a lower concentration of nitrogen oxides than the areas which are closer to the employment centers.

3.Most of the crimes are committed by the population where the percentage of lower class is between 10% to 36%.

4. there are some where the index of accessibility to radial highways is below 5, on the other hand there are some areas where index of accessibility to radial highways is close to 25. This indicates the regional disparity among the areas.

5.Majority of suburbs have a pupil-teacher ratio between 17 and 22, with a peak around 20. There are some outliers with much higher pupil-teacher ratios, which could represent underfunded or overcrowded schools

6.cheap houses are available every where irrespective of the air quality of that area. But the expensice houses are only occupied in areas where the air quality is under the acceptable range in this case between o.4 to 0.65.

7.areas with high pupil teacher ratio have a higher crime rate than the areas with lower pupil teacher ratio.

8.The distribution of median home values is roughly bell-shaped, with most suburbs having median home values between  10,000𝑎𝑛𝑑
 40,000.

# Multiple linear regression model.

I have also made a model to predict the median valus of owner occupied homes, by taking all the other variables in the dataset as input.

#Ending note:

Thanks for giving this a read. For detailed visualizations and coding you can refer to the ipynb files if you wish so.