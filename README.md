# auto-MPG

### Can you predict the fuel-efficieny of a car?

---
![](images/tim-mossholder-680992-unsplash.jpg)


## ML+Dev Process

1. Pick a problem
2. Build a model
3. Wrap it in a simple API
4. Host it
5. Build a small app that uses it
6. Set-up a retraining pipeline
7. Set-up monitoring
8. Write about it

Source: https://twitter.com/svpino/status/1567482857182101504?s=20&t=xU_m28LKfrTUiR3MI5D79A

## Data



 **Column Position**|**Attribute Name**|**Description**                                             |**Examples**               |**Attribute Type**   |**Nulls Ratio**
|-------------------|------------------|------------------------------------------------------------|---------------------------|---------------------|----------------|
|     #1            |   mpg            |  fuel efficiency measured in miles per gallon (mpg)        | 9.0, 13.0, 41.5           | quantitative        | 0%             |
|     #2            |   cylinders      |  number of cylinders in the engine                         | 3, 4, 8                   | qualitative         | 0%             |
|     #3            |   displacement   |  engine displacement (in cubic inches)                     | 68.0, 112.0, 455.0        | quantitative        | 0%             |
|     #4            |   horsepower     |  engine horsepower                                         | 46.0, 70.0, 230.0         | quantitative        | 2%             |
|     #5            |   weight         |  vehicle weight (in pounds)                                | 1613, 3615, 5140          | quantitative        | 0%             |
|     #6            |   acceleration   |  time to accelerate from O to 60 mph (in seconds)          | 8.00, 15.50, 24.80        | quantitative        | 0%             |
|     #7            |   model year     |  model year                                                | 73, 79, 82                | qualitative         | 0%             |
|     #8            |   origin         |  origin of car (1: American, 2: European, 3: Japanese)     | 1, 2, 3                   | qualitative         | 0%             |
|     #9            |   car name       |  car name                                                  | audi fox, subaru          | qualitative         | 0%             |



Source: https://code.datasciencedojo.com/datasciencedojo/datasets/tree/master/Auto%20MPG

## Acknowledgement

This data set has been sourced from the Machine Learning Repository of University of California, Irvine [Auto MPG Data Set (UC Irvine)](https://archive.ics.uci.edu/ml/datasets/auto+mpg). The UCI page mentions [StatLib (Carnegie Mellon University)](http://lib.stat.cmu.edu/datasets/) as the original source of the data set.
