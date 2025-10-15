# FrozenLake

#  FrozenLake Q-Learning Agent
This project implements a Q-Learning agent to solve OpenAI Gym’s FrozenLake-v1 environment. The agent learns to navigate the frozen lake, avoid holes, and reach the goal.
FrozenLake is a grid world where some tiles are safe (frozen) and others are dangerous (holes). The agent starts at S and tries to reach G. Movements can be slippery, so the agent must learn the best actions over time.
The Q-Learning algorithm builds a Q-table to store rewards for state-action pairs. Using exploration and exploitation, the agent improves its policy through repeated episodes until it can reliably reach the goal.
This project is a simple example of reinforcement learning and can be extended to larger grids or more complex environments.
##  Watch the Demo

![FrozenLake Q-Learning Demo](https://drive.google.com/uc?export=view&id=1LZKTGbIgM7ZLZP07Pz6UBKgCg1w989Hn)

##  Features

- **Q-Learning** implementation (Model-Free RL)
- Compatible with **Gym v0.26+**
- Adjustable hyperparameters: learning rate, discount factor, exploration rate
- Visualizes agent performance using `render()`
- Works in **Python 3.8+** and **Jupyter Notebook**

##  About FrozenLake

- 4x4 or 8x8 grid environment  
- Start at **S** and goal is **G**  
- Some tiles are frozen (**safe**) and some are holes (**H**)  
- Slippery surface introduces randomness in movement

## 🔧 Installation

```bash
# Clone the repository
git clone https://github.com/YourUsername/FrozenLake-QLearning.git
cd FrozenLake-QLearning

# (Optional) Create a virtual environment
python -m venv rl_env
source rl_env/bin/activate   # Linux/Mac
rl_env\Scripts\activate      # Windows

# Install dependencies
pip install gym numpy ipython matplotlib
