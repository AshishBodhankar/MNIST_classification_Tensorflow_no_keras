# TensorFlow framework (without Keras) to develop a multi-class classification problem on the MNIST handwritten digits dataset.
1. We build the architecture by custom defining the neural network class. Here, we use GradientTape to record operations for automatic differentiation. We first build a fully connectd neural network with 2 hidden layers (no regularization) and measure the performance.

We also separately have written a script for the same but this time including Keras commands and
	1. We build the same network as before.
	2. We then add regularization and compare the difference between L2 and Dropout.
	3. lastly, we add a few CNN layers and see if we can improve the model's performance further.  
