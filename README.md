# Optimizing Beta Value in β-VAE using N-arm-bandit and Simulated Annealing

As part of a collaborative project, we worked on β-VAE, a variation of VAE (Variational Autoencoder) and proposed a framework to optimize
the β value of β-VAE automatically during the training time.
β-VAE is proposed to improve distentangled representation learning in a complete unsupervised approach. However, the β value from β-VAE is completely
dataset dependent, and the model is not truly trained unsupervised if it is not learned automatically. In this paper, we
propose an n-arm-bandit and Simulated Annealing based β optimization technique, which learns the β value automatically based on the update of the loss function. Our approach improved the image generation performance of VAE but lostreconstruction accuracy slightly.

This project was submitted as part of the Advanced Machine Learning class taught by Professor Ricardo Vilalta at the University of Houston Spring 2022
