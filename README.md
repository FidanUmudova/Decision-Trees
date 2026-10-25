# Decision Tree from Scratch (Machine Learning Specialization)

This repository contains Python implementations of core algorithms used in **Decision Trees**, developed as part of practical assignments. The project implements entropy calculation, dataset splitting, information gain computation, and optimal feature selection.

## Features Implemented

1. **Entropy Calculation (`compute_entropy`)**:
   - Computes the impurity of a node using Shannon entropy based on the proportion of positive examples ($p_1$).
   - Handles edge cases where data is empty or the node is completely pure ($p_1 = 0$ or $p_1 = 1$).

2. **Dataset Splitting (`split_dataset`)**:
   - Splits a node's active indices into left and right branches based on a specific feature's value ($1$ or $0$).

3. **Information Gain (`compute_information_gain`)**:
   - Calculates the reduction in entropy (information gain) achieved by splitting a node on a given feature, taking into account the weighted entropies of the child branches.

4. **Best Split Selection (`get_best_split`)**:
   - Iterates through all available features to find the one that yields the maximum information gain, determining the optimal feature to split on at each step.

## Technologies Used
- Python 3
- NumPy
- Jupyter Notebook
