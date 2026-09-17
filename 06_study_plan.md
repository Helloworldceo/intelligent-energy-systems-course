# Suggested Study Plan & Tips

## Rough timeline (part-time)

| Week | Focus |
|------|--------|
| 1–2 | Project 1 – fundamentals, model, ON/OFF, P, PI, PID, metrics |
| 3 | Project 1 – disturbances, experiments, Streamlit dashboard |
| 4–5 | Project 2 – MDP, environment, baselines, Q-Learning |
| 6–7 | Project 2 – DQN, PPO, evaluation, learning curves |
| 8 | Project 3 – classic games, Nash, double auction |
| 9 | Project 3 – Stackelberg, strategy comparison, market plots |
| 10 | Connections, interview prep, personal extensions |

## How to study each project

1. Read the theory notes in `docs/` **before** diving deep into the code.
2. Run `python -m src.main` and look at the numerical results and plots.
3. Change one parameter at a time (gains, battery size, price profile, number of agents…) and predict the effect before running.
4. Write down in your own words why the result changed.
5. Only after you can explain the baseline behavior should you start larger extensions.

## Tips for lasting understanding

- Always connect the equation to a physical or economic meaning.
- Prefer implementing a simple version from scratch before using a high-level library.
- Keep a personal notebook of “things that surprised me” and “things I still find confusing”.
- When something fails, ask *why* before changing the code.
- At the end of each project, try to explain the whole pipeline to an imaginary interviewer in 5–7 minutes.

## Bridging the three topics

After finishing all projects, try one of these synthesis exercises:

- Replace the PID in Project 1 with a small RL agent that learns the heater command.
- Turn the single-agent battery controller of Project 2 into multiple agents that also trade in the market of Project 3.
- Design a simple Stackelberg pricing layer on top of the RL energy management agent.

These exercises force you to see the relationships instead of treating the topics as isolated silos.
