# Exploring Autonomous Driving Environments with Reinforcement Learning

This repository contains projects experimenting with OpenAI's Gymnasium environments provided by Farama Foundation. The goal is to explore the application of various reinforcement learning algorithms to autonomous driving tasks and understand how games could use RL.

## Project Overview

In this repository, we experiment with different reinforcement learning algorithms on the intersection and racetrack environments. Each file demonstrates the use of specific algorithms and provides insights into their performance and behavior.

## Files and Descriptions


https://github.com/suriyakumar99/highway-env-RL-agents/assets/68340831/3a7f3022-f3b0-4655-b104-2148c5005fe6


### Intersection Environment with DQN and PPO [![Intersection Environment with DQN and PPO](https://img.shields.io/badge/Colab-Open%20Notebook-brightgreen)](https://colab.research.google.com/drive/1AeU6BVIzq9GTLoolLnmTxiBQNjmGY8gB?usp=sharing)
- **Description**: This notebook explores the intersection environment using Deep Q-Network (DQN) and Proximal Policy Optimization (PPO).
  - **Deep Q-Network (DQN)**: Uses Q-learning with a neural network to approximate the state-action value function \(Q\).
  - **Proximal Policy Optimization (PPO)**: A policy gradient method optimizing a surrogate objective function.
  - **Inference**: PPO converged faster and more reliably than DQN, which had fluctuating performance initially but improved over time.

### Racetrack Environment with SAC [![Racetrack Environment with SAC](https://img.shields.io/badge/Colab-Open%20Notebook-brightgreen)](https://colab.research.google.com/drive/1FfF2ooxqawPJU4_kIxYIdswmeDzXi0mx?usp=sharing)


https://github.com/suriyakumar99/highway-env-RL-agents/assets/68340831/7b4d09b2-ea65-4f04-8803-95a99b53fe02


- **Description**: This notebook demonstrates the use of Soft Actor-Critic (SAC) in the racetrack environment.
  - **Soft Actor-Critic (SAC)**: An off-policy actor-critic algorithm that balances exploration and exploitation by maximizing entropy.
  - **Inference**: SAC showed robust performance, effectively managing the continuous action space of the racetrack environment.

### Racetrack Environment with DDPG [![Racetrack Environment with DDPG](https://img.shields.io/badge/Colab-Open%20Notebook-brightgreen)](https://colab.research.google.com/drive/1hzUeCpAX8cVdm9jnq584jCfzkGABKpPb?usp=sharing)
- **Description**: This notebook applies Deep Deterministic Policy Gradient (DDPG) to the racetrack environment.
  - **Deep Deterministic Policy Gradient (DDPG)**: Combines the advantages of DQN and policy gradient methods for continuous control.
  - **Inference**: DDPG demonstrated high precision and stability, efficiently learning to navigate the racetrack.


## Contributing

Feel free to fork this repository, make improvements, and submit a pull request. Your contributions are welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
