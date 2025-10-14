# 📈 Reinforcement Learning Stock Trading Strategy

This project demonstrates how **Reinforcement Learning (RL)** can be applied to build an **automated stock trading strategy**.  
The notebook trains and evaluates RL agents that learn to make **Buy**, **Sell**, or **Hold** decisions based on **historical stock data**.

---

## 🚀 Features

- ✅ Implements multiple RL algorithms — **DQN**, **PPO**, and **A2C** using *Stable-Baselines3*  
- 🧩 Custom trading environment built using the **Gym** interface  
- ⚙️ **Data preprocessing** and **feature engineering** with *pandas* and *NumPy*  
- 📊 **Performance visualization** for portfolio value, rewards, and actions  
- 🔁 **Backtesting and strategy comparison** with baseline methods (Buy & Hold, Random)

---

## 🧠 Reinforcement Learning Overview

The RL agent interacts with a simulated trading environment in a continuous feedback loop:

| Component | Description |
|------------|-------------|
| **State** | Market indicators and technical signals (e.g., RSI, SMA, MACD, Bollinger Bands) |
| **Actions** | Buy, Sell, or Hold |
| **Reward** | Profit or loss resulting from each trade |
| **Goal** | Maximize cumulative portfolio return |

Agents learn optimal trading behavior by exploring actions and receiving feedback based on profitability.

---

## 🧰 Tech Stack

| Component | Library |
|------------|----------|
| **RL Framework** | [Stable-Baselines3](https://github.com/DLR-RM/stable-baselines3) |
| **Environment** | [Gymnasium](https://gymnasium.farama.org/) |
| **Data Handling** | pandas, numpy |
| **Visualization** | matplotlib, seaborn |
| **Data Source** | yfinance / local CSV |

---

## ⚙️ Installation

### 1️⃣ Clone the repository
```bash
git clone https://github.com/<your-username>/Reinforcement_Learning_Stock_Strategy.git
cd Reinforcement_Learning_Stock_Strategy
2️⃣ Install dependencies
pip install -r requirements.txt

3️⃣ Run the notebook


📊 Results:
The notebook outputs include:
📈 Portfolio growth curves over the evaluation period
🟢🔴 Trading actions (Buy/Sell/Hold) 
⚖️ Performance comparison against Buy & Hold and Random baseline strategies
📄 Evaluation metrics such as Total Return, Sharpe Ratio, and Max Drawdown
