# TensorFlow framework (without Keras) to develop a multi-class classification problem on the MNIST handwritten digits dataset.
1. We built the architecture by custom defining the neural network class. Here, we use GradientTape to record operations for automatic differentiation. Firstly, we consider building a fully connected neural network with 2 hidden layers (no regularization) and measure the performance.

We also separately have written another (second) script for the same, but, this time including the Keras commands and, -

	1. We build the same network as before.
	2. We then add regularization and compare the difference between L2 and Dropout.
	3. lastly, we add a few CNN layers and see if we can improve the model's performance further.  
