 **PPO (Proximal Policy Optimization)** is an advanced **Actor-Critic** reinforcement learning algorithm developed by OpenAI. It improves training stability by preventing the policy from changing too much during each update.

### Main Idea

In standard Policy Gradient methods, large updates can make learning unstable. PPO solves this problem by **limiting how much the policy can change** after each training step.

State
  │
  ▼
Actor ──► Action
  ▲
  │
Critic ◄── Reward + Next State

Like Actor-Critic:

- The **Actor** learns the policy.
- The **Critic** evaluates the quality of actions.