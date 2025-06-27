# Reinforcement Learning with LunarLanderContinuous-v3

This project showcases the use of two popular reinforcement learning algorithms — Deep Q-Networks (DQN) and Proximal Policy Optimization (PPO) — to train agents to solve the `LunarLanderContinuous-v3` environment from OpenAI Gymnasium.

## 📁 Project Structure

- `DQN_LunarLanderContinuous-v3.ipynb` — Jupyter notebook implementing and training a DQN agent on a continuous environment (note: DQN is natively designed for discrete action spaces, so this version includes discretization logic).
- `PPO_LunarLanderContinuous-v3.ipynb` — Jupyter notebook implementing and training a PPO agent, which naturally supports continuous action spaces.

## 🚀 Environment

- **Environment**: `LunarLanderContinuous-v3`
- **Library**: [Gymnasium](https://gymnasium.farama.org/)
- **RL Algorithms**:
  - **DQN** (with discretization for continuous actions)
  - **PPO** (from [Stable-Baselines3](https://github.com/DLR-RM/stable-baselines3))

## 📦 Requirements

Install dependencies via:

pip install stable-baselines3[extra]
pip install gymnasium[box2d]

# Reinforcement Learning with Blackjack-v1

This project explores reinforcement learning techniques applied to the classic card game environment `Blackjack-v1` from OpenAI Gymnasium. The focus is on training agents using on-policy Temporal Difference learning with the SARSA algorithm.

## 📁 Project Structure

- `Blackjack_SARSA.ipynb` — Jupyter notebook implementing and training a SARSA agent on the discrete `Blackjack-v1` environment.
- `Blackjack_MonteCarlo.ipynb` — Jupyter notebook implementing and training a agent with Monte Carlo on the discrete `Blackjack-v1` environment.

## 🚀 Environment

- **Environment**: `Blackjack-v1`
- **Library**: [Gymnasium](https://gymnasium.farama.org/)
- **RL Algorithm**:
  - **SARSA** (State-Action-Reward-State-Action)

## 📦 Requirements

Install dependencies via:

pip install gymnasium

Make sure you have Python 3.8+.
