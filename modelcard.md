# Model Card

See the [example Google model cards](https://modelcards.withgoogle.com/model-reports) for inspiration. 

## Model Description

**Input:** Describe the inputs of your model 

Wine listing found at hedonism.co.uk

**Output:** Describe the output(s) of your model

We build a decision tree that predicts with high accuracy wether a wine is form Burgundy or not, without knowing the name of the wine.

**Model Architecture:** Describe the model architecture you’ve used

## Performance

Give a summary graph or metrics of how the model performs. Remember to include how you are measuring the performance and what data you analysed it on. 

Its super fast, just a decision tree.

## Limitations

Outline the limitations of your model.

Only focuses on Burgundy.

## Trade-offs

Outline any trade-offs of your model, such as any circumstances where the model exhibits performance issues. 

Overfitting is clear and we restricted tree depth to just very few criteria, however test set accuracy achieved is 84\%
