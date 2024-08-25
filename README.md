# Load-Flow-Analysis-using-Newton-Raphson-Method
This repository contains a Python implementation of load flow analysis using the Newton-Raphson method, one of the most widely used techniques in power system studies. 
Introduction
![Designer (12)](https://github.com/user-attachments/assets/5adba452-4530-45ae-94e6-babb74bd00d3)

Load flow analysis is essential for the planning, operation, and optimization of power systems. This project focuses on implementing the Newton-Raphson method in Python to calculate the steady-state voltages, angles, and power flows in a multi-bus power system. The method's robustness and efficiency make it a staple in power system studies.

Features
Newton-Raphson Load Flow Solver: Rapidly solves the power flow equations for a given power system network.
Customizable Bus and Line Data: Easily input and modify bus and transmission line parameters.
Convergence Check: Ensures the solution meets the desired accuracy.
Voltage Profile Visualization: Visualizes the voltage magnitudes across the buses using colorful pie charts.

Here I took an example of  3-bus system is provided in the repository, where you can observe how the Newton-Raphson method converges to the solution. The input data files define a simple network, and the resulting voltage profiles are visualized after running the analysis.

Visualization
Understanding the results is crucial in load flow analysis. This project includes a visualization tool that generates pie charts to represent the voltage profiles across different buses. The color-coded charts provide a clear and intuitive view of the voltage distribution in the power system.


Contributing
Contributions are welcome! If you have ideas for improving this project or want to add more features, feel free to fork the repository, make changes, and submit a pull request. Whether it's optimizing the code, fixing bugs, or enhancing the documentation, your input is valuable.
