# Neural Network experiments
This Jupyter Notebook contains two experiments related to Neural Networks and Reinforcement Learning, covering Q-learning for a maze navigation problem and Backpropagation Algorithm (BPA) for XOR classification.

# Experiment 10: Credit Assignment Problem using Q-Learning

Objective: Implement Q-learning to solve a maze navigation problem where an agent (traveler) learns the optimal path using reinforcement learning.

Rules:
The traveler can move in eight directions (up, down, left, right, and diagonals).
The maze consists of open paths (" "), walls ("#"), and a goal ("G").
Rewards System:
+100 for reaching the goal (G).
-100 for hitting obstacles (#).
-1 for each movement to encourage efficiency.

Implementation Steps:
1. Define the maze as a grid.
2. Set up a reward structure.
3. Implement the Q-learning algorithm.
4. Train the agent to optimize its path.
5. Visualize the learned policy.

# Experiment 11: Backpropagation Training Algorithm for XOR Problem

Objective: Design and simulate a Backpropagation Algorithm (BPA) to train a multi-layer perceptron (MLP) for solving the XOR classification problem.

Problem Statement: The XOR function is not linearly separable, requiring a hidden layer for successful training.

Implementation Details:

A 3-layer Neural Network:
1. Input Layer: 2 neurons (for XOR input pairs)
2. Hidden Layer: 2 neurons (to capture non-linearity)
3. Output Layer: 1 neuron (binary classification)
4. Activation Function: Sigmoid function for non-linearity.

Training Algorithm:
1. Forward Propagation: Compute the hidden and output layer activations.
2. Error Calculation: Compare predicted vs. actual output.
3. Backpropagation: Adjust weights using gradient descent.
4. Repeat for 10,000 epochs to minimize error.

Final Results:
The model successfully learns the XOR function.
Outputs approach expected values (0 for [0,0] and [1,1]; 1 for [0,1] and [1,0]).

# Requirements
Python
Jupyter Notebook
Libraries: NumPy, Pandas, Matplotlib (if visualization is included)

