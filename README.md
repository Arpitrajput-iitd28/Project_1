Winter Project 2024

Traditional machine learning models often fail to accurately model damped oscillatory systems, as they rely purely on data without accounting for underlying physical laws. This project uses Physics-Informed Neural Networks (PINNs) to integrate differential equations directly into the loss function, enabling better predictions for damped simple harmonic motion (SHM).

To simulate the dynamics of a damped harmonic oscillator using a PINN, ensuring the model:
Honors the governing physical differential equation
Accurately models decay in amplitude due to damping
Respects initial conditions (e.g., x(0) = 1, x′(0) = 0)

Implementation Highlights
Built using PyTorch
Defines a fully connected feedforward neural network for approximating x(t)
Loss = combination of:
Physics residual (how well the network satisfies the differential equation)
Initial condition loss
Visualization of predicted vs analytical solution

Results
Model accurately captures damping
No artificial perpetual oscillations
Predicts motion over time consistent with physics-based expectations

👤 Author
Arpit Rajput
Machine Learning Winter Project – 2025
Indian Institute of Technology Delhi




