# Task 3: Recognizing Handwritten Numbers (10p)

## a. Why are 784 layers appropriate for the input layer? (2p)

### Explanation:

- Each MNIST image is 28x28 pixels, which when flattened becomes a 784-dimensional vector.

### Chapter to Read:

#### Chapter 6: Deep Feedforward Networks

- Section 6.4: Architecture Design (Explanation on how to design network layers)

## b. Why are 10 layers appropriate for the output layer? Are there other options? (3p)

### Explanation:

- The MNIST dataset has 10 classes (digits 0-9), so the output layer has 10 neurons, each representing a class.
- Alternative options could include using different encoding schemes but one-hot encoding is standard for classification tasks.

### Chapter to Read:

#### Chapter 5: Machine Learning Basics

- Section 5.1: Learning Algorithms (Classification and regression tasks)

#### Chapter 6: Deep Feedforward Networks

- Section 6.4: Architecture Design

## c. Run a backpropagation algorithm on a smaller subset of the 60,000 examples and try to find reasonable values for the learning rate as well as the size of the hidden layer. (3p)

### Steps:

#### Subset Selection:
- Select a smaller subset for initial experimentation, e.g., 1000 or 10000 examples.

#### Network Initialization:
- Define the architecture with 784 input neurons, N hidden neurons (experiment with different sizes), and 10 output neurons.

#### Hyperparameter Tuning:
- Experiment with different learning rates and hidden layer sizes.

### Chapters to Read:

#### Chapter 4: Numerical Computation
- Section 4.3: Gradient-Based Optimization (Understanding the optimization process)

#### Chapter 5: Machine Learning Basics
- Section 5.9: Stochastic Gradient Descent (Details on training using SGD)

#### Chapter 6: Deep Feedforward Networks
- Section 6.5: Back-Propagation and Other Differentiation Algorithms (Details on backpropagation)

#### Chapter 11: Practical Methodology
- Section 11.4: Selecting Hyperparameters

## d. Run the backpropagation algorithm on the entire dataset, how well is it performing?

### Steps:

#### Full Training:
- Train the neural network on the entire MNIST dataset (60,000 examples) using the best hyperparameters found in the previous step.

#### Evaluation:
- Evaluate the performance using the test set (usually a separate 10,000 examples).
- Metrics to consider: accuracy, precision, recall, F1-score, confusion matrix.

### Chapters to Read:

#### Chapter 8: Optimization for Training Deep Models
- Section 8.2: Challenges in Neural Network Optimization
- Section 8.3: Basic Algorithms (Strategies for effective training)

#### Chapter 11: Practical Methodology
- Section 11.1: Performance Metrics (How to evaluate model performance)

## Summary of Chapters and Sections Aligned with Tasks

### Data Preparation:
- Chapters 5 and 11

### Network Initialization and Mathematical Foundations:
- Chapter 2: Linear Algebra
- Chapter 4: Numerical Computation

### Forward Propagation:
- Chapter 6: Deep Feedforward Networks

### Loss Calculation:
- Chapter 3: Probability and Information Theory
- Chapter 6: Deep Feedforward Networks

### Backward Propagation:
- Chapter 6: Deep Feedforward Networks

### Training Loop:
- Chapter 8: Optimization for Training Deep Models

### Regularization:
-Chapter 7: Regularization for Deep Learning

### Practical Tips:
- Chapter 11: Practical Methodology
By focusing on these chapters and sections, you will gain a deep understanding of the theoretical concepts and practical methodologies needed to successfully implement and train a neural network from scratch to recognize handwritten digits. If you have any further questions or need additional guidance on specific sections, feel free to ask!