# Single Perceptron
<p>
  <img align="center" src="https://github.com/RLR-GitHub/MultilayerPerceptron/blob/master/images/perceptron.PNG" />
</p>

# Training Diagram
<img align="center" src="https://github.com/RLR-GitHub/MultilayerPerceptron/blob/master/images/training_diagram.png" >

# Testing Diagram
<p align="center">
  <img width="750" src="https://github.com/RLR-GitHub/MultilayerPerceptron/blob/master/images/testing_diagram.png" >
</p>

# Equations
### Sigmoid Activation
$$
y = \frac{1}{1 + e^{-x}}
$$

### Delta
$$
\delta_k = (d_k - y_k) \, y_k \, (1 - y_k)
$$

*for \( k = 1,2,...,K \)*

### Weight Matrix: \( W \)
$$
\Delta W_{kj} = \rho \, \delta_k \, z_j
$$

*for \( j = 1,2,...,J \)*

### Weight Matrix: \( V \)
$$
\Delta V_{ji} = \rho \, z_j (1 - z_j) \, x_i \sum_{k=1}^{K} (\delta_k w_{kj})
$$

*for \( j = 1,2,...,J \) and \( i = 1,2,...,n \)*

### Updated Weight Matrix: \( W \)
$$
W_{kj}^{t'} = w_{kj}^{t} + \Delta w_{kj}
$$

### Updated Weight Matrix: \( V \)
$$
V_{ji}^{t'} = v_{ji}^{t} + \Delta v_{ji}
$$

## Python Training Results

<p align="center">
  <img width="300" src="https://github.com/RLR-GitHub/MultilayerPerceptron/blob/master/images/training_result_matrices.PNG">
</p>


## Python Testing Results

<p align="center">
  <img width="300" src="https://github.com/RLR-GitHub/MultilayerPerceptron/blob/master/images/testing_result_matrices.PNG">
</p>

## VHDL Training Results

<p align = "center">
    <img width="500" src="https://github.com/RLR-GitHub/MultilayerPerceptron/blob/master/images/actual.PNG">
</p>

## VHDL Testing Results

<p align = "center">
    <img width="500" src="https://github.com/RLR-GitHub/MultilayerPerceptron/blob/master/images/target.PNG">
</p>
