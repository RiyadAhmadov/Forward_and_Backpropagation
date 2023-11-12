# Forward and Backpropagation

![Manual Backpropagation](https://i0.wp.com/neptune.ai/wp-content/uploads/2022/10/Backpropagation-passes-architecture.png?resize=434%2C414&ssl=1)

Forward and backward propagation are essential steps in training artificial neural networks, a key component of machine learning. These processes are fundamental to updating the model parameters (weights and biases) based on the observed errors during training. Let's explore each process:

### Forward Propagation:

1. **Input Layer:**
   - The process begins with the input layer, where the model receives the input features.

2. **Weighted Sum and Activation:**
   - Each neuron in a hidden layer computes a weighted sum of its inputs, where weights are the model parameters.
   - The weighted sum is then passed through an activation function, introducing non-linearity.

3. **Propagation through Hidden Layers:**
   - The weighted sums and activations are propagated through subsequent hidden layers.

4. **Output Layer:**
   - Similar computations are performed in the output layer, and the final output of the network is generated.

5. **Loss Calculation:**
   - The predicted output is compared with the actual target values using a loss (cost) function.

### Backward Propagation (Backpropagation):

1. **Gradient Descent:**
   - Backpropagation involves the minimization of the loss by adjusting the model parameters (weights and biases).
   - The gradient of the loss with respect to each model parameter is computed using the chain rule of calculus.

2. **Update Parameters:**
   - The model parameters are updated in the opposite direction of the gradient, aiming to minimize the loss.
   - Learning rate determines the step size during this optimization process.

3. **Propagation of Gradients:**
   - Gradients are propagated backward through the network, updating weights and biases in hidden layers.

4. **Iterative Process:**
   - Forward and backward propagation are repeated iteratively over batches of training data to optimize the model.

### Summary:

- **Forward propagation** involves passing input through the network to compute predictions.
- **Backward propagation** is responsible for computing gradients and updating model parameters to minimize the loss.

## Contact

For questions or feedback regarding this README or Backpropagation, please contact *Riyad* at *riyadehmedov03@gmail.com*.
