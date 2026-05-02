# Reinforcement Learning - Week 1 Lab  
## Multi-Armed Bandit Problem

## Overview
This repository contains the implementation of the Week 1 lab focused on the Multi-Armed Bandit problem in Reinforcement Learning. The objective of this lab is to understand the exploration vs exploitation trade-off and evaluate different action-selection strategies.

## Objectives
- Understand the Multi-Armed Bandit problem
- Implement action-value estimation methods
- Compare different strategies such as:
  - Epsilon-greedy method
  - Greedy method
- Analyze performance based on rewards over time

## File Structure
- `week1_bandit_lab.ipynb` : Jupyter Notebook containing implementation, experiments, and results

## Key Concepts
- Action-value methods
- Exploration vs exploitation
- Incremental update rule
- Reward estimation

## Methodology
The implementation follows these steps:
1. Initialize bandit environment
2. Select actions based on chosen strategy
3. Receive rewards from environment
4. Update estimated action values
5. Repeat for multiple iterations
6. Track and visualize performance metrics

## Results
- The results demonstrate how different strategies perform over time
- Graphs show average reward and optimal action selection
- Epsilon-greedy strategy balances exploration and exploitation effectively

## Requirements
- Python 3.x
- Jupyter Notebook
- NumPy
- Matplotlib

## How to Run
1. Clone the repository:
   git clone https://github.com/your-username/repository-name.git

2. Navigate to the project folder:
   cd repository-name

3. Open the notebook:
   jupyter notebook

4. Run all cells in `week1_bandit_lab.ipynb`

## Conclusion
This lab provides a foundational understanding of decision-making under uncertainty using bandit algorithms. It highlights the importance of balancing exploration and exploitation to achieve optimal performance.

## License
This project is for academic purposes.