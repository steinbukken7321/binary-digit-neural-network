# Binary Digit Neural Network

A pure Python and NumPy implementation of a **Feedforward Neural Network** designed to recognize digits (0-9) represented in a 5x6 binary grid. This project demonstrates the core mathematical concepts of machine learning, including backpropagation and gradient descent, without relying on high-level frameworks like TensorFlow or PyTorch.

## 🚀 Features

* **From-Scratch Implementation**: Sigmoid activation, Feedforward, and Backpropagation logic built using NumPy.
* **Interactive UI**: Uses `ipywidgets` to allow manual bit manipulation and real-time testing.
* **Performance Analysis**: Built-in plotting for accuracy and loss curves across different learning rates.
* **Noise Testing**: Tools to flip random bits and evaluate model robustness against corrupted data.

## 🛠️ Requirements

To run this notebook, you will need:

* Python 3.x
* NumPy
* Matplotlib
* IPython / Jupyter Widgets

## 📖 How to Use

1. **Clone the Repository**:
```bash
git clone https://github.com/YOUR_USERNAME/binary-digit-neural-network.git
cd binary-digit-neural-network

```


2. **Open the Environment**:
Upload the `.py` or `.ipynb` file to **Google Colab** or run it locally using **Jupyter Notebook**.
3. **Train the Model**:
* Run the initialization cells to load the binary dataset.
* Execute the training cell. You can adjust the `Learning_rate` and `epochs` parameters in the `train()` function.


4. **Test and Interact**:
* **Existing Data**: Use the dropdown to see how the model classifies the original training set.
* **Manual Input**: Use the interactive 5x6 grid to toggle bits (0 or 1) and click "Gerar e Testar Rede" to see the model's prediction in real-time.
* **Noise Test**: Use the "Bits a alterar" field to flip random bits and see at what point the model begins to fail.



## 📊 Hyperparameters

The project includes a dedicated section to compare different Learning Rates (, , , etc.), helping you visualize how the step size affects the convergence of the loss function.

---
