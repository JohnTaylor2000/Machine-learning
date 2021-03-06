# Machine-learning

Code that applies machine learning to science problems.

## Test-fit

Explore the **Universal Approximation Theorem** by fitting a range of functions using a neural network. **We also explore extrapolation** i.e. beyond the range of data used to fit the model. This is also known as the ability to generalise.

Here we demonstrate that a neural network has the potential to fit any function. **Examples use different functions of increasing complexity.**

We investigate extrapolation and the **role of the activation function in extrapolation**. You will find that the activation function largely determines the fit to extrapolations beyond the range of the training data. Note that interpolation between sparsely placed input data also increases the importance of the activation function.

**You can easily vary the number of layers and hidden units** to explore the role these play in training a model of increasing complexity.

The impact of key parameters on the computation time, such as the batch size and the number of hidden units can be investigated. For example, the batch size can be increased to match the Epoch size so that the optimisation is not stochastic.

Running with and without a GPU/TPU makes a big difference to training times. For example, you can explore the role of the GPU/TPU by running in a Google Colab. We also illustrate how you can add timers to code, in addition to what is currently available, that allow you to easily time any section of code.

## License

Apache License 2.0
