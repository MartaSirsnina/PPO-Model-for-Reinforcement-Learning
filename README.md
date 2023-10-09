# PPO Model for Reinforcement Learning

![Training Graph](https://i.postimg.cc/SsLnq8df/image.png)

## Description
This repository contains the implementation of the Proximal Policy Optimization (PPO) model for solving reinforcement learning tasks. The PPO algorithm is used to train an agent to learn how to control a lunar lander in the LunarLander-v2 environment from OpenAI's Gym.

## Screenshots
![Game Screenshot](https://i.postimg.cc/C1C0rpHc/16-4-game.png)

## Requirements
- Python 3.x
- PyTorch
- NumPy
- Gym (Install using `pip install gym`)
- matplotlib

## Usage
1. Clone the repository:
   ```
   git clone <repository_url>
   cd <repository_name>
   ```
2. Run the PPO agent training script:
  ```
  python ppo_agent.py
  ```
You can adjust the hyperparameters and other settings by modifying the script or passing command-line arguments.

## Hyperparameters
You can modify the hyperparameters in the ppo_agent.py script to customize the training process. Here are some of the key hyperparameters:

- learning_rate: The learning rate for the actor and critic networks.
- batch_size: The batch size for training the networks.
- episodes: The number of episodes for training.
- replay_buffer_size: The size of the replay buffer.
- hidden_size: The number of units in the hidden layers of the actor and critic networks.
- gamma: The discount factor for future rewards.
- epsilon: The exploration rate.
- epsilon_min: The minimum value for the exploration rate.
- epsilon_decay: The rate at which the exploration rate decays.
- max_steps: The maximum number of steps per episode.
- target_update: The frequency at which the target actor network is updated.
  
## Results
You can visualize the training progress by plotting the training scores, losses, and other metrics. The training graphs can be found in the plt-<episode>.png files if you specify a RUN_PATH in the script.

## Acknowledgments
- This implementation is based on the Proximal Policy Optimization (PPO) algorithm.
- The LunarLander-v2 environment is provided by OpenAI's Gym.
Feel free to modify and improve upon this implementation for your own reinforcement learning tasks.

Happy Reinforcement Learning!
