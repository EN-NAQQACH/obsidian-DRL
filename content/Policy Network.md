A **Policy Network** is a neural network that directly learns a **policy**, i.e., a mapping from states to actions. Instead of estimating the value of actions like DQN, it outputs the action (or the probability of each action) that the agent should take in a given state.

#### Key Idea

The network represents the policy:

π(a∣s)\pi(a\mid s)π(a∣s)

where:

- **s** = current state
- **a** = action
- **π(a|s)** = probability of choosing action _a_ in state _s_