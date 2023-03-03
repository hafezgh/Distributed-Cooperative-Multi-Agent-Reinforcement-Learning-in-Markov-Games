# Distributed-Cooperative-Multi-Agent-Reinforcement-Learning-in-Markov-Games

## Team Q-Learning, Distributed Q-Learning, QD-Learning, and Networked Actor-Critic Algorithms for Cooperative Markov Games

In this project, we will consider distributed multi-agent reinforcement learning (MARL) in cooperative Markov games. We first consider a simple single-agent Q-learning algorithm to solve a single-agent MDP as a starting point. Afterwards, we will implement four MARL algorithms to solve multi-agent tasks modeled by cooperative Markov games. The first three algorithms are all value-based and include Distributed Q-Learning, Team Q-Learning, and QD-Learning. The first two algorithms do not require communication among agents for convergence but only converge in deterministic MDPs, while QD-Learning is communication-based. This algorithm and the fourth algorithm which is a communication-based actor-critic algorithm for cooperative agents maximize the sum of expected return of all agents.
