# CJR
CJR project
The learned logistic regression coefficients are *[0.39, -0.51, 2.56, 1.01], with a bias term of **0.43*. Since all features were standardized, the magnitude and sign of each coefficient directly represent its relative influence on the probability of predicting the positive class.

The *third feature (2.56)* has the strongest positive impact, indicating that increases in this feature substantially raise the likelihood of the positive outcome. The *fourth feature (1.01)* also contributes positively but with a more moderate effect. The *first feature (0.39)* has a smaller positive influence on the predicted probability. In contrast, the *second feature (-0.51)* negatively affects the prediction, meaning higher values of this feature reduce the probability of belonging to the positive class.

Overall, the model demonstrates meaningful feature separation and interpretability, aligning with the expected behavior of logistic regression in binary classification tasks.
