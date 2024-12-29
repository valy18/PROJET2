# Deep Learning Framework from Scratch

This project implements a deep learning framework entirely from scratch without using popular libraries like PyTorch or TensorFlow. The goal was to write all necessary functions to build and train neural networks, ensuring a deeper understanding of the underlying principles.

---

## Features
- Implementation of neural network layers (e.g., Dense, Activation functions).
- Forward and backward propagation.
- Gradient computation and optimization algorithms.
- Training and evaluation loops.

---

## Getting Started

### Prerequisites
To run the code, make sure you have Python installed along with the following libraries:

```bash
pip install numpy matplotlib
```

### Installation
1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the project directory:
   ```bash
   cd ScratchRn
   ```

### Usage
1. Open the `noteBook.ipynb` file in Jupyter Notebook or your preferred editor.
2. Run the cells step by step to understand the framework.
3. Modify the architecture or parameters in the notebook as needed.

---

## Project Structure

- **noteBook.ipynb**: Contains the full implementation of the framework with explanations and usage examples.
- **utils/**: (Optional) Placeholder for utility scripts if separated from the notebook.
- **README.md**: Project documentation.

---

## Implementation Details

### Neural Network Components
The framework includes the following:
1. **Activation Functions**: Sigmoid, ReLU, and Softmax.
2. **Loss Functions**: Mean Squared Error (MSE) and Cross-Entropy Loss.
3. **Optimization**: Gradient Descent.

### Training Workflow
1. Initialize the model.
2. Define the loss function and optimizer.
3. Train the model over multiple epochs, computing gradients manually.

---

## Results
Performance metrics and visualizations are available in the notebook. Training accuracy and loss trends are plotted using Matplotlib.

---

## Contributing
Contributions are welcome! If you'd like to improve this project, feel free to submit a pull request.

---

## License
This project is licensed under the MIT License.

---


