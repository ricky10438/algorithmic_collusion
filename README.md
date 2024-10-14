# Algorithmic Collusion with Reinforcement Learning: Evaluating Q-learning Robustness in Bertrand Duopoly Contexts

## Objective

This notebook applies Q-learning to explore the robustness of these algorithms when transferred to new market conditions, and analyses whether they lead to collusive outcomes.

## Key Features

- **Memoriless Agents**: Unlike the original repository [Algorithmic Collusion Replication by Matteo Courthoud](https://github.com/matteocourthoud/Algorithmic-Collusion-Replication), this implementation modifies the agents to be memoryless. In this variant, the agents no longer rely on past states beyond the current Q-values, ensuring that their strategies are shaped solely by present conditions.
- The robustness of the Q-learning algorithms is tested by transferring agents to different market environments (e.g., from low-cost to high-cost settings), examining their ability to adapt and achieve collusion.

## Citations

Original repository:

> Matteo Courthoud. Algorithmic Collusion Replication. Available at [https://github.com/matteocourthoud/Algorithmic-Collusion-Replication](https://github.com/matteocourthoud/Algorithmic-Collusion-Replication).

