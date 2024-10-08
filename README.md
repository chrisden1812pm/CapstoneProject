# CapstoneProject : Machine Blind Tasting

We source an excel file from the website of a luxury wine shop in London called Hedonism and situated on Davies St. just off Berkeley square. The objective is to detect in the listing, based on just a few criteria, whether a bottle is from Burgundy or not. Country is an allowed criterion, which reduces the spectrum of investigation. However nothing in the name of the wine can be used to arrive at our conclusion.


## DATA
A summary of the data you’re using, remembering to include where you got it and any relevant citations. 

We've used minimally post-processed data as an input to our model. We had to deal with semicolon separators in our csv and also with commas in the description of the wines.

## MODEL 
A summary of the model you’re using and why you chose it. 

We use a simple decision tree, and inspect the results in order to mitigate the obvious overfitting.

## HYPERPARAMETER OPTIMSATION
Description of which hyperparameters you have and how you chose to optimise them. 

Tree depth is the hyperparameter and we iterated through tree depth, a kind of grid search if you will. No Bayesian optimisation was required as calculations run super fast. 

## RESULTS
A summary of your results and what you can learn from your model 

The resulting tree is very shallow and very few criteria are needed to figure whether a listed wine is from Burgundy or not with 84\%+ accuracy, namely country and price.

