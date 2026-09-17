# Connecting the Three Topics

## Control → RL

Classical control assumes a model and designs a feedback law.  
RL learns a policy (which can be seen as a controller) directly from interaction when the model is unknown or high-dimensional.

A PID controller is a very specific parameterized policy.  
An RL agent can learn more general (and potentially better) policies, especially under complex constraints and stochastic prices/PV.

## RL → Game Theory / Multi-Agent

Single-agent RL optimizes one reward.  
When multiple agents learn simultaneously, the environment becomes non-stationary from each agent's perspective. This is the multi-agent RL setting, which is closely related to game theory (repeated games, stochastic games).

## Game Theory in Energy Markets

P2P trading, aggregators, and demand-response programs are naturally game-theoretic.  
Mechanism design (auctions, pricing rules) determines the incentives that the agents respond to.

## Practical Engineering View

Real systems often combine:

- Low-level classical controllers (PID loops for inverters, battery management systems)
- Mid-level optimization / MPC
- High-level RL or rule-based energy management
- Market layer based on game-theoretic / auction mechanisms
