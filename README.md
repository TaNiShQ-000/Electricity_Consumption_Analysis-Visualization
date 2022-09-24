# POWER_CONSUMPTION analysis
**data science project that analyse the dataset for patterns and predict future values**

**ABOUT THE DATASET**- "usage" dataset contains record of consumption of power in KWH and date-time stamp "weather" dataset contains detils about the weather on that specific datetime such -> temprature, due , wind speed, humidity (min/max/avg)

**LIBRARIES/TOOLS USED**-> numpy, pandas ,seaborn ,matplotlib , sklearn

-> a combined data was used so as to extract all corelation between atmosphere and power condition as well as the dependence on time feature like the -what time of day it is -day of the week -week of the year -month of the year
-> some data visualization were used to find out the corellations and dependance of target of different fetures
-> then finally the model was first  trained using the random forest regressor then a neural network is built with batch normalisation and dropout layers(with total (20*8*10) layers) were also used in the network so as check for same task but this tie with neural network to find out which type suits the data best
->comparing both we picked up best model to train on  the data set then created the final 
