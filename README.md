# Training Cartpole using Proximal Policy Optimization 

Using a Reinforcement Learning agent to solve the Cartpole problem.


## CartPole Problem 

A pole is attached by an un-actuated joint to a cart, which moves along a frictionless track. The system is controlled by applying a force of +1 or -1 to the cart. The pendulum starts upright, and the goal is to prevent it from falling over. A reward of +1 is provided for every timestep that the pole remains upright. The episode ends when the pole is more than 15 degrees from vertical, or the cart moves more than 2.4 units from the center.

The enviorment is imported using the <b>OpenAI</b> `gym` library 

## Solution 

We are using the Proximal Policy optimization algorithm to train the RL agent, 



## Libraries used 
1. `numpy`
2. `pytorch`
3. `matplotlib`
4. `gym`