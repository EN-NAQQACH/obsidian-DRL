A **Deep Q-Network (DQN)** is a value-based Deep Reinforcement Learning algorithm that uses a neural network to approximate the **Q-function**, which estimates the expected cumulative reward of taking a specific action in a given state.

Instead of storing Q-values in a table (which becomes impractical for large state spaces), DQN uses a **deep neural network** to predict: **Q(s,a)**

where:

- **s** = current state
- **a** = action
- **Q(s,a)** = expected future reward after taking action _a_ in state _s_