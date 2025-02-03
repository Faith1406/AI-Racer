# AI-Racer

## Overview

AI-Racer is a reinforcement learning-based racing game built using **Pygame** and **PyTorch**. The game leverages a Deep Q-Network (DQN) to train an AI agent to navigate a racing environment.

## Features

- Built with **Pygame** for game rendering.
- Uses **Deep Q-Learning** for AI training.
- Implements **Neural Networks** with PyTorch.
- Self-learning AI that improves over time.
- Tracks progress including best distance and time taken.

## Technologies Used

- Python
- Pygame
- PyTorch
- NumPy

## Installation

### Prerequisites

Ensure you have Python installed (>=3.7). Install dependencies using:

```bash
pip install pygame torch numpy
```

## Usage

Run the AI-Racer training script:

```bash
python main.py
```

## Game Mechanics

- The AI learns to navigate towards a **finish line**.
- **Reinforcement learning** principles are applied to optimize movement.
- The reward system encourages **shortest distance** and **fastest time** to completion.
- The AI updates using a **Deep Q-Network (DQN)** with experience replay.

## Training Details

- **State Space**: Player's x, y position.
- **Action Space**: Left, Right, Up, Down.
- **Reward System**:
  - Positive reward for getting closer to the finish line.
  - Large reward for reaching the finish.
  - Small penalty for time taken.

## File Structure

```
AI-Racer/
├── assets/             # Game assets (images, fonts)
├── main.py            # Main AI training script
├── utils.py           # Helper functions for game setup
├── README.md          # Project documentation
├── requirements.txt   # Required dependencies
```

## Future Improvements

- Implement different racing tracks.
- Add collision detection.
- Optimize neural network architecture for faster training.

## License

This project is licensed under the **MIT License**.

---

Developed by **Aditya** 🚀

I hoped that was interesting enough
