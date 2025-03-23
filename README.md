# PINN
This repo is for my final project about Physics-Informed Neural Networks for Deep Generative Modeling course.

Project Title:
Physics-Informed Neural Networks for Predicting River Water Depth and Velocities Using the Saint-Venant Equations

This project employs a machine learning framework using a state-of-the-art physics-informed neural network (PINN) to enhance the spatial resolution of large-scale hydrodynamic models and simulate fluid dynamics more accurately at the river-ocean interface. The study focuses on applying PINNs to directly solve the one-dimensional Saint-Venant equations and integrate various types of data like outputs of a HEC-RAS model, remote sensing data, and observed data, aiming to improve the accuracy of flood prediction models.

Coastal areas are prone to compound flooding triggered by high river discharge and storm surges during severe weather events. This project leverages physics-informed neural networks (PINNs) to address the inadequacies of traditional hydrodynamic models, integrating physical laws into the learning process to provide a more precise simulation of flood dynamics.

The model uses a deep neural network (DNN) configured with five hidden layers to simulate the river flow dynamics, predicting water depth and velocity based on spatial and temporal data. Custom loss functions are defined to combine residuals of the partial differential equations with observational data, ensuring the model adheres closely to physical laws. To refine predictions, the model integrates data from large-scale models, remote sensing snapshots, and in-situ measurements.

I used the one-dimensional Saint-Venant equations for modeling water flow, incorporating continuity and momentum equations that describe the dynamics of water movement within a river channel.

The PINN model demonstrates significant improvements in predicting water depths compared to traditional methods, with detailed analysis of the model's performance using metrics like the relative L2 error and RMSE.
？