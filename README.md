# Simple Neural Network in PyTorch  

This repository contains a basic implementation of a simple neural network using PyTorch. The model consists of one hidden layer and an output layer, both using the **tanh** activation function.

## Features  
- Built using **PyTorch**  
- A **fully connected neural network** with one hidden layer  
- **Weight initialization** with uniform distribution  
- **Bias initialization** with constant values  

## Code Overview  
The script defines a neural network class **`FirstNN`** that inherits from `torch.nn.Module`. The model structure includes:  
- **Input layer:** 2 neurons  
- **Hidden layer:** 2 neurons with `tanh` activation  
- **Output layer:** 1 neuron with `tanh` activation  

### Model Initialization  
- Weights are initialized **randomly** in the range `[-0.5, 0.5]`.  
- Biases are initialized to **0.5** for the hidden layer and **0.7** for the output layer.  

### Forward Pass  
The forward method applies **tanh activation** to both the hidden and output layers.  

## Usage  
To run the script, install PyTorch if not already installed:  
```bash
pip install torch
```
Then, execute the Python script:  
```bash
python script.py
```

## Example Output  
When you run the script, it will print the output of the neural network for an input tensor `[0.5, 0.5]`:  
```
Neural Network Result: <some_value>
```

## Author  
Developed by **Khaled Zakaria**  

---
This is a simple example to demonstrate neural network construction using PyTorch. Feel free to modify and extend it for your needs! 🚀  
