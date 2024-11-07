# Generating MNIST digits using GAN

This is a simple implementation of Generative Adversarial Networks (GAN) for generating MNIST digits.

![step_80000](images/step-80000.png)

I use simple BCE loss function for calculating the loss and Adam optimizer (lr=0.0001) for training.

read the notebook online:

## Architecture

- The **generator** is series of Linear layers with BatchNorm and ReLU activations.
- The **discriminator** is a series of Linear layers with BatchNorm andLeakyReLU activations.

## Training History

![losses_plot](images/losses.png)

## Generation History

- Step 0
![step_0](images/step-0.png)

- step 1000
![step_1000](images/step-1000.png)

- step 3000
![step_3000](images/step-3000.png)

- step 18000
![step_18000](images/step-18000.png)

- step 80000
![step_80000](images/step-80000.png)