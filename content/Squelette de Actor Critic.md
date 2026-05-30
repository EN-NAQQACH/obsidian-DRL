**Actor-Critic** is a reinforcement learning architecture that combines **policy-based** and **value-based** methods. It consists of two neural networks:

- **Actor:** chooses the action to perform.
- **Critic:** evaluates how good the chosen action is.

State
  │
  ▼
Actor ──► Action
  ▲
  │
Critic ◄── Reward + Next State