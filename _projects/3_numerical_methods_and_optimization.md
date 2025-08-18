---
name: Optimization of Compressor Performance
tools: [Python, spotoptim, spotPython, scipy.optim, Scikit-learn, Pandas, Numpy]
image: https://naitikdalwadi.github.io/assets/images/performance.png
description:  It aims to find the optimal parameters of the Llamas model that computes speed lines for measured data of the pressure ratio and mass flowrate. This project also compares the classical optimization methods and surrogate-model based methods.
---

# Optimization of Compressor Performance

## Problem Statement

Determine the optimal coefficients for a mathematical model of the compressor performance map. Additionally, address the following questions:

- Which configurations(optimization algorithm, error metric, boundary conditions) work and why?
- What metrices should we use?
- Which algorithm is the best?
- Which algorithm is the most efficient?

## Summary

This project aims to optimize compressor performance using both classical optimization methods and surrogate model–based approaches. For this purpose, three datasets were provided, containing mass flow rate and pressure ratio data at different compressor rotor speeds. These datasets represent varying level of measurement noise.

In the classical optimization approach, the following methods were implemented:
- Nelder-Mead
- Powell
- TNC
- L-BFGS-B

These methods were applied in combination with three different error metrics to fit curves to the measured data points. Initially, all combinations were tested on the dataset with the highest measurement noise and evaluated against both measured pressure ratio and mass flow rate data. Based on the results, the intersection of the top five combinations for both quantities was selected. However, the error values for the Nelder-Mead and L-BFGS-B methods with the Ortho metric were identical. To achieve a clearer distinction, the number of iterations metric was considered, which identified L-BFGS-B with the Ortho metric as the most suitable combination.  

![Classical optimization approach](/assets/images/no_of_iterations_optim_1.png)
![speed line fit](/assets/images/speed_line_optim_1.png)

For surrogate-model based approach, the following methods were implemented:
- Differential Evolution
- Dual Annealing
- Direct

Initially, these methods were tested on the dataset with the least measurement noise and evaluated against both the measured pressure ratio and mass flow rate data. The rationale for selecting the dataset with minimal noise was to assess the performance of the surrogate models. If these models demonstrated good accuracy and computational efficiency, the same methods could then be applied to the other datasets. The optimized &beta; parameters obtained from the classical approach were used as the starting point for the surrogate model–based methods. Based on the results, the differential evolution method showed the best performance. In this approach, the fun_eval and init_size hyperparameters were utilized to enhance the efficiency of the algorithm.

![Surrogate-model based approach](/assets/images/optim_task_2.png)

## More Details

- [Jupyter Notebook and Report](https://github.com/NaitikDalwadi/Numerical_Methods_and_Optimization)