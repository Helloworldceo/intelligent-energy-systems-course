# Course Overview

## The Big Picture

```
Control Systems
      ↓
Optimization / Optimal Control
      ↓
Reinforcement Learning (single agent)
      ↓
Multi-Agent Systems
      ↓
Game Theory
      ↓
Intelligent Energy Systems
```

### Why this order?

- **Control Systems** teach you feedback, stability, and how to make a physical system behave as desired when the model is (approximately) known.
- **Reinforcement Learning** generalizes this to sequential decision making when the model is unknown or too complex, using trial-and-error and reward signals.
- **Game Theory** appears when multiple intelligent agents (households, prosumers, aggregators) interact and each optimizes its own objective.
- Real intelligent energy systems need all three.

## Learning Objectives (by the end)

You should be able to:

1. Explain open-loop vs closed-loop control and why feedback is essential.
2. Derive and discretize a simple thermal (or battery) model.
3. Implement PID from scratch and tune it.
4. Formulate an energy management problem as an MDP.
5. Implement Q-Learning and understand the Bellman equation.
6. Train a DQN and explain experience replay + target networks.
7. Understand the motivation for policy gradient methods and PPO.
8. Represent games in normal form and find pure/mixed Nash equilibria in small games.
9. Implement a simple double auction for P2P energy trading.
10. Explain Stackelberg (leader-follower) games with an energy example.
11. Discuss the relationship between single-agent RL and multi-agent RL / game theory.

## Time Estimate

- Project 1: 1–2 weeks (depending on depth)
- Project 2: 2–4 weeks
- Project 3: 1–3 weeks
- Connections + polishing: 1 week

Total: roughly 1.5–3 months of serious part-time work.
