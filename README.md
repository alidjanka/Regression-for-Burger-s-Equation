# Regression-for-Burgers-Equation

In this notebook, you will have to design simple feedforward neural network that can solve another regression task. To do that, you will use directly the tensorflow layer and you will need to explore a bit the different loss and activation function of tensorflow.
The dataset comes from a solution of the Burgers' equation which is a simplification of the Navier Stokes equation:

\begin{equation}
    \frac{\partial u}{\partial t} + u\frac{\partial u}{\partial x} = \nu \frac{\partial^2 u}{\partial x^2}
\end{equation}
with $\nu=0.01/\pi$. While non-chaotic, the Burgers equation display can exhibit some basic features of turbulence such as the development of shock-like interface.
