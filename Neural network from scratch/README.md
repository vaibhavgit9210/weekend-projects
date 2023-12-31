# Simple MNIST NN from Scratch

**This notebook demonstrates how to build a neural network from scratch to classify handwritten digits using the MNIST dataset. It's designed for educational purposes, emphasizing the underlying math and implementation details.**

## Inspiration and Resources:

This implementation is heavily inspired by the excellent YouTube tutorial by Samson Zhang: [https://www.youtube.com/watch?v=w8yWXqWQYmU&list=WL&index=5]. I strongly recommend watching his video for a more comprehensive explanation of the concepts and the code.

**Key Features:**

- **Two-layer neural network:** Explores a simple architecture with an input layer, a hidden layer with ReLU activation, and an output layer with softmax activation.
- **Detailed math explanation:** Includes clear explanations of forward propagation, backward propagation, and parameter updates, accompanied by equations and visualizations.
- **Step-by-step implementation:** Guides you through the code implementation, covering data loading, model definition, training loop, and evaluation.
- **Accuracy evaluation:** Demonstrates how to assess model performance on both training and development sets.
- **Visualization of predictions:** Provides examples of digit predictions along with their corresponding images.

**Contents:**

1. **Data Loading and Preprocessing:**
   - Loads the MNIST dataset from a CSV file.
   - Splits the data into training and development sets.
   - Normalizes pixel values to [0, 1].

2. **Neural Network Architecture:**
   - Defines a two-layer neural network with ReLU and softmax activations.
   - Initializes model parameters with random weights and biases.

3. **Forward Propagation:**
   - Calculates the activations of each layer, from input to output.
   - Applies ReLU activation in the hidden layer and softmax activation in the output layer.

4. **Backward Propagation:**
   - Computes gradients of the loss function with respect to model parameters.
   - Uses the chain rule to propagate errors backward through the network.

5. **Parameter Updates:**
   - Updates weights and biases using gradient descent to minimize the loss.

6. **Training Loop:**
   - Iterates through multiple epochs of training.
   - Performs forward propagation, backward propagation, and parameter updates in each epoch.
   - Monitors training accuracy and prints updates periodically.

7. **Evaluation:**
   - Measures accuracy on both training and development sets.
   - Visualizes predictions on sample images to assess model performance qualitatively.

**To run the notebook:**

1. Download the MNIST dataset from [https://www.kaggle.com/datasets/zalando-research/fashionmnist](https://www.kaggle.com/datasets/zalando-research/fashionmnist)
2. Place the dataset in the appropriate directory.
3. Install required libraries: `numpy`, `pandas`, `matplotlib`.
4. Execute the code cells in the notebook sequentially.

**Disclaimer:**

This notebook is intended for educational purposes and does not claim originality. It adapts and builds upon the concepts and code presented in the aforementioned YouTube tutorial. I highly encourage viewers to explore the original source for deeper understanding and further learning.
