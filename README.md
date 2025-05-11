# deep-q-learning-gymnasium
Deep Q-Network (DQN) implementation for solving Gymnasium environments like LunarLander and Acrobot.



🧠 Deep Q-Networks (DQN) for LunarLander-v3 and Acrobot-v1:
This repository contains implementations of the Deep Q-Network (DQN) algorithm to solve two classic control problems from the Gymnasium library:
🚀 LunarLander-v3
🤸 Acrobot-v1
Both implementations follow the original DQN architecture with replay buffers, target networks, and epsilon-greedy exploration.

📂 Files:
Filename	Description:
DQN.ipynb	Colab notebook implementing DQN for both environments
Code includes	DQN model, replay buffer, training logic, and result visualization

⚙️ Dependencies:
To run this notebook, install the following packages:
pip install gymnasium torch matplotlib numpy
pip install swig
pip install "gymnasium[box2d]"
✅ Tested on Google Colab with Python 3.10+

🧪 Environments Used:
LunarLander-v3: Control a lander to land smoothly on a pad using engine thrust.
Acrobot-v1: A two-link pendulum system where the goal is to swing the end of the lower link to a target height.

🧱 Core Components:
DQN: A neural network approximator for Q-values.
ReplayBuffer: A cyclic buffer to store and sample past experiences.
select_action: Epsilon-greedy strategy to balance exploration and exploitation.
train and optimize_model: Functions for model updates based on minibatches from the replay buffer.
Logging: Episode reward averages and training losses are plotted for performance visualization.

📊 Results:
The notebook produces:
Average return over 100 episodes

Mean Squared Error (MSE) loss during training

Both metrics are visualized using matplotlib.

📌 Disclaimer:
This project was developed as part of a personal learning journey in reinforcement learning.
As such, it may contain experimental implementations, non-optimized code, or areas for improvement.
Feedback, suggestions, and contributions are always welcome!
