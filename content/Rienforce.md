**REINFORCE** is the simplest **Policy Gradient** algorithm. It learns a policy directly by increasing the probability of actions that lead to high rewards and decreasing the probability of actions that lead to low rewards.

### Main Idea

The agent:

1. Interacts with the environment.
2. Completes an entire episode.
3. Calculates the total reward obtained.
4. Updates the policy so that successful actions become more likely in the future.

The policy is represented by a neural network: πθ(a∣s)\pi_{\theta}(a\mid s)πθ​(a∣s)