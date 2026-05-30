The Critic computes the **TD Error**, which measures the difference between the predicted value and the observed value:

δ=r+γV(s′)−V(s)

where:

- **r** = reward received
- **γ** = discount factor
- **V(s)** = current state's value
- **V(s')** = next state's value
- **δ** = TD Error