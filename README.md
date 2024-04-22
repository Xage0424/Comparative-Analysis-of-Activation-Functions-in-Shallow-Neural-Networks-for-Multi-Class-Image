#  [ Ongoing Project ]
Note: Training the Models with the Chosen Activation Function on the Hidden Layer in Each Independent Environment or Colab Notebook

# Initial Work Plan:
# Concept/Idea:
Comparisons of how different chosen activation functions perform/behave and affects on a shallow neural network performances with constant architectural parameters in each dataset for multi-class image classification like MNIST Digits and CIFAR-10 using the selected evaluation metrics.

# Initial Shallow NN Architecture to be used:
1. MNIST Handwritten Digits
- Input Layer: 28,28,1
- Hidden Layer: 32
- Dropout Layer: 0.1
- Hidden Layer: 64
- Dropout Layer: 0.1
- Output Layer: 10
  
2. CIFAR-10
- Input Layer: 32,32,3
- Hidden Layer: 
- Dropout Layer: 0.1
- Hidden Layer: 
- Dropout Layer: 0.1
- Output Layer: 10

# Image Datasets to be used:
1. MNIST Handwritten Digits (Grayscale)
2. CIFAR-10 (RGB)

# Different Activation Functions for the Hidden Layer to be used:
Baseline: ReLu (Rectified Linear Unit)
1. Leaky ReLu
2. ELU (Exponential Linear Unit)
3. SELU (Scaled Exponential Linear Unit)
4. Swish
5. PreLu (Parametric ReLu)
6. Mish
7. Sigmoid
8. Tanh
9. Maxout

# Activation Function for the Output Layer:
1. Softmax

# Optimizer, Loss Function & Possible Evaluation Metrics to be used:
# Optimizer:
1. Adam (Adaptive Moment Estimation)

# Loss Function:
1. Categorical Cross Entropy

# Evaluation Metrics:
1. Accuracy
2. Loss
3. Confusion Matrix
4. Precision
5. Recall
6. F1 Score

# Additional/Possible Evaluation Techniques to be used:
1. Cross Validation like K-Fold
2. Statistical Analysis techniques
