# AI-driven Stock Market Prediction with Q-Learning

This project applies **Reinforcement Learning** (RL) using the **Q-Learning** algorithm to predict stock market movements. The goal is to create an intelligent agent that can decide when to **buy**, **sell**, or **hold** a stock based on historical price data. The agent learns by interacting with the market and optimizing its actions to maximize profits over time.

## Table of Contents

- [Introduction](#introduction)
- [Technologies](#technologies)
- [Setup Instructions](#setup-instructions)
- [Project Structure](#project-structure)
- [How to Use](#how-to-use)
- [License](#license)

## Introduction

This project demonstrates the application of **Q-Learning** in stock market prediction. The agent makes decisions based on historical stock prices and learns the best trading strategy (buy, sell, hold) to maximize its rewards (profits).

### Key Features:
- **Stock Trading Environment** created using OpenAI **Gym**.
- **Q-Learning** algorithm for the agent to learn the best trading strategy.
- Historical stock price data (e.g., Apple stock - AAPL) for training.
- Reward system based on profit and loss from trading actions.
- Visualizations to track the performance of the agent.

## Technologies

This project uses the following technologies:
- **Python 3.x** for programming.
- **Jupyter Notebook** for interactive coding and training.
- **yfinance** for downloading historical stock price data.
- **OpenAI Gym** for creating the trading environment.
- **Matplotlib** for visualizations.
- **Pandas** for data manipulation.
- **Numpy** for numerical operations.
- **Scikit-learn** for utilities like splitting datasets and evaluating the model.

## Setup Instructions

To get started with this project, follow these steps:

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/your-username/ai-driven-stock-market-prediction.git
    ```

2. Navigate to the project folder:

    ```bash
    cd ai-driven-stock-market-prediction
    ```

3. Install the required dependencies using `pip`:

    ```bash
    pip install -r requirements.txt
    ```

4. Open the Jupyter Notebook file:

    ```bash
    jupyter notebook AI-driven Stock Market Prediction with Q-Learning.ipynb
    ```

## Project Structure

The project has the following structure:

```plaintext
AI-driven-Stock-Market-Prediction-with-Q-Learning/
│
├── stock_trading_env.py       # Custom Stock Trading Environment using Gym
├── q_learning_agent.py        # Q-Learning Agent Implementation
├── stock_data.csv             # Historical Stock Data (AAPL)
├── AI-driven Stock Market Prediction with Q-Learning.ipynb  # Jupyter Notebook for AI-driven Stock Market Prediction with Q-Learning
└── README.md                  # Project documentation
