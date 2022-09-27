# POWER_CONSUMPTION analysis
> ** This is a data science project that takes past 3 years electricity consumption data to analyze for patterns and predict future usage**

<img align="center" alt="Coding" width="400" src="https://ec.europa.eu/eurostat/documents/4187653/9806083/Energy+consumption+in+EU+households">
## The goal
Is to create a machine learning model that can learn to predict power consumption in advance so as the companies gets an idea of the demand and strategize themselfs accordingly

## ABOUT THE DATASET
**"usage" dataset** ->  contains record of consumption of power in KWH and date-time stamp
**"weather" dataset** -> contains detils about the weather on that specific datetime such   
- temprature
- due
- wind speed
- humidity (min/max/avg)
**Data was extracted from the kaggle datasets**                                                                                            
                                                                                            
**LIBRARIES/TOOLS USED**-> 
- Numpy
- Pandas
- Seaborn 
- Matplotlib
- Sklearn
- Keras


## About Project
1. A combined data was used so as to extract all corelation between atmosphere and power condition as well as the dependence on time feature like the -what time of day it is -day of the week -week of the year -month of the year
2. Some data visualization were used to find out the corellations and dependance of target of different fetures
3. Corellation with various date-time elements were discovered(i.e- sudden increase in conumption at specific day of the week )
4. Then finally the model was first  trained using the random forest regressor then a neural network is built with batch normalisation and dropout layers(with total (20 - 8 - 10) layers) were also used in the network so as check for same task but this tie with neural network to find out which type suits the data best
5. Comparing both we picked up best model to train on  the data set then created the final 
6. Least error we got from the dataset was 0.179 that is about 83% accuracy
