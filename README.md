# mobile_phone_classification

## problem statement
Bob has started his own mobile company. He wants to give tough fight to big companies like Apple,Samsung etc.

He does not know how to estimate price of mobiles his company creates. In this competitive mobile phone market you cannot simply assume things. To solve this problem he collects sales data of mobile phones of various companies. The dataset collected has the following features

- battery_power: Total energy a battery can store in one time measured in mAh
- blue: Has bluetooth or not
- clock_speed: speed at which microprocessor executes instructions
- dual_sim: Has dual sim support or not
- fc: Front Camera mega pixels
- four_g: Has 4G or not
- int_memory: Internal Memory in Gigabytes
- m_dep: Mobile Depth in cm
- mobile_wt: Weight of mobile phone
- n_cores: Number of cores of processor
- pc: Primary Camera mega pixels
- px_height: Pixel Resolution Height
- px_width:Pixel Resolution Width
- ram: Random Access Memory in Mega Bytes
- sc_h: Screen Height of mobile in cm
- sc_w: Screen Width of mobile in cm
- talk_time: longest time that a single battery charge will last when you are
- three_g: Has 3G or not
- touch_screen: Has touch screen or no
- wifi: Has wifi or not
- price_range: This is the target variable with value of 0(low cost), 1(medium cost), 2(high cost) and 3(very high cost).

## objective
The objective of this project is to build a model that can predict the price range of phones based on data collected

## info
The first notebook contains the baseline model using the logistic regression algorithm which had an accuracy score of about 95.6 percent despite minimal preprocessing being carried out

The second notebook contains code for preprocessing the data a little bit more than the first notebook and training using a decision tree classifier which actually gave a slightly worse accuracy score of approximately 85 percent 

## conclusion
The baseline model which had an accuracy of 95.6 percent would be selected and deployed using streamlit and heroku  

The data for this project was gotten from https://www.kaggle.com/iabhishekofficial/mobile-price-classification?select=train.csv
