# Neural Network from Scratch with NumPy

This repository demonstrates how to build a **neural network from the ground up** using only Python and NumPy.  
It is designed as an educational project to show the inner workings of forward propagation, backward propagation, cost computation, and parameter updates without relying on deep learning frameworks such as TensorFlow or PyTorch.

## ✨ Features
- Implementation of **forward propagation** and **backward propagation**
- Activation functions: **ReLU** and **Sigmoid**
- **Mean Squared Error (MSE)** cost function
- Training loop with weight and bias updates
- Example dataset (Age, Height, Name, Score) for prediction tasks
- Clear, modular code structure for learning and experimentation

## 📂 Project Structure
- `data.py` → sample dataset
- `forward_propagation.py` → forward pass logic
- `backward_propagation.py` → gradient calculations
- `train.py` → training loop
- `utils.py` → activation functions and derivatives

## 🚀 Getting Started
Clone the repository and run the training script:

```bash
git clone https://github.com/your-username/neural-network-from-scratch.git
cd neural-network-from-scratch
python train.py

📊 Output

During training, the loss value is printed to the console so you can observe the learning process. After training, the model can be used to make predictions on new data.
🎯 Purpose

This project is intended for educational purposes. It helps beginners understand how neural networks work internally and provides a foundation for exploring more advanced machine learning frameworks.

