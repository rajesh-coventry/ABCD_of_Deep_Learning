# **ABCD of Deep Learning:**

Welcome to **ABCD of Deep Learning**, a foundational educational series designed to bridge the gap between biological intuition and the mathematical formalism of early neural networks. 

This repository explores the historical and conceptual evolution of Deep Learning, starting from the biological inspiration of the 1940s to the mathematical rigor of the Perceptron in the 1990s. It serves as a comprehensive "Chapter 0" for anyone wishing to understand the *why* and *how* behind modern Artificial Intelligence.

## **🧠 Project Goal:**

The primary goal of this series is to demystify the core components of a neuron without jumping straight into complex libraries or black-box implementations. We build the understanding from the ground up:
1.  **Biological Roots:** How biological neurons invoke the idea of artificial ones.

2.  **Learning Rules:** How early scientists thought machines could "learn" (Hebbian, Oja, Delta rules).

3.  **The Perceptron:** The first true learning machine, dissecting its mathematics, geometry, and limitations.

## **📚 Curriculum Structure:**

The content is organized sequentially to guide the learner through the evolution of these ideas.

| Sequence | Topic | Description |
| :--- | :--- | :--- |
| **00** | **Core Ideas** | Overview of the mental model: from biological signals to mathematical error correction. |
| **01** | **Biological Motivation** | Understanding Neuroplasticity and the biological neuron (Dendrites, Soma, Axon). |
| **02** | **Early Models** | The McCulloch-Pitts neuron and early attempts to model logic mathematically. |
| **03** | **Hebbian Learning** | "Neurons that fire together, wire together" — the correlation-based learning rule. |
| **04** | **Oja’s Rule** | Stabilizing Hebbian learning to prevent weight explosion. |
| **05** | **Delta & LMS Rules** | The shift from correlation to **error-correction** and the birth of Gradient Descent intuition. |
| **06** | **Linear Classifiers** | Understanding classification, decision boundaries, and linear separability. |
| **07** | **The Artificial Neuron** | Formalizing the elements: Inputs, Weights, Bias, and Activation Functions. |
| **08** | **Linear Mathematics** | The geometry of linear combinations and the equation of a line/hyperplane. |
| **09** | **Dimensions** | Visualizing perceptrons in higher-dimensional spaces. |
| **10** | **Perceptron Learning** | The complete **Perceptron Learning Algorithm (PLA)**, including loss functions and weight updates. |
| **11-12**| **Vectorization** | Implementing the forward pass using modern PyTorch-style matrix operations and batching. |
| **13** | **Next Steps** | A conclusion connecting these foundations to modern Deep Learning training. |

## **📐 Mathematical Focus:**

This project places a heavy emphasis on the **mathematics** essentially required to truly understand Neural Networks:
- **Linear Algebra:** Dot products, vector spaces, hyperplanes, and matrix multiplication mechanics ($Y = X @ W^T$).

- **Calculus:** The intuition of gradients and minimization of loss functions.

- **Optimization:** Gradient Descent and the geometric interpretation of weight updates.

- **Techniques:** Bias Augmentation (treating bias as a weight) and Vectorization for efficiency.

## **🚀 Further Learning:**

This module concludes at the **`Perceptron`**. While the Perceptron creates the foundation, it has limitations (e.g., the XOR problem) that necessitated the development of Multi-Layer Perceptrons (MLPs) and Backpropagation.

For the continuation of this journey into training Deep Neural Networks, please refer to the follow-up series:
> **[100 Days of Deep Learning](https://github.com/rajesh-coventry/100-Days-of-Deep-Learning)**