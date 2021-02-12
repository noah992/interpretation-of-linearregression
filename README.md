# interpretation-of-linearregression

* [Code](https://github.com/noah992/interpretation-of-linearregression/blob/main/code/interpretation-of-linearregression.ipynb)
* [Dataset](https://github.com/noah992/interpretation-of-linearregression/blob/main/data/orange_juice.csv)


## Summary

* Objective
* Modeling
* Interpretation


## Objective

This repo is built for an explanation of interpretaion of a model.
I made an [article](https://noah992.medium.com/how-to-interpret-a-linearregression-model-data-science-26ba4440a1a1) to demonstrate how to interpret a model. This repo contains a dataset and code for the article.


## Modeling
I used below data to predict prices of orange juice with `LinearRegression`

#### Data dictionary
|Column|Type|Description|
|-|-|-|
|price|int|price of orange juices|
|weight|int|weight of each orange juice|
|season|str|season when each orange juice was sold|

#### Result
|Column|Coefficient|
|-|-|
|weight|0.014|
|season_Spring|-1.014|
|season_Summer|3.057|
|season_Winter|-1.855|


## Interpretation

For `weight`
> For each increase of weight unit, we can expect the price is increased by $0.014 holding all other features consistent

For `season_Summer`
> We can expect price of the orange juice in Summer is $3.05 higher than its price in Fall holding all other features consistent
