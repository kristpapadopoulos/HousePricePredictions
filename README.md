## Follow the Trend

### An examination of lattice regression against lasso and random forest regression 

This [paper](https://github.com/kristpapadopoulos/HousePricePredictions/blob/master/CSC2515_Paper_Krist_Papadopoulos.pdf) includes experiments on the Boston Housing Dataset using the algorithms below to examine whether including linear biases such as prior assumptions of monotonicity between variables in lattice regression can improve performance of predictions by avoiding overfitting noise in the data:

1) Lasso Regression
2) Random Forest Regression
3) Lattice Regression: Calibrated Linear 1-D Lattice, Calibrated Lattice and Random Tiny Little Lattices [1]

The algorithms performance in terms of mean squared error were evaluated on the dataset with and without outliers.

The Lattice Regression algorithms tested; Calibrated Lattice and Random Tiny Little Lattices [1] were more effective than lasso and random forest regression in lower mean square error and lower standard deviation of predictions.

[1] Maya Gupta, Jan Pfeifer, Seungil You.  Tensorflow Lattice: Flexibility Empowered by Prior Knowledge.  Google Research Blog, 2017.  URL  https://research.googleblog.com/2017/10/tensorflow-lattice-flexibility.html

