---
layout: post
title: "Deep Learning"
date: 2024-05-08
excerpt: "Implementation of neural networks and reinforcement learning algorithms in Python."
tags: [Python, Deep Learning, Neural Networks]
comments: true
project: true
---

### Deep Learning

#### Neural Networks
- Implemented fully connected and convolutional neural networks.
- Developed and trained one-stage (FCOS) and two-stage (Faster R-CNN, integrating a Region Proposal Network) object detectors.
- Created image captioning models using RNN, LSTM, and Transformer networks with spatial attention.
- Implemented generative adversarial networks, network visualization techniques to create saliency maps, and style transfer.

#### Control Strategies
- Implemented an iterative linear quadratic regulator (iLQR) for inverted double-pendulum swing-up on a cart.
- Developed shooting and collocation methods for finite horizon Linear Quadratic Regulation (LQR) with input constraints.
- Applied MPPI for cartpole swing-up, optimizing nonlinear trajectories and achieving stable pole-up configurations.

#### Reinforcement Learning
- Designed reward functions for robotic manipulation, optimizing task success rates in obstacle-free and obstacle-present environments.
- Created a Variational Autoencoder (VAE) and applied Gaussian Process regression using GPyTorch with various kernels to model noisy data with uncertainty.

#### Robotics
- Implemented an A-star path planning algorithm for collision-free paths in 2D environments.
- Developed Euler and Velocity Verlet integrators, a PID controller, and a simple pendulum simulation.
- Built forward and inverse kinematics algorithms for 3D robot configurations.
- Designed collision-free motion planning using RRT, RRT*, and RRT-Connect algorithms.
