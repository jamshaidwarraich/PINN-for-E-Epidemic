This project implements a Physics-Informed Neural Network (PINN) in TensorFlow to solve a system of ordinary differential equations (ODEs) that
models the spread of a virus across four compartments: Susceptible (S), Infectious Stage 1 (I1), Infectious Stage 2 (I2), and Recovered (R).
#Model Description
The ODE system describes the flow between the compartments using parameters such as infection rate, recovery rate, and natural death rates. The dynamics are defined in the system_ode function.

The PINN model is trained using synthetic data generated from this ODE system using scipy.integrate.odeint.
##Section 1 – Model Training and Result Generation
This section contain the PINN implementation and generates the prediction plots.
##Physics and Data Loss Code
This section gives the plot for physics and data loss.
##Statistical Analysis
This section plots the comaprison of PINN with ground truth by using different evaluation metrices.
The hyperparameters for the training this network are given in the paper.
