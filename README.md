## CartPole Reinforcement Learning Project

This project implements and experiments with Reinforcement Learning (RL) algorithms to solve the classic CartPole balancing task from OpenAI Gym. We demonstrate how to train, evaluate, and compare different RL agents using Stable-Baselines3.

### 📂 Project Structure

```
├── CartpoleRL (1).ipynb   # Jupyter Notebook with full implementation and experiments
└── README.md              # This file
```

### 🔑 Key Features

- **Environment:** Uses the `CartPole-v1` environment from OpenAI Gym.
- **Algorithms:** Implements two popular RL algorithms:
  - **Deep Q-Network (DQN)**
  - **Proximal Policy Optimization (PPO)**
- **Training:** Train agents with configurable hyperparameters directly within the notebook.
- **Evaluation:** Plot training learning curves (episode reward over time) and compare performance of different agents.
- **Visualization:** Render the CartPole environment to visually inspect agent behavior after training.


### 📊 Results

- **Learning Curves:** Visual comparison of episode rewards for DQN vs PPO.
- **Final Performance:** Average reward over 100 evaluation episodes for each agent.
- **Agent Behavior:** Example animation of a trained agent balancing the pole for 500+ timesteps.

### 📋 Requirements

- Python 3.7+
- `gym`
- `stable-baselines3`
- `numpy`, `matplotlib`

You can install them via:

```bash
pip install gym stable-baselines3 numpy matplotlib
```

### 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to open an issue or submit a pull request.

---

*Developed by Houssem Aridhi*

