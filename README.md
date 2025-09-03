# 🕹️ Atari Breakout – Deep Reinforcement Learning Agent

Welcome to my little corner of AI experiments.  
This project is all about teaching a computer how to play **Atari Breakout** using **Deep Reinforcement Learning (DRL)**.  
The end goal? Watching an agent that starts completely clueless eventually figure out how to smash bricks like a pro, just by trial and error.

---

## 🌟 Why Breakout?
Breakout is one of the classic Atari 2600 games. It’s simple to humans (move paddle, hit ball, break bricks), but for a computer, learning this from raw pixels is a surprisingly tough challenge.  
It makes a perfect playground for reinforcement learning:
- **Clear reward signals** (points when bricks break).  
- **Simple mechanics** (just left, right, or do nothing).  
- **Complex strategy** (angle control, ball tracking).  

This project shows how an agent can evolve from total randomness to something that actually looks *smart*.

---

## 🚀 Features
- Environment: [OpenAI Gym’s Breakout](https://gym.openai.com/envs/Breakout-v0/).
- Implements Deep Q-Network (DQN) with extensions like:
  - Frame skipping & grayscale preprocessing.
  - Experience replay buffer.
  - Epsilon-greedy exploration.
- Neural network for approximating Q-values directly from pixels.
- Save & load trained models to continue experiments later.
- Option to run in **training** or **evaluation** mode.

---

## 🛠️ Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/FlowerGodzilla/Atari-Breakout-ML.git
   cd Atari-Breakout-ML
