# Monte Carlo Integration Program in SageMath: An Academic Project

This repository is home to an academic project developed for a course in Numerical Methods. It contains a detailed SageMath program aimed at estimating the value of definite integrals through the Monte Carlo method. The Monte Carlo method is a statistical approach to mathematical computation based on random sampling techniques.

The project tackles a set of non-trivial mathematical functions, such as:

* f(x) = sqrt(1 - x^2),
* f(x) = x^2,
* f(x) = x^3,
* f(x) = 1/x,
* f(x) = sin(x),
* f(x) = 1/(1+x^2),
* f(x) = 1/sqrt(1-cos(x)),
* f(x) = 1/(x^2+1),
* f(x) = e^x/(1+e^x),
* f(x) = 1/sqrt(x).
These functions were chosen due to their complexity when it comes to analytical integration. The Monte Carlo method offers an alternative for obtaining numerical approximations of these integrals, bypassing the need for complicated analytical solutions.

The Monte Carlo method has an intriguing history. Its name stems from the Monte Carlo Casino in Monaco, as it essentially 'gambles' with random numbers to arrive at an outcome. Developed during the 1940s as part of the top-secret Manhattan Project, the Monte Carlo method was initially used to model neutron diffusion - a critical part of the design for the first atomic bomb. It was Stanislaw Ulam, a mathematician working on the project, who first realized the potential of random sampling for numerical computation. Nowadays, the method is widely used in fields as diverse as finance, physics, computer graphics, and, of course, numerical integration.

# How to Run
1. Install SageMath and required Python libraries if not already installed.

2. Clone this repository or download the .ipynb file.

3. Open the .ipynb file in SageMath.

4. Run the program. You can adjust the functions and their parameters as needed.

Please keep in mind, the more iterations you allow, the closer you'll get to the actual integral value. The beauty of the Monte Carlo method lies in its simplicity and the power of statistical sampling. Happy exploring!
