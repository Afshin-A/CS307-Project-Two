# CS307-Project-Two

My approach to solving this problem was using the Keras framework to train a neural network that approximates the optimal Q-values through many cycles. The game environment is represented by the `TreasureMaze` class, AI agent actions and outcomes are stored in the `GameExperience` class for experience replay. The `qtrain` function iterates through epochs, randomly selecting starting positions, executing actions based on exploration-exploitation strategy, and collecting experiences.
