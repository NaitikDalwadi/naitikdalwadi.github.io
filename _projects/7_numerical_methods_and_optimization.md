---
name: Optimization of Compressor Performance
tools: [Python, spotoptim, spotPython, scipy.optim, Scikit-learn, Pandas, Numpy]
image: https://naitikdalwadi.github.io/assets/images/performance.png
description: 
---

# Optimization of Compressor Performance

This project aims to optimize the performance of the compressor using classical optimization methods and surrogate model based methods. For this project, 3 datasets were given contain mass flowrate and pressure ratio data at different compressor rotor speeds. These 3 datasets have different level of measurement noise. For classical optimization approach, following methods were implemented:
- Nelder-Mead                   
- Powell                        
- TNC
- L-BFGS-B
These methods were used in combination with 3 different error metrics used to fit the curve to the measured data points. First, these different combinations were run on the dataset which has the highest measurement noise and evaluated with both measured pressure ratio and mass flow rate data. Based on the result, the intersection of the top 5 combinations in both quantity were chosen. However, the error value for the Nelder-Mead and L-BFGS-B with Ortho metric were same. To see more clear difference, *number of iterations* metric was used, and L-BFGS-B with Ortho metric is the suitable combination,   

![Classical optimization approach](/assets/images/optim_task_1.png)

## Problem Statement



## My Role


## Achievement/Recognition


<p class="text-center">
{% include elements/button.html link="https://www.youtube.com/watch?v=d-sza2mzV4o" text="Working Video" %}
</p>