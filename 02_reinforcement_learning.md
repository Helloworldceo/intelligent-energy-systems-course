# Project 2 Guide – Reinforcement Learning for Solar + Battery EMS

**Repository:** https://github.com/Helloworldceo/rl-solar-battery-energy-management

## Stages Covered

1. RL fundamentals (agent, environment, state, action, reward, policy, value, Q-function)
2. Markov Decision Process formulation
3. Custom energy environment (PV, Load, Battery, Grid price)
4. Reward design
5. Baselines (random + rule-based)
6. Tabular Q-Learning
7. Deep Q-Network (DQN) with PyTorch
8. PPO
9. Evaluation (cost, peak demand, battery cycling, PV utilization)
10. Packaging

## Core MDP

**State example:** `[SOC, PV_generation, Load, Price, Time_of_day]`

**Actions:** Charge / Idle / Discharge (discrete) or continuous power setpoints

**Reward:** Negative electricity cost + penalties for constraint violations + bonuses for high self-consumption

## How to study

1. Start with the environment code and understand the transition and reward
2. Run the random and rule-based baselines
3. Train tabular Q-Learning on a discretized state space
4. Move to DQN and examine the loss / target network
5. Compare all agents on the same test days
