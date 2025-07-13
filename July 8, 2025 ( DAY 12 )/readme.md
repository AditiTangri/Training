# ARTIFICIAL INTELLIGENCE AND MACHINE LEARNING  
**DAY - 12**

**Date**: 8 July 2025

---

## Neural Network

Neural networks are **machine learning models** that mimic the structure and function of the **human brain**. They are composed of interconnected nodes (neurons) and are designed to learn from data, recognize patterns, and perform tasks like classification, prediction, and decision-making.

---

### Key Components of a Neural Network

- **Neurons**: Basic units of computation that receive inputs and produce outputs using activation functions.
- **Connections**: Links between neurons, where data flows; each connection has a **weight** and **bias**.
- **Weights & Biases**: Parameters that determine how strongly an input influences a neuron.
- **Propagation Function**: Governs how signals move between layers.
- **Learning Rule**: Updates the weights and biases based on error correction during training.

---

### Learning Process

1. **Input Computation**: Data enters the input layer.
2. **Output Generation**: The model makes a prediction using current weights and biases.
3. **Iterative Refinement**: Weights and biases are updated to minimize prediction error.

---

## Importance of Neural Networks

Neural networks are key in solving complex problems and powering technologies like:

- Natural Language Processing (NLP)
- Autonomous Vehicles
- Medical Diagnosis Systems
- Recommendation Engines

They are the foundation of **modern AI** due to their ability to handle high-dimensional and unstructured data.

---

## Layers in Neural Network Architecture

1. **Input Layer**: Receives raw input data (each neuron = 1 input feature).
2. **Hidden Layers**: Perform the bulk of computation. May be multiple layers deep.
3. **Output Layer**: Produces final predictions (e.g., class labels or numeric values).

---

## Forward Propagation

**Forward propagation** is the process of calculating the output of a neural network:

1. **Linear Transformation**:  
   Each neuron in a layer receives inputs which are multiplied by the weights associated with the connections. These products are summed together and a bias is added to the sum. 

2. **Activation Function**:  
   The result of the linear transformation (denoted as z) is then passed through an activation function. The activation function is crucial because it introduces non-linearity into the system, enabling the network to learn more complex patterns. Popular activation functions include ReLU, sigmoid and tanh.

 This process continues layer-by-layer until the final output is generated.

---

## Backward Propagation (Backpropagation)

**Backpropagation** is the phase where the network *learns* by adjusting weights and biases:

1. **Loss Calculation**:  
   Compare prediction vs. actual using a **loss function**:
   - Mean Squared Error (MSE)
   - Cross Entropy

2. **Gradient Computation**:  
   Use **chain rule of calculus** to compute the contribution of each weight to the error.

3. **Weight Update**:  
   Apply optimization algorithm to minimize error.

 This process repeats over many **epochs** until the model converges to optimal performance.


> Neural Networks are the heart of deep learning systems and a cornerstone in building smart, adaptive AI models.



**By**  : Aditi Tangri

**URN**  : 2302460  

**CRN**  : 2315004
