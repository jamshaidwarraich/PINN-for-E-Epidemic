This project implements a custom Physics-Informed Neural Network (PINN) framework using only TensorFlow and NumPy, targeting a completely different problem domain: the solution of ordinary differential equations (ODEs) governing the spread of an infectious disease. This framework is lightweight, fully customizable, and intended for use in mathematical modeling of epidemiological systems or other dynamic processes described by differential equations.

### Requirements
- Python >= 3.7  
- NumPy >= 1.18  
- TensorFlow >= 2.4.3 and <= 2.9.4  
- Matplotlib >= 3.1  
- SciPy >= 1.4

 ### Model Setup and Data Description
The initial conditions, training and validation data details, parameters values,time interval, and number of training epochs used in this implementation are all provided in the referenced paper [1]. These values were directly adopted from the study to ensure consistency with the original modeling approach.

### Data Preparation
The time points and corresponding synthetic data are converted to TensorFlow tensors with float32 precision before being passed to the model for training. This step ensures compatibility with TensorFlow operations during the optimization process.
