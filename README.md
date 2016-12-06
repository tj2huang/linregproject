# linregproject

Linear regression project for Stat 331.

"The dataset strikes_clean.csv contains information on strike activity in 18 countries be- longing to the Organization for Economic Co-operation and Development (OECD), during the postwar period 1951-1985."


We attempt to fit a linear regression model to predict strike activity in various countries. A preliminary look at the data indicates that there is a multiplicative relationship going on, hence we apply a log transformation to the strike activity response variable. We identify several interpretable main effects and interpretable interactions using a series of F-tests in order to come up with one candidate model. We find a second candidate model through backward selection. A comparison of residuals, leverage, influence, and cross-validation SSE leads us to determine that the models share similar flaws, while having very minor differences in predictive power. We thus pick the first model which is significantly more interpretable, and see that Country is the most important factor affecting strike activity. We also find that several of the assumptions of linear regression are violated, such as constant variance of errors and randomness of response, but come to the realization that a model that is not perfect can still be useful.
