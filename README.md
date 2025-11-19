# snake-rl-agent

# 🐍 Deep Q-Learning Snake AI  
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)]()
[![PyTorch](https://img.shields.io/badge/PyTorch-2.x-red)]()
[![Reinforcement Learning](https://img.shields.io/badge/RL-DQN-green)]()
[![Status](https://img.shields.io/badge/Status-Training%20Agent-orange)]()

---

## 📌 Project Overview
This project implements a **Deep Q-Learning (DQN)** agent that learns to play the classic **Snake** game from scratch using **Reinforcement Learning** and **PyTorch**.

The agent improves over time by:
- Receiving rewards for eating food (+10)
- Getting penalized for dying (-10)
- Learning long-term strategies via discounted future rewards
- Using experience replay and epsilon-greedy exploration

The entire training pipeline (environment, agent, model, trainer) is implemented manually to help understand RL fundamentals.

---
## 🎥 Demo Video

[![Watch the video](https://img.youtube.com/vi/0O4_kOa5LJM/0.jpg)](https://youtu.be/0O4_kOa5LJM)


---

## 🚀 How to Run
### 1. Install Requirements
Make sure you have the dependencies installed:

```bash
pip install torch pygame numpy matplotlib
```

## 📌 Project Overview
This project implements a **Deep Q-Learning (DQN)** agent that learns to play the classic **Snake** game from scratch using **Reinforcement Learning** and **PyTorch**.

The agent improves over time by:
- Receiving rewards for eating food (+10)
- Getting penalized for dying (-10)
- Learning long-term strategies via discounted future rewards
- Using experience replay and epsilon-greedy exploration

The entire training pipeline (environment, agent, model, trainer) is implemented manually to help understand RL fundamentals.

---

## 📌 How to Run
To start training the RL agent:

1. **Open the Notebook**
main.ipynb
**Run All Cells**


Running all cells will:
- Start training the RL agent  
- Display live score and mean score graphs  
- Automatically save the best model weights  

---

## 🧠 How It Works
The project is built using **Deep Q-Learning (DQN)**, where a neural network predicts the best action for the Snake agent based on the current game state.

DQN enables the agent to learn over time by:
- Evaluating the quality (Q-value) of each possible action  
- Learning from rewards and penalties  
- Storing past experiences in memory  
- Sampling these experiences to train more effectively  

---

## ⚙️ DQN Components

### ✔️ Neural Network Architecture
Input:   11-dimensional state vector
Hidden:  256 neurons (ReLU activation)
Output:  3 Q-values (straight, right, left)


## 💾 Model Saving
The best-performing model is automatically saved to:

---

## 📜 License
This project is open-source and available for learning, modification, and extension.

---

## ❤️ Contribute
If this project helped you, please consider ⭐ **starring the repository**.  
Pull requests and ideas for improvements are always welcome!

---

