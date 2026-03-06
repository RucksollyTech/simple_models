The linear models fit perfectly well with nn.Linear

The non_Linear_model still didn't fit even after introducing non linearity to it with ReLU.
Turns out the model was trying to extrapolate due to the training data.

So shuffling the data made the model learn 