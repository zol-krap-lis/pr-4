
# Tic Tac Toe with Q-Learning

This project implements a simple Tic Tac Toe game with a Q-Learning agent that learns to play optimally. The agent is trained over multiple episodes to improve its decision-making based on rewards.

## Installation

To run the program, ensure you have Python installed along with the following libraries:
```bash
pip install numpy matplotlib
```

## How to Run

1. Save the code in a file named `tic_tac_toe.py`.
2. Execute the file:
   ```bash
   python tic_tac_toe.py
   ```
3. The program will display the game board at each step and plot the rewards after training.

## Features

- **Game Logic:** A complete implementation of Tic Tac Toe with the ability to check for winners and valid moves.
- **Q-Learning Agent:** The agent uses Q-Learning to learn optimal strategies for playing the game.
- **Visualization:** The learning process is visualized through a reward plot.

## File Structure

- `tic_tac_toe.py`: Contains the complete implementation of the game and Q-Learning agent.
- `README.md`: Instructions for running the project.

## Parameters

- `episodes`: Number of training episodes (default: 1000).
- `alpha`: Learning rate for Q-Learning.
- `gamma`: Discount factor for future rewards.
- `epsilon`: Exploration rate for ε-greedy policy.

## Example Output

During training, the program displays the game board and plots the rewards to visualize learning progress.

![Reward Plot](images/rewards_plot.png)

## Acknowledgments

This project demonstrates reinforcement learning principles in a simple environment and is an educational example for beginners.
