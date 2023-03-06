# Linear Regression:

## Introduction :

- 1. For Linear regression (or) specifically, for any supervised machine Learning Algorithm we must requires two things:

     - **a) Feature variables/independent variables/predictor variables**, these are like regular variables which are attributes of labels.

      - **b) Target variables/Dependent variables/class lables**, it is like a "Source of Truth" - use for learning a pattern (or) giving knowlegde/information about the variables to the Algorithm.

    for example, Iris dataset having independent variables ['sepal Length', 'sepal width', 'petal length', 'petal width'] and, dependent variables (or) class labels ['Iris setosa', 'Iris Versicolor', 'Iris virginia']
    <br><br>

  ![](./images/1_iris_example.png)


  - 2. Linear Regression consists of predictor variable and dependent variable related linearly to each other. These can be expressed in terms of a straight line and we can find out the relationship between independent variable and dependent variable.

  <center><span style="font-size:32px;"> y = mx + c </span></center> 
<center><span style="font-size:16px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;( it's a line equation )</span></center></br>

where y is the line, m is the slope, c is the y-intercept.

but in Linear Regression,

 <center><span style="font-size:32px;">Y = θ<sub>0</sub> + θ<sub>1</sub>X +  ε </span></center> </br>

where,

θ<sub>0</sub> :  is the y-intercept (or) c

θ<sub>1</sub> : is the slope (or) m

ε : is the random error (or) noise.

- Linear Regression also knowns as <span style="font-family: Fantasy;">ordinary least squares (OLS)</span> and <span style="font-family: Fantasy;">linear least squares.</span>
