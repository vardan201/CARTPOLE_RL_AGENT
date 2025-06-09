# 🧠 Deep Q-Learning Agent for CartPole-v1

This repository contains an implementation of a **Deep Q-Learning (DQL) agent** to solve the **CartPole-v1** environment using **OpenAI Gym** and **TensorFlow/Keras**.

---

## 📌 Project Overview

The goal of this project is to train a reinforcement learning agent to balance a pole on a cart using a neural network-based Q-learning approach.

**CartPole-v1** is a classic control problem where:

- The agent must prevent the pole from falling over.
- The episode ends when the pole falls or after 500 steps.
- A reward of +1 is given at each step the pole remains upright.

---

## 🚀 Features

- 🎯 Deep Q-Network (DQN) using Keras Functional API
- 🧮 Replay Buffer for stable training
- 🤖 Epsilon-Greedy Exploration strategy
- 🔄 Target Network soft updates


---

## 🧰 Technologies Used

- Python
- TensorFlow / Keras
- OpenAI Gym
- NumPy


---

## 🛠️ Setup Instructions

1. **Clone the repository**

```bash
git clone https://github.com/your-username/DQL-CartPole.git
cd DQL-CartPole
