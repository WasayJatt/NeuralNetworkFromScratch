# Handwritten Digit Classification With Neural Network From Scratch

This project demonstrates the implementation of a simple neural network from scratch in Python for classifying handwritten digits using the MNIST dataset. It avoids using pre-built libraries like TensorFlow or PyTorch, offering a deeper understanding of how neural networks operate at the core level.

---

## Features

- Implementation of forward and backward propagation
- Activation functions such as ReLU and softmax
- Categorical cross-entropy loss
- Gradient descent optimization
- Evaluation metrics for accuracy

---

## Installation

To set up the project, follow these steps:

1. Clone the repository:

    ```bash
   git clone https://github.com/WasayJatt/NeuralNetworkFromScratch.git
    cd NeuralNetworkFromScratch
    ```

2. Install the required dependencies:

    ```bash
    pip install numpy matplotlib pandas 
    ```

---

## Usage

### Running the Project

1. Clone the repository if not already done:

    ```bash
   git clone https://github.com/WasayJatt/NeuralNetworkFromScratch.git
    cd NeuralNetworkFromScratch
    ```

2. Execute the script:

    ```bash
    python main.py
    ```

---

## Dataset

The project uses the MNIST dataset, a benchmark dataset for handwritten digit classification. It consists of:

- **Training Data**: 60,000 images (28x28 grayscale)
- **Testing Data**: 10,000 images (28x28 grayscale)

The dataset is automatically downloaded from `tensorflow.keras.datasets`.

---

## Example Output

Add a sample image or training visualization here (e.g., confusion matrix, accuracy vs. epochs graph, or sample predictions).

---

## Roadmap

- Enhance accuracy by tuning hyperparameters
- Add support for additional datasets
- Improve visualization features
- Implement a web interface for easy access
- Include transfer learning for performance enhancement

---

## License

This project is licensed under the **MIT License**. You are free to use, modify, and distribute this project, as long as proper credit is given to the author.

For more details, refer to the [LICENSE](./LICENSE) file.

---
