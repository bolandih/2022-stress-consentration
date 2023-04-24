# Stress Consentration
## Deep learning paradigm for prediction of stress distribution in damaged structural components with stress concentrations
[Paper](https://www.sciencedirect.com/science/article/pii/S0965997822001430)

#### Authors: [Hamed Bolandi](https://bolandih.github.io/), Xuyang Li, Talal Salem Vishnu Boddeti, Nizar Lajnef

### Abstract
Scientists and engineers agree that solving complex problems requires integrating traditional physics-based
modeling techniques with state-of-the-art deep learning (DL) methods. This paper aims to integrate physics
knowledge into a convolutional neural network (CNN) to boost learning within a feasible solution space in
a specific domain. Our proposed method uses deep neural networks in the form of (CNNs) augmented with
custom loss functions which uses physics rules to bypass the need for Finite Element Analysis and predict
high-resolution stress distributions on damaged steel plates with variable loading and boundary conditions. We
embedded physics constraints into the loss function to enforce the model training, precisely capturing stress
concentrations around the tips of various structural damage configurations. The CNN was designed and trained
to use the geometry, boundary conditions, and load as input and predict the stress contours. The proposed
framework’s performance is compared to Finite-Element simulations using partial differential equation (PDE)
solver. The trained DL model can predict the stress distributions of damaged steel plates with a mean absolute error of 0.22% percent and an absolute peak error of 1.5% for the Von Mises stress distribution.

### Overview figure
![2nd paper](https://user-images.githubusercontent.com/78941477/234071864-f1b4b5a7-11c7-421d-904e-7b72b50a413e.png)

### Comparisson of model with physics informed loss function (Phy loss) and non-physics informed loss function (MSE loss)
![MSE-Phy](https://user-images.githubusercontent.com/78941477/234072594-5e31ca2d-2c43-44b2-af04-607d9b0e0b35.png)

