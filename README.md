# Intelligent Energy Systems Course

**Control Systems → Reinforcement Learning → Game Theory**

A complete, practical course that builds the skills needed for intelligent energy systems (microgrids, EMS, P2P markets, battery control).

## Projects (all improved & executable)

| # | Topic | Repository | What you get |
|---|-------|------------|--------------|
| 1 | Control Systems | [smart-hvac-control-system](https://github.com/Helloworldceo/smart-hvac-control-system) | Room model, ON/OFF→PID, disturbances, metrics, plots, Streamlit dashboard |
| 2 | Reinforcement Learning | [rl-solar-battery-energy-management](https://github.com/Helloworldceo/rl-solar-battery-energy-management) | Energy env, Q-Learning, DQN, PPO, learning curves, cost/peak/self-consumption metrics |
| 3 | Game Theory | [game-theoretic-p2p-energy-market](https://github.com/Helloworldceo/game-theoretic-p2p-energy-market) | Nash solvers, double auction, strategy comparison, Stackelberg, market plots |

## How to run any project

```bash
git clone <repo-url>
cd <repo>
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
python -m src.main
```

## Learning Path

1. **Control** – understand feedback, modeling, PID, performance metrics
2. **RL** – sequential decisions under uncertainty, value functions, deep RL
3. **Game Theory** – strategic interaction, markets, multi-agent thinking
4. **Connections** – how the three layers work together in real energy systems

See the Markdown guides in this repository for detailed explanations and interview-style questions.

## Status

All three projects are fully executable and produce numerical results + plots out of the box.
