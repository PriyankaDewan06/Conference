# Conference
### Logistic Regression
Logistic regression is a statistical method that is used for building machine learning models where the dependent variable is dichotomous: i.e. binary. Logistic regression is used to describe data and the relationship between one dependent variable and one or more independent variables. The independent variables can be nominal, ordinal, or of interval type.

The name “logistic regression” is derived from the concept of the logistic function that it uses. The logistic function is also known as the sigmoid function. The value of this logistic function lies between zero and one.

### How Does the Logistic Regression Algorithm Work?
Consider the following example: An organization wants to determine an employee’s salary increase based on their performance.

For this purpose, a linear regression algorithm will help them decide. Plotting a regression line by considering the employee’s performance as the independent variable, and the salary increase as the dependent variable will make their task easier.


![image](https://user-images.githubusercontent.com/71719225/163659854-f9739a66-e8af-4e9c-819a-747554f16ddd.png)

Now, what if the organization wants to know whether an employee would get a promotion or not based on their performance? The above linear graph won’t be suitable in this case. As such, we clip the line at zero and one, and convert it into a sigmoid curve (S curve).

![image](https://user-images.githubusercontent.com/71719225/163659935-ff6ce3b9-43d1-494b-92eb-cf57006be864.png)



Based on the threshold values, the organization can decide whether an employee will get a salary increase or not.

To understand logistic regression, let’s go over the odds of success.

Odds (𝜃) = Probability of an event happening / Probability of an event not happening

𝜃 = p / 1 - p

The values of odds range from zero to ∞ and the values of probability lies between zero and one.

Consider the equation of a straight line: 

𝑦 = 𝛽0 + 𝛽1* 𝑥

![image](https://user-images.githubusercontent.com/71719225/163659952-754d2678-98dd-4274-936e-13eb25cb03d7.png)


Here, 𝛽0 is the y-intercept

𝛽1 is the slope of the line

x is the value of the x coordinate

y is the value of the prediction

Now to predict the odds of success, we use the following formula:

log

Exponentiating both the sides, we have:

et-y

Let Y = e 𝛽0+𝛽1 * 𝑥

Then p(x) / 1 - p(x) = Y

p(x) = Y(1 - p(x))

p(x) = Y - Y(p(x))

p(x) + Y(p(x)) = Y

p(x)(1+Y) = Y

p(x) = Y / 1+Y

px

The equation of the sigmoid function is:



The sigmoid curve obtained from the above equation is as follows:

![image](https://user-images.githubusercontent.com/71719225/163659963-f271108f-b420-4d51-b3b9-627375400084.png)



