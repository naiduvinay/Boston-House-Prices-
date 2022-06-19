# Boston-House-Prices-
Regression Project
# Boston House Prices

A regression project for predicting the prices(MEDV: Median value of owner-occupied homes in $1000s) of houses.


## Description of the features
Each record in the database describes a Boston suburb or town. The data was drawn from the Boston Standard Metropolitan Statistical Area (SMSA) in 1970. The attributes are deﬁned as follows (taken from the UCI Machine Learning Repository1):

CRIM: per capita crime rate by town

ZN: proportion of residential land zoned for lots over 25,000 sq.ft.

INDUS: proportion of non-retail business acres per town

CHAS: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)

NOX: nitric oxides concentration (parts per 10 million

RM: average number of rooms per dwelling

AGE: proportion of owner-occupied units built prior to 1940

DIS: weighted distances to ﬁve Boston employment centers

RAD: index of accessibility to radial highways

TAX: full-value property-tax rate per $10,000

PTRATIO: pupil-teacher ratio by town

B: 1000(Bk−0.63)2 where Bk is the proportion of blacks by town

LSTAT: % lower status of the population

MEDV: Median value of owner-occupied homes in $1,000.

## Model Results

LR:  R2 = 0.6986730544969698, std = 0.10370110391452685\
LASSO: R2 = -0.04199384837104778, std = 0.03473033831013379\
Ridge: R2 = 0.6992668493596584, std = 0.10372360405571503\
DT: R2 = 0.7678187463695689, std = 0.07372595117913171\
RF: R2 = 0.8622928113144404, std = 0.06440107256262281\
SVR: R2 = 0.8148957729611517, std = 0.10286320319914544\
XGB: R2 = 0.8877842026204892, std = 0.027276775246207686
 
