# Feedforward Neural Network using Flux.jl

This project demonstrates how to build a simple feedforward neural network using [Flux.jl](https://fluxml.ai/) in Julia. The model is applied to the Iris dataset and aims to showcase the core components of building, training, and evaluating a neural network using Julia's deep learning ecosystem.

## Overview

The project includes:
- Data loading and preprocessing (normalization, train/test split)
- Model architecture using `Chain` and `Dense` layers
- Training using `ADAM` optimizer and `crossentropy` loss
- Evaluation of model performance on the test set
- Visualization of loss during training

## Technologies Used

- Julia 1.9+
- Flux.jl
- MLDatasets.jl
- Statistics.jl
- Plots.jl

## Project Structure

```

Feedforward-Neural-Network-Julia/
│
├── Feedforward_Neural_Network.ipynb   # Main notebook with code and explanations
├── README.md                  # Project description and instructions

````

## Features

- Fully connected neural network implementation
- ReLU and softmax activation functions
- Tracks loss over epochs
- Evaluates classification accuracy
- Simple and understandable code structure for beginners

## How to Run

1. Install [Julia](https://julialang.org/downloads)
2. Open the notebook in JupyterLab, Jupyter Notebook, or Kaggle
3. Install the required Julia packages:

```julia
using Pkg
Pkg.add("Flux")
Pkg.add("MLDatasets")
Pkg.add("Statistics")
Pkg.add("Plots")
````

4. Execute all cells in sequence

## Results

* Achieves high accuracy on Iris dataset
* Loss curve visualized using Plots.jl
* Suggestions for future improvements included

## Future Improvements

* Add confusion matrix for performance analysis
* Test deeper architectures and other optimizers
* Apply the model to different datasets (e.g., MNIST)

## Author

Umair – BS Artificial Intelligence Student
This project was developed as part of an academic assignment to understand neural network implementation in Julia.

## License

This project is licensed under the MIT License.
