# MultilayerPerceptron in VHDL

# Perceptron
<p>
  <img align="center" src="https://github.com/RLR-GitHub/MultilayerPerceptron/blob/master/images/perceptron.PNG" />
</p>

# Training Diagram
<img align="center" src="https://github.com/RLR-GitHub/MultilayerPerceptron/blob/master/images/training_diagram.png" >

# Testing Diagram
<img src="https://github.com/RLR-GitHub/MultilayerPerceptron/blob/master/images/testing_diagram.png" >

# Testing Diagram
![Perceptron](https://github.com/RLR-GitHub/MultilayerPerceptron/blob/master/images/testing_diagram.png)

# Equations
### Sigmoid Activation 
<img src="https://render.githubusercontent.com/render/math?math=y = \frac{1}{{1} \dagger {\e}^{ -x }}"> 

### Delta 
<img src="https://render.githubusercontent.com/render/math?math=\delta_k = ( d_k - y_k ) y_k ( 1 - y_k ) "> *for k = 1,2,...,K*

### Weight Matrix: W 
<img src="https://render.githubusercontent.com/render/math?math=\triangle{W_{kj}} = \rho \delta_k z_j"> *for j = 1,2,...,J*

### Weight Matrix: V
<img src="https://render.githubusercontent.com/render/math?math=\triangle{V_{ji}} = \rho z_j ( 1 - z_j ) x_i \sum_{k=1}^{\K} (\delta_k w_{kj})"> *for j = 1,2,...,J and i = 1,2,...,n*

### Updated Weight Matrix: W 
<img src="https://render.githubusercontent.com/render/math?math={W_{kj}}^{t\'} = {w_{kj}}^{t} + \triangle{w_{kj}}"> 

### Updated Weight Matrix: V
<img src="https://render.githubusercontent.com/render/math?math={V_{ji}}^{t\'} = {v_{ji}}^{t} + \triangle{v_{ji}}"> 


# Python Implementation 

## Python Training Results
<p align="center">
  <img width="500" height="500" src="https://github.com/RLR-GitHub/MultilayerPerceptron/blob/master/images/training_result_matrices.PNG">
</p>


## Python Testing Results
<p align="center">
  <img width="500" height="500" src="https://github.com/RLR-GitHub/MultilayerPerceptron/blob/master/images/testing_result_matrices.PNG">
</p>

<p align = "left"></p>

##

# VHDL Implementation
## VHDL Training Results
![Training](https://github.com/RLR-GitHub/MultilayerPerceptron/blob/master/images/actual.PNG)

## VHDL Testing Results
![Testing](https://github.com/RLR-GitHub/MultilayerPerceptron/blob/master/images/target.PNG)
