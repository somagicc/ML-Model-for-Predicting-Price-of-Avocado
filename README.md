# ML Model for Predicting Price of Avocado
![](https://github.com/somagicc/ML-Model-for-Predicting-Price-of-Avocado/blob/master/Images/Intro.gif)

### Presentation
Watch the [presentation](https://drive.google.com/file/d/1G11gw0lnwCIIzq1qRoiwoe5-ALasy09I/view?usp=sharing/edit "presentation") giving the details of the project. 

### Video Presentation
You can also watch the elaborate [video ](https://www.youtube.com/watch?v=Aw30lqpZhNQ&t=2s "video ")presentation.

Or just continue here.
## Table of Contents
1. [Problem Statement](#section1)
2. [Attributes of Data](#section2)
3. [Exploratory Data Analysis](#section3)
4. [Pre-Processing Data](#section4)
5. [Algorithms Used](#section5)
6. [Python Notebook](#section6)
-------
<a id=section1></a>
## 1. Problem Statement
The goal is to build a model to predict the price of the avocadoes.


<a id=section2></a>
## 2. Attributes of Data
The provided data had atributes as shown below.

| Column Name      | Description                                                              |
| -------------    | -------------                                                           | 
| Unnamed: 0       | Index column                                                             | 
| Date             | The date of the observation                                              |  
| AveragePrice     | The average price of a single avocado                                    | 
| Type             | Conventional or organic                                                  |   
| Year             | The year                                                                 |
| Region           | The city or region of the observation                                    |
| Total Volume     | Total number of avocados sold                                            |
| 4046             | Total number of avocados with PLU 4046 sold (4046 – Hass – small)        |
| 4225             | Total number of avocados with PLU 4225 sold (4225 – Hass – large)        |
| 4770             | Total number of avocados with PLU 4770 sold (4770 – Hass Extra Large)    |                                 
| Total Bags       | Total number of bags of all sizes                                        |
| Small Bags       | Size of bag                                                              |
| Large Bags       | Size of bag                                                              |
| XLarge Bags      | Size of bag                                                              |


<a id=section3></a>
## 3. Exploratory Data Analysis

![](https://github.com/somagicc/ML-Model-for-Predicting-Price-of-Avocado/blob/master/Images/Average%20Price%20of%20Avocado%20Across%2054%20Countries.png)



![](https://github.com/somagicc/ML-Model-for-Predicting-Price-of-Avocado/blob/master/Images/Average%20Price%20of%20Avocado%20Across%20the%20Years%202015-2018.png)



![](https://github.com/somagicc/ML-Model-for-Predicting-Price-of-Avocado/blob/master/Images/Average%20Price%20of%20Avocado%20of%20Two%20Types.png)



![](https://github.com/somagicc/ML-Model-for-Predicting-Price-of-Avocado/blob/master/Images/Frequency%20of%20Each%20Type.png)



![](https://github.com/somagicc/ML-Model-for-Predicting-Price-of-Avocado/blob/master/Images/Frequency%20of%20Each%20Year.png)

<a id=section4></a>
## 4. Pre-Processing Data
Distribution of target variable, that is, price of an avocado is shown below.

![](https://github.com/somagicc/ML-Model-for-Predicting-Price-of-Avocado/blob/master/Images/Distribution%20of%20Target%20Variable.png)

Clearly, it is not normal. So after normalising it using log transformaion it looks like this.
![](https://github.com/somagicc/ML-Model-for-Predicting-Price-of-Avocado/blob/master/Images/Distribution%20of%20Target%20Variable%20after%20log%20transformation.png)


<a id=section5></a>
## 5. Algorithms Used
I used two algorithms and then compared them on the basis of different model evaluation metrics. Algorithms used are:
- Linear Regression
- Random Forest

### Model Evaluation Metrics Used
- RMSE

<a id=section6></a>
## 6. Python Notebook
Find all the codes [here.](https://github.com/somagicc/ML-Model-for-Predicting-Price-of-Avocado/blob/master/ML_Model_for_Predicting_Price_of_Avocado.ipynb "here")

Thank you!
