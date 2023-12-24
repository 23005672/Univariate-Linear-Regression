# Implementation of Univariate Linear Regression
## Aim:
To implement univariate Linear Regression to fit a straight line using least squares.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the independent variable X and dependent variable Y.
2.	Calculate the mean of the X -values and the mean of the Y -values.
3.	Find the slope m of the line of best fit using the formula.
 <img width="226" alt="eq1" src="https://github.com/23005672/Univariate-Linear-Regression/assets/138971519/e31dc8c8-1e4a-4b4a-87d7-5076caa4581d">

4.	Compute the y -intercept of the line by using the formula:
 <img width="143" alt="eq2" src="https://github.com/23005672/Univariate-Linear-Regression/assets/138971519/1d2db998-73f8-400d-ba7a-5c3731ce48f2">
 
5.	Use the slope m and the y -intercept to form the equation of the line.
6.	Obtain the straight line equation Y=mX+b and plot the scatterplot.
## Program
```PYTHON
##Developed by : RIYA P L
##Register no : 23005672

import numpy as np
import matplotlib.pyplot as plt
x=np.array(eval(input()))
y=np.array(eval(()))
xmean=np.mean(x)
ymean=np.mean(y)
num,den=0,0
for i in range(len(x)):
    num+=(x[i]-xmean)*(y[i]-mean)
    den+=(x[i]-xmean)**2
m=num/den
c=ymean-m*xmean
print(m,c)
y_pred=m*x+c
print(y_pred)
plt.scatter(x,y)
plt.plot(x,y_pred,color='red')
plt.show()






```
## Output
<img width="405" alt="univariate" src="https://github.com/23005672/Univariate-Linear-Regression/assets/138971519/e8bd8ac3-62e8-4e5e-85d3-18186f5d4234">


## Result
Thus the univariate Linear Regression was implemented to fit a straight line using least squares.
