# Debug-Challenge
Fixed bugs in logistic regression notebook

Debug Challenge – Answers

1. What was the bug?
The main issues were that y_test was generated as boolean values instead of integers, the learning rate was too high, and the cost function was numerically unstable due to log(0).

2. How did you identify it?
I identified the bug by observing unstable loss values and checking the datatype of y_test. I also noticed that the learning rate was too large and that the cost function could produce NaN values.

3. Why did it cause the specific problem?
Boolean labels caused incorrect accuracy calculations, the high learning rate caused gradient descent to diverge, and log(0) produced numerical errors, leading to unstable training.

4. What learning rate worked best?
0.01

5. What accuracy did you achieve?
Train: ~55%
Test: ~50%



Nupur
