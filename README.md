# Singe-Neuron-Learning-Life-cycle
A step-by-step demonstration of a single forward pass, loss calculation, and backpropagation cycle in a simple neural network

This project provides a foundational, step-by-step computational demonstration of the single learning cycle within a minimal $3 \times 2$ neuron neural network. The primary objective is to demystify the core mechanism that drives all deep learning: how a network identifies a mistake and precisely calculates the required corrections to its internal parameters (weights).

Methodology

Using a simplified architecture, the project meticulously tracks one full iteration of learning:

Forward Pass: Calculating the initial output guess.

Loss Quantification: Determining the magnitude of the mistake using the Mean Squared Error (MSE).

Backpropagation: Applying the Chain Rule of Calculus to derive the Gradient ($\mathbf{dLoss/dW}$) matrix, which assigns responsibility for the loss to every single weight.

Gradient Descent: Adjusting the weights using a fine-tuned Learning Rate to minimize the loss.Key TakeawayThe successful execution confirms the mathematical validity of the Gradient Descent process, proving that even the simplest network can intelligently modify its knowledge.

The project serves as a crucial reference for understanding the "heartbeat" of a neural network before scaling up to complex, multi-layered architectures.
