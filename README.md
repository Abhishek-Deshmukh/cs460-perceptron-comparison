# CS460 perceptron comparison

[Dataset](https://archive.ics.uci.edu/ml/datasets/Solar+Flare) is about
predicting flares from the sun in the coming 24 hrs based on observation in the
previous 24 hrs.

The dataset has data about the number of flares of different types, to convert
the problem into binary classification (and also because there were too many
zeros in it), I transformed it a yes/no asking weather there were any flares.

![Plot representing the difference in accuracy depending on type of perceptron
per epoch](./Epoch_vs_accuracy.png)

In the above plot we can see that the Averaged Perceptron is consistent and
more accurate over epochs compared to a vanilla perceptron.
